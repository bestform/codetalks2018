# code.talks 2018

![](IMG_0586.jpg)

## Der Aufhänger

ESONO bietet seinen Entwicklern pro Jahr fünf RnD (Research and Development) Tage an. In diesen Tagen kann jeder Entwickler selbst entscheiden, mit was er sich gerne beschäftigen würde. Eine Option ist auch der Besuch einer Konferenz. Ein Kollege und ich entschieden uns für letzteres und ich will ein paar Worte über unsere Erfahrung dort verlieren.

Alle Meinungen und Bewertungen über Sachverhalte, Talks und Teilnehmer sind natürlich meine ganz persönlichen und repräsentieren nicht zwangsläufig die Einstellung von ESONO und dessen Mitarbeiter.

## Die Veranstaltung

![](IMG_0645.jpg)

Die code.talks sind eine non-profit Veranstalung, die sich an Entwickler aus allen Bereichen wendet. Durch die aktuelle IT Landschaft konzentrierten sich viele Talks aber auf den Bereich der Webentwicklung.

Die Veranstaltung wird finanziert von Sponsoren und AboutYou. Es werden auch kostenlose Tickets an Studenten und Programmierer in der Ausbildung gegeben, um den Nachwuchs zu fördern. Das Konzept ist sehr zu begrüßen und sorgte dafür, dass das Publikum nicht nur aus Abgesandten großer Firmen bestand.

![](IMG_0644.jpg)

Auch wenn es auffällt, dass beispielsweise im Vergleich zu der jährlichen Symfony Live durchaus einige weibliche Mitglieder der Community anzutreffen waren, beklagte der Veranstalter bei der Eröffnung das immer noch eklatante Geschlächterverhältnis. Die Veranstaltung gibt sich sehr viel Mühe, unterrepräsentierte Gruppen besser zu fördern und auf der Veranstaltung zu begrüßen. Das gelinge allerdings trotz starker Bemühungen immer noch nicht zufriedenstellend.

## Die Location

Die code.talks fanden - wie jedes Jahr - in einem Cinemaxx Kino statt. Ein Kino ist im Grunde ein sehr guter Ort für eine derartige Veranstaltung, da es viele große Räume für Vorträge gibt. Diese haben sensationell große Leinwände für die Slides und ein gutes Bilckfeld für jeden Besucher. 

![](IMG_0604.jpg)

Kinosessel sind für einen zwei Stunden langen Film vielleicht noch in Ordnung, wenn man allerdings zwei Tage hintereinander insgesammt gefühlte 80000 Stunden in ihnen verbringt, schwindet die Begeisterung ein wenig. Gepaart mit schindendem Sauerstoffgehalt in der Luft und fehlendem Sonnenlicht, stellt das ganze dann eine Herausforderung der ganz besonderen Sorte dar. 

## ESONO bei den code.talks

ESONO schickte einen Kollegen und mich zu der ausverkauften Veranstaltung 2018.

Laut Veranstalter gab es mehrere hundert Entwickler auf der Warteliste für Tickets. Diese müssen sich allerdings wirklich auf den letzten Drücker angemeldet haben, da auch ESONO die Tickets erst in der Woche der Veranstaltung online bestellte. 

## Die tracks

Die Veranstaltung bot insgesamt 16 Tracks an, die von Mobile, über Management bis zu Security reichten und im Grunde das komplette Spektrum der Entwicklerszene abdeckten. Pro Slot gab es 8 parallele Tracks, was durchaus zu einigen Konflikten führen konnte, auch wenn die Track hinreichend unterschiedlich waren, sodass man ein einigermaßen konsistentes Konferenzprogramm zusammenstellen konnte, ohne auf persönliche must-see Vorträge verzichten zu müssen.

Die Talks, die hier vorgestellt werden, sind diejenigen, für die ich mich entschieden habe. Über die anderen kann ich leider nichts sagen. Diese wurden zwar aufgezeichnet, aber wann und ob diese veröffentlich werden, konnte mir niemand so recht beantworten.

## Welcome Speech

Kino 1, voller Raum, große Leinwand. Einer der Organisatoren stellt die Veranstaltung vor und sagt im Grunde das, was ich bereits in der Einleitung zu diesem Post beschrieben habe.

Auch wenn der Talk einige interessante Punkte und Informationen enthielt, geriet er für mich doch etwas zu lang.

![](IMG_0587.jpg)

