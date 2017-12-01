# Artificial Intelligence 

### Definitionen

[Oxford Dictionaries](https://en.oxforddictionaries.com/definition/artificial_intelligence): The theory and development of computer systems able to perform tasks normally requiring human intelligence, such as visual perception, speech recognition, decision-making, and translation between languages.

[Techopedia](https://www.techopedia.com/definition/190/artificial-intelligence-ai): Artificial intelligence (AI) is an area of computer science that emphasizes the creation of intelligent machines that work and react like humans. Some of the activities computers with artificial intelligence are designed for include: Speech recognition, Learning, Planning, Problem solving

Eine weitere Buchquelle?

Artificial Intelligence, im folgenden AI, ist ein Bereich der Informatik, in dem an künstlichen Intelligenzen geforscht wird. Allerdings ist das Forschungsgebiet keinesfalls geschlossen. Viele andere Wissenschaften wirken bei der Entwicklung mit.  Es geht darum, Systeme zu entwickeln, die Aufgaben erledigen können, bei denen normalerweise menschliches Denken benötigt wird. Dazu gehören zum Beispiel Spracherkennung, Bilderkennung, Übersetzungen, Entscheidungen anhand mehrerer Faktoren richtig treffen und neue Dinge zu lernen. Entgegen der weit verbreiteten Vorstellungen muss eine AI nicht unbedingt die Fähigkeit haben, dazu zu lernen. Viele Systeme Klassifizieren "nur" die vorliegenden Daten, oder extrahieren wissen daraus. Ein ebenfalls weit verbreiteter Irtum ist, dass eine AI Intelligent ist, jedoch wird mittels Mathematik und Informatik lediglich intelligentes Verhalten simuliert. Von der Schaffung eines Bewusstseins ist die Forschung noch unabsehbar weit entfernt. 

### starke künstliche Intelligenz
Die Schaffung eines Bewusstseins wird durch den Begriff starke künstliche Intelligenz beschrieben. Sie beschäftigt sich damit, menschliches Denken zu mechanisieren, damit eine Maschine wie ein Mensch reagieren kann. Wie oben schon beschrieben, ist dieser Bereich von AI eher eine Vision. Es ist unklar, ob es realistisch ist, die Ziele in naher Zukunft zu erreichen.

### schwache künstliche Intelligenz
Die künstliche Intelligenz hingegen hat es sich zum Ziel gemacht, konkrete Anwendungsprobleme des menschlichen Denkens zu meistern und den Menschen "beim Denken" zu unterstützen. Da kaum Begrenzungen an Einsatzgebieten vorhanden sind, wurden schon viele kleine und große Erfolge in verschiedenen Bereichen gefeiert.

### DataSets
Damit die Algorthmen ordentlich arbeiten können ist es von enormer Wichtigkeit, die richtigen Daten im richtigen Format vorliegen zu haben. Diese Beziehung gilt natürlich auch umgekehrt. Der Algortimus muss umso besser werden, je größer die Unsicherheiten bzw. problematischen Informationen in den Daten sind. (zu ergänzen)

### Der Turing-Test
Der Turin-Test ist ein von Alan Turing entwickelter Test, welcher ein Maß dafür gibt, wie gut bzw. ob eine Maschine die Intelligenz eines Menschen gleichwertig simuliert. Seit 1991 existiert ein Preis für denjenigen, dessen Maschine den Test besteht. Bisher hat das aber noch niemand geschafft. Um den Test zu bestehen, darf die Testperson nicht unterscheiden können, ob es sich bei seinem Gesprächspartner an einem Terminal um einen echten Menschen oder eine Maschine handelt. Die Person stelllt dabei beliebige Fragen, ohne zu wissen, wer ihm antwortet. Kann die Person am Ende Mensch und Maschine nicht unterscheiden, hat die Maschine den Test bestanden.
  
# Machine Learning
### Supervised Learning
* *dt: überwachtes Lernen*
* *Lernen mithilfe eines bekannten Soll-Ergebnisses*

Der Begriff "Supervised Learning", zu deutsch überwachtes Lernen, beschreibt ein Ansatz beim Lösen von Lern-Problemen. Die Idee von Supervised Learning ist, einen AI-Algorithmus mithilfe eines bekannten Ergebnisses lernen zu lassen. Genauer gesagt ist dem Algorithmus bereits zu Beginn bekannt, welche Ergebnisse oder Klassen für den Anwendungsfall zu erwarten sind. Realisiert wird dies indem der Algorithmus zu Beginn mit einer Datengrundlage ausgestattet wird anhand derer er lernen kann. Diese zeigt dem Algorithmus zu welchem Ergebnis er kommen hätte müssen hätte er mit den Daten gearbeitet und kann dieses Wissen bei neuen Situationen anwenden. Am Beispiel der Bilderkennung ausgedrückt hat ein Algorithmus die Vorgabe, das ein Bild entweder einen Hund oder eine Katze zeigt. Neue einzuordnende Bilder werden jetzt den bekannten Klassen zugeordnet. 

### Unsupervised Learning
* *dt: unüberwachtes Lernen*
* *eigenständige Erarbeitung von möglichen Ergebnissen*

Ganz im Gegensatz zu Supervised Learning steht Unsupervised Learning, zu deutsch unüberwachtes Lernen. In diesem Konzept hat ein AI-Algorithmus keine Ergebnisse oder Ziele an denen er erkennen kann wie mit neuen Daten umgegangen werden soll. Jedes Ergebnis muss selbst vom Algorithmus herauskristallisiert werden. Häufig wird dabei Clustering verwendet, näheres dazu siehe unter CLustering. Dabei werden Lösungsgruppen gefunden. Im Fall der Bilderkennung kann ein Algorithmus somit nicht sagen das er Bilder mit Hunden und Katzen vor sich hat, er ist aber in der Lage eine klare Grenze zwischen verschiedenen Bilder zu ziehen und sie in unterschiedliche Merkmalsgruppen einzuteilen, da ein Hund nicht wie eine Katze aussieht. 

### Reinforcement Learning
* *dt: bestärkendes Lernen*
* *"Reward" soll maximiert werden*

Reinforcement Learning wählt einen Ansatz, bei dem ein Wert errechnet wird, der verbessert werden soll. Diesen Wert nennt man auch Fitness. Bei jedem Durchlauf wird als Ergebnis eine Zahl gegeben, die dem Algorithmus zeigen kann wie gut er war. Was dabei als gut zu bezeichnen ist, ist eine Frage der Kalibrierung. Ziel des Algorithmuses ist es die Fitness zu verbessern.

### Neural Network
Die Idee zu [neuronalen Netzen](https://www.computerwoche.de/a/eine-kleine-geschichte-der-kuenstlichen-intelligenz,3330537,5) kam das erste Mal in den 1940er Jahren auf. Der Neuropsychologe und Kypernetiker Warren McCulloch entwickelte zusammen mit Walter Pitts, ebenfalls Psychologie spezialisiert auf die Kognition, das Modell des McCulloch-Pitts-Neurons. Er forschte dabei über die Funktionsweise des menschlichen Gehirns und entwickelte dabei die uns heute bekannte Auffassung über neuronale Netze. Die beiden Wissenschaftler konnten beweisen, dass mit einem endlichen Netz solcher sogenannten Neuronen turing-berechenbare Probleme gelöst werden können. Allerdings fehlte damals ein leistungsfähiger Computer, weswegen die Idee der Neuronalen Netze bis in die Mitte der 80er in den Hintergrund geriet. 

Der aufkokmmende Konnektionismus orientierte sich wieder an dem menschlichen Gehirn als Vorbild. Die Grundidee bestand daraus, dass das Verarbeiten einer Information in vielen simplen einheitlichen Verarbeitungselementen paralell erfolgt. Die Forscher setzten also die bereits entwickelten Neuronen in einem Netz ein und brachten dem System anhand von Beispielsätzen das Sprechen bei. Das funktionierte bis zu einem gewissen Maß sehr gut, denn die Netze lernten gut und schnell. Allerdings waren die Cumputer zu der Zeit immer noch nicht leistungsfähig genug. Zudem fehlte es an genügend Trainingsdaten, sowie an Möglichkeiten diese zu strukturieren.

Seit 2010 kommen die Neuronalen Netze nun richtig zur geltung. Ursachen dafür sind die nun vorhandenen ausreichenden Rechenleistungen und die zunehmende Verfügbarkeit an strukturierten Daten, mit denen die Algorithmen trainiert werden können. Weitere Aspekte sind die Weiterentwicklung der Neuronalen Netze, verbesserte Algorithmen und vor allem eine Variante der neuronalen Netze: Deep Learning. In Abschnitt (DL) wird DeepLearning genauer betrachtet.

#### Elemente eines neuronalen Netzwerks
Jedes neuronale Netz besteht aus vielen Neuronen oder auch Knoten, welche untereinander auf eine bestimmte Art und Weise vernetzt sind. Die Art der Vernetzung, auch Topologie genannt ist abhängig von dem zu lösenden Problem und sollte gut durchdacht sein. Das Netz kann in verschiedene Layer aufgeteilt werden: Input, Hidden und Output Layer. Dabei besteht jedes Layer aus einer beliebigen Anzahl von Knoten. 
Jeder Input kann geweichtet werden und jeder Output kann durch einen Optimierungsalgorithmus optimiert werden. 

#### Convolutional NN
* *Faltung*
* *werden für Bilderkennung verwendet*
* *komplexer Algorithmus der Teilbereiche größerer Bereiche herunterdrosselt und vereinfacht*

#### Deep NN
Deep Neuronal Networks werden beim oben genannten Deep Learning verwendet. Der Unterschied zu einem gewöhnlichen neuronalen Netzes besteht darin, dass es über mehrere Hidden Layer verfügt. Das Ziel des Trainings ist es, einen möglichst geringen Fehler im Output zu erreichen.  Ein Training durchläuft normalerweise folgende Phasen:
* Netz durchlaufen
* Vermutung aussprechen
* Fehlermessung
* Aktualisierung der Gewichte
* Weiter bei Punkt 1
[Deep Learning](http://www.spektrum.de/news/maschinenlernen-deep-learning-macht-kuenstliche-intelligenz-praxistauglich/1220451) wird häufig zur statistischen Datenerkennung verwendet und eignet sich aufgrund der großen Lernfähigkeit sehr gut für eine große Menge an "unlabeld Data". Das ist auch der Grund, warum Deep Learning in letzter Zeit einen so großen Aufschwung erlebt. Denn der größte Teil an Daten liegt unkategorisiert vor. Unteranderem mit Hilfe von Deep Learning konnte im Januar 2016 der Weltmeister im Spiel Go durch eine Maschine besiegt werden. Doch  nicht nur beim Go spielen dominiert Deep Learning, das Spracherkennungsmodul von Appels Siri basiert ebenfalls auf diesem Verfahren.


### Classification
* *Klassifizierung von Dingen*
* *Technik im Bereich supervised*
* *Zuordnung in eine vorgegebene Menge an Klassen anhand Eigenschaften*
* *Bsp: Ist dieses Auto ein Mercedes oder ein Opel?*

Die Klassifizierung beschreibt eine eindeutige Zuordnung eines Objektes zu einer Klasse. Diese Technik wird häufig im Zusammenhang mit supervised learning verwendet. So ist es ein übliches Klassifizierungsbeispiel, festzustellen, was auf einem Bild angezeigt wird. Als Lerngrundlage wird einem AI-Algorithmus eine möglichst große, aussagekräftige Datengrundlage gegeben, die bereits die Aufgabe erfüllt. In diesem Beispiel können das 1000 Bilder sein, die unter dem Aspekt eingeteilt wurden, was auf Ihnen zu sehen ist (Hund, Katze, Apfel). Der Algorithmus kann anhand dieser Grundlage lernen und verstehen, wieso die Klassifizierung so vorgenommen wurde. Dabei achtet er auf Gemeinsamkeiten zweier gleicheingeordneter Bilder und auf Unterschiede der Bilder in unterschiedlichen Klassen. Anschließend sollte er in der Lage sein, eine eigene, möglichst genaue Einteilung bei neuen Bilder vorzunehmen. 

### Clustering
* *Objekte anhand ähnlicher Eigenschaften gruppieren
* *Technik im Bereich unsupervised*
* *Bsp: Algorithmus gruppiert Autos anhand Eigenschaften in Bereiche wie Kombi, Sport...*

Clustering ist im Gegensatz zu Classification eine Technik im Bereich unsupervised learning. Im Rahmen des Beispiels wird ein Algorithmus zu Beginn nicht mit einer Datengrundlage ausgestattet, sondern wird sozusagen blind Bilder einteilen. Dabei wird er die Unterschiede zwischen Bildern erkennen und Ähnlichkeiten feststellen. So werden auch bei dieser Methode als Ergebnis mehrere Klassen, hier besser Gruppen genannt, gefunden. Diese werden je nach Granularität und Einstellung ebenfalls auf Hunde, Katzen und Äpfel getrennt sein, auch wenn der Algorithmus nicht weiß das sie als solche bezeichnet werden. Im Grunde genommen bedeutet Clustering also nichts anderes als die Einteilung von Dingen nach Merkmalen, ohne das vorher eine Datengrundlage gegeben ist.

### Regression
* *Technik im Bereich supervised*
* *Zahlen als Eingabe, Zahl als Ausgabe*
* *Bsp: Wert eines Autos anhand bestimmter Parameter bestimmen*

Die Regression, welche auch schon in der Mathematik Anwendung findet, spielt im Bereich des supervised Learning eine Rolle. Im Normalfall wird dabei nur mit Zahlen gearbeitet, welche bestimmte Parameter darstellen. Diese Parameter lassen sich dazu verwenden, das Objekt an bekannte Werte anzunähern und einen Ergebniswert zu bestimmen. Ein konkreter Anwendungsfall für Regression ist die Wertbestimmung eines Autos anhand von Faktoren wie Alter und Kilometerstand des Wagens.

### Evolutionary Algorithms
* *Das Prinzip der Evolution in der Natur in Form von Algorithmen*
* *bestimmtes Vorgehen um bestmögliches Ergebnis zufinden*
* *nicht perfekt, meist findet sich nur lokales Optimum*

Evolutionäre Algorithmen finden ihren Ursprung in der Natur. Die Evolution hat zum Ziel, jedes Lebewesen so anzupassen das es in seiner Umgebung am besten zurecht kommt. Die Optimierung funktioniert dabei über die Fortpflanzung, da meist die Lebewesen am längesten überleben, die die besten Eigenschaften für die aktuelle Situation besitzen. Durch das Mischen und Vererben dieser Eigenschaften kann die Evolution ein Lebewesen in wenigen Generationen auf den Durschnitt gesehen länger und besser überleben lassen. Dieses Vorgehen wird durch evolutionäre Algorithmen in die Technik übernommen. Dort gilt es ebenfalls oft, eine optimale Lösung zu finden. Verwendet werden dafür die selben Ideen, die sich bereits in der Natur wiederfinden lassen. Zu Beginn werden die Lösungen selektiert, bevor diese ausgewählten Lösungen untereinander neu kombiniert werden. Ohne einen gewissen Einfluss an kontrolliertem Zufall wird es jedoch, wie in der Natur auch, weniger gut funktioneren einfach erneut zu selektieren. Deshalb muss zuerst eine Mutation einiger Lösungen durchgeführt werden. Die selektierten, neu aufgestellten Lösungen werden nun mit einem Fitness-Wert versehen, bevor mithilfe von dieser der Prozess von vorne beginnt und eine erneute Selektion druchgeführt wird.  

### Natural Language Processing
* *großer Teilbereich, Spracherkennung*

NLP beschreibt ein großes Teilgebiet des Machine Learnings, die Sprachverarbeitung. Das Ziel ist eine gleichwertige Kommunikation zwischen Mensch und Maschine. Durch Text- und Stimmerkennung wurden bereits große Meilensteine im Bereich NLP erreicht, es gibt bereits Algorithmen die den höheren Sinn aneinander gehängter Worte erkennen können, selbst wenn dieser Sinn unterschiedlich ausgedrückt wird. Trotzdem gibt es noch viele Forschungsmöglichkeiten, da eine perfekte Kommunikation aktuell noch nicht gewährleistet werden kann.

# Einsatzgebiete: 
### BigData

#### Definition
Big Data stellt keine neue Art von Daten dar, sondern vielmehr charakterisiert es, wie Daten heute immer häufiger auftreten. Um die Daten zu Charakterisieren wird oftmals das 4 V Modell von IBM verwendet. Folgende Tabelle zeigt die 4 Vs und ihre Bedeutung.

| V | Bedeutung | Beschreibung |
| ----- | ----- | ------- |
| Volume | Menge der Daten | Im Jahr 2016 umfasste das Weltweite Datenvolumen 16,1 Zettabyte (1 Zettabyte = 1 Mrd. TB). Für 2025 wird eine verzehnfachung erwartet |
| Variety | Datenvielfalt | Die Daten liegen in vielen verschiedenen Formaten wie zum Beispiel Mediendateien, Textdatein, etc. vor. Dabei ist der große Anteil der Daten unstrukturiert. |
| Velocity | Geschwindigkeit | Der Zugriff auf die Daten muss größtenteils in Echtzeit erfolgen, damit eine Auswertung sinnvoll ist. Hierfür braucht es gute Algorithmen sowie die entschprechende Rechenpower. |
| Veracity | Aussagekraft | Das letzte der vier V steht für die Vertrauenswürdigkeit der Daten. Das Prinzip "Garbage In- Garbage Out", welches in dem Zusammenhang oftmals erwähnt wird besagt, dass nur wenn gute Daten durch einen guten Algorithmus analysiert werden, auch gute Ergebnisse erwartet werden können. Sobald der Algorithmus schlecht ist, ist der Output so gut wie unbrauchbar.|

#### Zusammenhang mit AI
Um die große Menge an Daten Effizient auswerten zu können, werden oftmals künstliche Intelligenzen eingesetzt. Die verschiedenen Modelle können die große Datenflut in der gegebenen Zeit besser bewältigen als der Mensch. Allerdings ist es unverzichtbar, wie das vierte V zeigt, auf ein gutes Model zu bauen. Big Data stellt also ein großes Einsatzgebiet für Artificial Intelligence dar.

### Data-Mining
* systematische Anwendung statistischer Methoden auf große Datenbestänge 
* Ziel: neue Querverbindungen und Trends erkennen

Unter [Data Mining](https://www.bigdata-insider.de/was-ist-data-mining-a-593421/ "Data Mining") versteht man die systematische Anwendung statistischer Methoden und Verfahren aus dem Bereich Artificial Intelligence auf einen vorliegenden Datenbestand. Das Ziel von Data Mining ist es, neue Querverbindungen, Trends und relevante Zusammenhänge in den Daten zu erkennen und diese zu exrahieren. Data Mining und Big Data werden oft im selben Kontext benutzt. Allerdings bedeuten sie nicht das gleiche, wie fälschlicherweise oft angenommen. Big Data bezeichnet die Analyse großer Datenmengen aus vielfältigen Quellen in hoher Geschwindigkeit. Wie in Kapitel (Big Data) beschrieben ist eine Analyse der Daten mit herkömmlichen Toolsund Methoden in realistischer Zeit kaum mehr möglich. Big Data bietet hierfür die technische Plattform. Data Mining ist hingegen nicht auf große Datenmengen begrenzt, auch wenn es dort oft eingesetzt wird, und beschreibt den eigentlichen Vorgang der Analyse der Daten. 

Für Data Mining gibt es verschiedene Aufgabenbereiche mit einem jeweiligen Ziel.
* Klassifikation: Zuordnung von Datenobjekten auf Klassen.
* Segmentierung: Zuammenfassung von Objekte mit gemeinsamen Merkmalen zu einer Gruppe.
* Prognose: Vorhersage von unbekannten Merkmalen auf Basis von bereitz bekannten Merkmalen und zuvor gewonnenen Erkenntnissen.
* Abhängigkeitsanalyse: Beziehungen zwischen Objekten bzw. den Merkmalen der Objekte finden.
* Abweichungsanalyse: Erkennen von Objekten, die nicht den Regeln der anderen Objekte entsprechen.

Angewandt werden kann Data Mining sehr vielfältig. Eine Möglichkeit ist der Einsatz bei der Entscheidungsfindung bei bestimmten Problemen. Zum Beispiel kann im Handel das Kaufverhalten von Kunden analysieren und Ihnen daraufhin passende Angebote machen bzw. entscheiden, ob der Kunde zahlungsfähig oder zahlungsunfähig ist. Banken und Versicherungen können Data Mining nutzen um Risikoanalysen durchzuführen.

### Robotik
* Interaktion mit der physischen Welt auf Prinzipien der IT/technisch machbare Kinetik übertragen
* Nachvollziehen von Verhaltensweisen
* z.B. Autos lackieren, Mienensuche

In der Robotik geht es vorrangig darum die Interaktion mit der physischen Welt auf Prinzipien der IT und technisch machbare Kinetik zu übertragen. Beliebte Einsatzgebiete sind solche, die für den Menschen gefährlich sein können, wie zum Beispiel das Suchen nach Mienen oder das Lackieren von Autos. Das hat ersteinmal nichts mit Artificial Intelligence zu tun. Allerdings liegt es durchaus im Bereich des Möglichen die beiden Themenbereiche zu kombinieren. 

Doch dabei werden viele Ethische Fragen aufgeworfen, wie zum Beispiel "Ist ein Roboter mit einer KI ein lebendiges Wesen, welches das Recht auf leben besitzt?". Die größte und momenta aktuelle Diskussion ist wohl die zwischen Tesla Gründer Elon Musk und Facebook Gründer Mark Zuckerberg. Letzterer sieht in AI viele Vorteile für die Zukunft. Elon Musk hingegen befürchtet dass die Kombination aus AI und Roboter zu einer tödlichen Waffe nicht nur gegen einzelne Menschen werden kann, sondern für die gesammte Menschheit. Einige Experten haben einen Brief an die Vereinten Nationen geschrieben und gebeten, die Entwicklung und Nutzung von autonomen Waffensystemen zu verbieten. Dies zeigt, dass es in Zukunft wichtig sein könnte, bestimmte Regularien im Bezug auf AI aufzustellen, damit diese großartige Technologie nur im positiven Sinn eingesetzt wird.