Es wurden auch die Tracks einzeln vom dem jeweiligen Kuratoren vorgestellt. Das ist im Prinzip eine gute Idee, allerdings artete es ein bisschen in eine trockene Aufzählung der Vortäge aus. Das war redundant und nicht informativ. Dennoch begrüße ich diese Art der Einführungsveranstaltung. sie ist ein guter Einstieg, der die Motivation und das Konzept einer Konferenz zeigt.

## All your money belongs to us (me)

#### Denis Hamann - Netlight Consulting GmbH

Auf vergangenen Veranstaltungen des Chaos Computer Clubs hat man bereits sehr interessante Vorträge zum Thema gesehen: Das Kompromittieren von Mobile Banking Apps.

Einen ähnlichen Vortrag hatte ich mir hier erwartet und wurde leider ein wenig enttäuscht.

Der beschriebene Angriff - am Beispiel der PayPal App - nutzte Code Injection zu Runtime.

![](IMG_0590.jpg)

Hier wird im Grunde direkt Java Code der laufenden App manipuliert. Das ist natürlich nur durch die Kompromittierung des Gerätes möglich, wogegen die App nicht wirklich etwas unternehmen kann, selbst wenn sie wollte. Aber Denis bemerkt, dass das vor allem ein PR Desaster für den Anbieter darstellt, was ein einteressanter Punkt ist. Konsumenten ist es egal, wie absurd der Angriff ist. Wenn er gezeigt wird, ist es das Problem des Anbieters.

Wichtigster Hinweis des Vortrags zum Schutz vor derartigen Angriffen: Update your Phones!

Und da ich das auch noch mal betonen will, hier noch mal: Update. Your. Phones! Srsly. 

Dementsprechend sind auch hauptsächlich alte, niemals aktualisierte Android Telefone anfällig, oder wie Denis es nennt: "cheap china phones".

Denis blieb beim gesamten Vortrag oberflächlich und gab einen nur im Ansatz technischen Einblick in die Methoden. Das ist kein Problem von Denis' Vortrag sondern von meinen Erwartungen. 

## Predictive Analytics with Big Query

#### Christopher Denk - Google

#### Ksenia Nekrasova - Google

Ja, auch google war mit meheren Vorträgen bei den code.talks. Im Grunde wollte google hier ihre neuen Produkte im Bereich ML vorstellen.

![](IMG_0592.jpg)

Dieser Vortrag hatte allerdings den Fokus auf Big Query und wie man die Google Cloud zum analysieren riesiger Datenmengen nutzen kann.

Als Beispiel nahmen Ksenia und Christopher einen Hotelbetrieb, der seine Kunden besser analysieren möchte, um den Service zu verbessern.

Als Datenquellen dienten ein Loyality Program, Website Analytics, Hotel Properties und Room bookings. Alle Daten wurden zusammengesammelt und in ein google data warehouse gekippt. Das ganze System kann mit Daten von mehreren Petabytes umgehen. Dafür werden die Tables in einzelne Shards aufgeteilt, um sie besser skalieren zu können.

![](IMG_0593.jpg)

Die Daten liegen als semi-structured data types vor in Form von Structs und Arrays. Sie haben ein "Partial schema", was meines Erachtens nach "haben halt die selbe Form, haben wir aber nicht so wirklich definiert" klingt. Da sollte man sich wohl mal tiefer mit beschäftigen.

Wichtige Daten für das Hotel waren zum Beispiel Searchterms (honeymoon, cheap hotel, parking opportunities). Dadurch findet man die Zielgruppen (Business, Couples, Family...) und man in der Folge personalisierte Newsletter generieren.

Der Vorteil dabei, solche Analysen in der Google Cloud zu machen, liegt natürlich darin, sich nicht um Infrastruktur und Skalierbarkeit kümmern zu müssen.

In der Folge wurde noch die Beta von BQML vorgestellt. Das ML darin steht - natürlich - für Machine Learning.

Das Beispiel hier waren Kunden, die nicht angegeben haben, ob sie verheiratet sind. Daraufhin wurde in der Cloud trainiert und dann die fehlenden Angaben ergänzt. Spooky. 

![](IMG_0594.jpg)

Insgesamt war das ein schöner Talk mit Live Demo und kompetenten Speakern.

## A day in the life of a security consultant - Story telling around DDoS and web attacks

#### Gerhard Giese - Akamai

Gerhard fing gleich mal mit den berühmt berüchtigten 419 Scam Mails an. Das sind die mit dem Millionen Erbe aus Nigeria, dessen glückliche Empfänger wir sind. Er ließ es sich auch nicht nehmen, dabei auf das sensationelle 419eater.com hinzuweisen.

![](IMG_0596.jpg)

Erstaunlicherweise sind diese Scam Mails - so absurd und offensichtlich sie sind - bis heute erfolgreich. Es gibt immer noch Opfer, die darauf hereinfallen. Sein Fazit dazu: "Gier ist ein schlechter Berater".

Desweiteren stelle Gerhard eine Drohung vor, die mir bisher noch nicht untergekommen ist, die aber wohl auch verbreitet ist: Zahle oder DDoS. Auf die Frage, ob man denn zahlen sollte, meinte er, dass dann nur der nächste kommen würde, da es einfach zu viele socher Kiriminellen gibt. Er würde aber nicht so weit gehen, sie als vernetzt anzusehen, nach dem Motto: "Schau mal, der hat bei mir gezahlt, greif den mal an!"

![](IMG_0598.jpg)

Am häuigsten wird Retail Opfer dieser Angriffe.

Gerhard stellte außerdem den schöner Angriffsvektor vor: Sonos hacken und darüber Alexa steuern. Next Level: Per Ultraschall mit Siri sprechen. Das klingt lustig und abgefahren, ist aber ein realer Angriff.

Sein Rat: Als Programmierer den Hut abnehmen und die Hacker Basecap aufsetzen. Mal aus der Box steigen. Das ist sicherlich ein guter Hinweis, den so einige Entwickler mal beherzigen sollten.

![](IMG_0601.jpg)

Ein sehr unterhaltsamer und informativer Talk. 

## Software Qualität === Gesundheit

#### Roland Golla - Never Code Alone

Roland erlitt vor einiger Zeit einen Nervenzusammenbruch. Als Auslöser beschrieb er im Grunde das, womit so ziemlich jeder Entwickler tagtäglich zu kämpfen hat:

Es kommen immer mehr Tickets, immer mehr Bugs, die Arbeit wird zur Kesselflickerei, weil ja keine Zeit für gescheite Lösungen da ist, das führt zu noch mehr Bugs, noch mehr Tickets etc.

![](IMG_0608.jpg)

Das klingt übertrieben, aber so ist es leider in vielen Betrieben.

Außerdem gibt er den guten Hinweis: Wenn du nur alten Legacy Code fixt, bist du nichts mehr Wert auf dem Markt, da Technologie voran schreitet, du selbst aber nicht. Das ist ein Hinweis, der sich durch die gesamte Veranstaltung und durch mehrere Talks hindurchzieht. Es scheint sich also wirklich um ein vorherrschendes Problem in der Entwicklerszene zu handeln. Entwickler verheizen sich mit dem Flicken alten Codes und werden dadurch nicht nur depressiv, sondern nehmen sich nach und nach auch immer mehr die Möglichkeit, am Markt noch mal zu was besserem zu kommen.

![](IMG_0610.jpg)

Bekämpft den Burn Out, fordert gute Bedingungen ein, schaut auf euch und eire Gesundheit. Mehr kann ich dazu auch nicht sagen.

## Hilfe - Kind im Brunnen: Systematisch technische Schulden abbauen

#### Gernot Starke - INNOQ

Gernot wurde mir im Vorfeld bereits empfohlen als guter Speaker und Mensch mit Anhnung. Ich habe seine Bücher bisher nicht gelesen, aber nach dem Vortrag sind sie auf jeden Fall auf meiner Liste gelandet.

![](IMG_0612.jpg)

Es geht wie so oft um alte Systeme, die in einem Wust von Abhängigkeiten, Gluecode und Legacycode untergehen. Es wird versucht, Systeme zu integrieren und dabei wird außer Acht gelassen:

"Integrationsprojekte kann man entweder schnell machen, oder gut."

Das Management hat bei einem Integrationsprojekt die beiden Ziele: Termin einhalten und Budget nicht überschreiten. Diese Ziele sprechen gegen das Ziel des Engineerings, eine wartbare und gute Lösung zu entwickeln.

![](IMG_0613.jpg)

Gerard stellt sein eigenes System aim42.org vor, das dabei helfen soll, derartige Projekte vernünftig zu planen.

Ein wichtiger Punkt, den er anspricht, ist, dass Problemraum und Lösungsraum voneinander getrennt werden müssen. Zu oft denken gerade Entwickler direkt in Lösungen - was nicht verwunderlich ist, da genau das ihr Job ist. 

Und auch Gernot spricht das wiederkehrende Thema an:

"Ohne Innovation sinkt der Marktwert der Entwicker!"

![](IMG_0614.jpg)

Um ein System zu verbessern, muss man Verbesserungen mit dem Tagesgeschäft kombinieren. Es muss eine kontinuierliche Architektur-Modernisierung stattfinden.

Änderung braucht Zeit, der Erfolg muss nachweisbar sein über die Zeit. Beweise dem Management, dass die Änderungen kontinuierlich zu Verbesserung führen.

## 1's and 0's: Golang and WebAssembly

#### Guus van Weelden - Loodse

Guus beschreibt in seinem Talk das experimentelle Feature des WebAssembly compliation targets in go 1.11. 

![](IMG_0616.jpg)

WebAssembly ist ein Binary Instruction Format für den Browser, das im Vergleich zu JavaScript eine kleinere Dateigröße und eine schnellere Ausführung bietet. Das mit der kleineren Dateigröße ist aber aktuell bei wasm Modulen, die aus go kommen, noch nicht wirklich gegeben, da diese immer mindestens 2MB groß sind. Dafür genießt man die Vorteile von go, also zum Beispiel bestehende Libraries und Typensicherheit.

Theoretisch ist es dadurch auch möglich, den selben Code im Frontend und Backend zu verwenden (code sharing). Das ist aber etwas, das in meiner Erfahrung immer nur im theoretischen Beispiel (Input Validation) vorkommt und in der Praxis so gut wie nie hilfreich ist. Frontend und Backend sind zwei derart unterscheidliche Welten, da ist fehlendes Codesharing das letzte Problem, das mit einfällt.Effektiver, Standardisiert, Sandboxed, Support für mehr Sprachen

WebAssembly unterstützt aktuell noch keine nativen DOM APIs. Hierfür muss noch Gluecode herhalten.

Außerdem besteht noch kein Multithreading support.

Ich werden später noch ein mal etwas auf WebAssembly eingehen in einem späteren Talk.

## Building smarter apps with Machine Learning, from magic to reality

#### Laurent Picard - Google

Wieder ein Vortrag von google, dieses mal mit dem sehr sympatischen Franzosen Laurent Picard. Er sprach über die Machine Learning APIs (Image, Text, Speech) von google.

![](IMG_0628.jpg)

Das besondere an seinem Talk war, dass er das Publikum mit einbezog, was sehr sehr mutig ist. Das Publikum war aber dankbar und bestrafte ihn nicht für seinen Mut. 

Für die Visions API ließ er die Besucher Selfies hochladen, die dann mit einem Schnurrbart versehen wurden. Außerdem interpretierte die API die aktuelle Laune des Besuchers und gab Statistiken aus.

![](IMG_0630.jpg)

Für die Translation API ließ er sich dann Texte schicken, die nach Englisch übersetzt wurden. Auch hier wurde die Emotion von dem Service interpretiert und prozentual ausgegeben.

Kurz stellte Laurent auch noch die Text-To-Speech API vor, welcher er in einem persönlichen Gespräch danach auch durchaus eine Creepiness zusagte.

![](IMG_0631.jpg)

AutoML kam zur Sprache. Damit kann man seine eigenen Daten trainieren und eine eigene API in der Cloud haben. Als Beispiel stellter vor, wie man damit der Visions API beibringen kann, nicht nur Wolken als solche zu erkennen, sondern auch deren Typ. Hierzu trainiert man AutoML mit eigenen Bilddaten. 

![](IMG_0636.jpg)

Ich persönlich finde diese Beispiele immer etwas schwierig, da sie Einfachheit vorspielen. Klar, auf einem technischen Level ist das alles viel simpler, als auf einer grünen Wiese damit zu beginnen. Aber so eine Wolkenerkennung trainiert sich auch nicht mit 3 getagten Bildern. Im Beipspiel trainierte er den Service mit hunderten getagter Bilder pro Wolkenart. DIese muss man eben auch erst mal produzieren. 

## Digitalpolitik 2018 - geht da noch was?

#### Nico Lumma - next media accelerator

Digitalpolitik in Deutschland ist für Nico Lumma "Fake it until you make it". Ja, wir machen einen Breitbandausbau. Irgendwann. Es wird geredet, aber nichts gemacht.

![](IMG_0639.jpg)

Für mich ist Nico Lummas Auftreten die wandelnde Bildkolumne. Mit dem Unterschied, dass er meistens recht hat mit dem, was er sagt. Er versteht es aber, es unterhaltsam und eindringlich vorzutragen.

Er beklagt in diesem Talk die Prioritäten, die in unserer Politik derzeit - und auch schon seit langer Zeit - gesetzt werden. Als einen Grund für den Mangel an Digitalthemen ist, dass man einen Mindestlohn einfach besser den Leuten erklären kann.

Und eigentlich sind die Vorraussetzungen für ein Vorankommen in der Digitalpolitik ganz gut. 90% aller Deutschen über 14 Jahre sind online. Es handelt sich durchaus um ein aktuelles Thema.

![](IMG_0642.jpg)

Doch das Dauerthema sind Flüchtlinge. Nico Lumma will der Wichtigkeit des Themas nichts absprechen, aber andere Themen werden überproportional davon verschluckt.

Das Bildungssystem wird nicht verändert, "das könnte ja Leute irritieren".

"Wir haben doch auch Wasser und Strom überall hinbekommen, warum dann nicht Breitband? Kostet 100 Milliarden. Ist machbar und finanzierbar." Dem ist wohl nicht viel hinzuzufügen, wobei man bei Nico besser noch mal die genannten Zahlen überprüfen sollte.

![](IMG_0641.jpg)

Wie kommen wir jetzt weiter?

Mit MdB reden und vom Leben erzählen. Die wissen das nicht und es interessiert sie. WIr haben nicht die Lobby, wie sie z.B. VW hat. Aber wir sind viele. Leider sind wir gleichzeitig sehr zersplittet, und werden deshalb nicht wahrgenommen.

China, USA und Europa fechten gerade die Digitale Zukunft aus. Wir sollten da mitmachen.

Ein spannender Talk, der in seiner Art etwas populistisch rüberkam, aber vielleicht ist es genau das, was es manchmal braucht.

## Creating High-Performance Web Apps with WebAssembly

#### Konstantin Möllers - Baqend

Der zweite Talk über WebAssembly, dieses mal mit etwas mehr Fokus auf WebAssembly und weniger auf go. Das könnte daran liegen, dass Konstantin mit Rust arbeitete, das ist aber nur eine Vermutung.

![](IMG_0646.jpg)

Der Talk ging etwas genauer auf die Eigenarten von WebAssembly (wasm) ein. Zum ersten mal hörte ich davon, dass es durchaus auch sinnvoll sein kann, wasm im Backend mit node.js zu verwenden, um dort Dinge zu beschleunigen.

Im Frontend unterstützt mittlerweile jeder aktuelle Browser die Ausführung von wasm.

Ein Nachteil ist aktuell noch, dass es schwer zu debuggen ist, man sieht nur den stack based code im Browser. Das ist nur wenig hilfreich.

![](IMG_0647.jpg)

Interessant fand ich die Tatsache, dass es in wasm kein string, boolean usw. gibt. Nur int32, int64... sind dort vorhanden. IN Rust und Go wird sich aber mit gluecode darum gekümmert, sodass man dort diese Typen verwenden kann. Alles andere wäre auch absurd.

![](IMG_0652.jpg)

Schön waren die Benchmarks, die Konstantin präsentierte.

## Nicht du bist das Problem, sondern die Kompexität

#### Alexander Jäger - Trustedshops

Ein sehr eindrücklicher Talk von Alexander. Was ist uns unsere begrenzte Lebenszeit wert? Was wollen wir? Was macht uns zufrieden?

![](IMG_0659.jpg)

Alexander präsentier ein Manifest für ein besseres Leben. Er will Entwicklern bewusst machen, dass sie schlechte Arbeitsbedingungen, schlechten Code und schlechtes Management nicht tollerieren sollen und müssen.

![](IMG_0660.jpg)

In vielen Betrieben werden die Entwickler verheizt. "Was, der hat Kopfschmerzen? Mach mal weniger Licht."

Wir sind keine Resource. Wir sollten uns nicht als solche behandeln lassen.

## Fazit

Eine sehr unterhaltsame und gut organisierte Veranstaltung. Über die Umstände kann man nur eine typische Postkarte schreiben: Essen lecker, Party gut, Leute nett. Gerne wieder.

Gespräche kamen einige sehr interessante zu Stande - der eigentliche Grund, warum man zu solchen Konferenzen geht, meiner Meinung nach. Diese Gespräche werde ich hier aus persönlichkeitsrechtlichen Gründen nicht rezitieren, da sie - auch wenn auf einer großen Konferenz gehalten - im Privaten stattfanden.

![](IMG_0675.jpg)







