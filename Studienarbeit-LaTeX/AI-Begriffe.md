# Artificial Intelligence 
* KI-Systeme haben die Fähigkeit zu lernen *(können die Fähigkeit haben)*
* Müssen mit Unsicherheiten und problematischen Informationen umgehen können
* Keine Schaffung von Bewusstsein, sondern Simulation intelligenten Verhaltens mittels Mathe und Informatik
* Kein geschlossenes Forschungsgebiet (Techniken verschiedener Disziplinen)
* 

### starke KI
* Menschliches Denken mechanisieren
* Maschine, die wir Mensch reagiert
* Eine Vision *(unklar ob in naher Zukunft realistisch)*

### schwache KI
* Konkrete Anwendungsprobleme des menschlichen Denkens meistern
* *kaum vorhandene Begrenzungen an Einsatzgebieten*
* Das Denken unterstützen
* Viele kleine und große Erfolge wurden schon gefeiert

  
# Machine Learning
### Supervised Learning
* *dt: überwachtes Lernen*
* *Lernen mithilfe eines bekannten Soll-Ergebnisses*

Der Begriff "Supervised Learning", zu deutsch überwachtes Lernen, beschreibt ein Ansatz beim Lösen von Lern-Problemen. Die Idee von Supervised Learning ist, einen AI_Algorithmus mithilfe eines bekannten Ergebnisses lernen zu lassen. Genauer gesagt ist dem Algorithmus bereits zu Beginn bekannt, welche Ergebnisse oder Klassen für den Anwendungsfall zu erwarten sind. Am Beispiel der Bilderkennung ausgedrückt hat ein Algorithmus die Vorgabe, das ein Bild entweder einen Hund oder eine Katze zeigt. Neue einzuordnende Bilder werden jetzt den bekannten Klassen zugeordnet. Der Algorithmus wird zu Beginn mit einer Datengrundlage anhand derer er lernen kann gefüttert.

### Unsupervised Learning
* *dt: unüberwachtes Lernen*
* *eigenständige Erarbeitung von möglichen Ergebnissen*

Ganz im Gegensatz zu Supervised Learning steht Unsupervised Learning, zu deutsch unüberwachtes Lernen. In diesem Konzept hat ein AI-Algorithmus keine Ergebnisse oder Ziele an denen er sich vorarbeiten kann. Jedes Ergebnis muss selbst vom Algorithmus herauskristallisiert werden. Häufig wird dabei CLustering verwendet, näheres dazu siehe unter CLustering. Dabei werden Lösungsgruppen gefunden. Im Fall der Bilderkennung kann ein Algorithmus somit nicht sagen das er Bilder mit Hunden und Katzen vor sich hat, er ist aber in der Lage eine klare Grenze zwischen beiden Bilder zu ziehen und sie in unterschiedliche Merkmalsgruppen einzuteilen, da ein Hund nicht wie eine Katze aussieht.

### Reinforcement Learning
* *dt: bestärkendes Lernen*
* *"Reward" soll maximiert werden*

Reinforcement Learning wählt einen Ansatz, bei dem ein Wert errechnet wird, der verbessert werden soll. Diesen Wert nennt man auch Fitness. Bei jedem Durchlauf wird als Ergebnis eine Zahl gegeben, die dem Algorithmus zeigen kann wie gut er war. Was dabei als gut zu bezeichnen wird ist eine Frage der Kalibrierung. Ziel des Algorithmuses ist es die Fitness zu verbessern.

### Deep Learning
* Statische Datenerkennung
* Gut für große Menge an "unlabeld" Data

### Neural Network
* Elemente: Input, Hidden und Output Layer
* Layer bestehen aus mehreren Nodes (entspr. Neuronen)
* Nodes: Inputs, Weights (Gewichtung des Inputs), Net Input Function, Activation Function, Output

#### Convolutional NN
* *Faltung*
* *werden für Bilderkennung verwendet*
* *komplexer Algorithmus der Teilbereiche größerer Bereiche herunterdrosselt und vereinfacht*

#### Deep NN
* Mehrere Hidden Layer
* Ziel des Trainings: möglichst geringer Fehler des Outputs
* Training: 
  * Netz durchlaufen
  * Vermutung aussprechen
  * Fehlermessung
  * Aktualisierung der Gewichte
  * Weiter bei Punkt 1

### Classification
* *Klassifizierung von Dingen*
* *Technik im Bereich supervised*
* *Zuordnung in eine vorgegebene Menge an Klassen anhand Eigenschaften*
* *Bsp: Ist dieses Auto ein Mercedes oder ein Opel?*

Die Klassifizierung beschreibt eine eindeutige Zuordnung eines Objektes zu einer Klasse. Diese Technik wird häufig im Zusammenhang mit supervised learning verwendet. So ist ein klassiches Klassifizierungsbeispiel, festzustellen, was auf einem Bild angezeigt wird. Als Lerngrundlage wird einem AI-Algorithmus eine möglichst große, aussagekräftige Datengrundlage gegeben, die bereits die Aufgabe erfüllt. In diesem Beispiel können das 1000 Bilder sein, die unter dem Aspekt eingeteilt wurden, was auf Ihnen zu sehen ist (Hund Katze Apfel). Der Algorithmus kann anhand dieser Grundlage lernen und verstehen, wieso die Klassifizierung so vorgenommen wurde und ist anschließend in der Lage, eine eigene Einteilung bei neuen Bilder vorzunehmen.

### Clustering
* *Objekte anhand ähnlicher Eigenschaften gruppieren
* *Technik im Bereich unsupervised*
* *Bsp: Algorithmus gruppiert Autos anhand Eigenschaften in Bereiche wie Kombi, Sport...*

Clustering ist im Gegensatz zu Classification eine Technik im Bereich unsupervised learning. Im Rahmen des Beispiels wird ein Algorithmus zu Beginn nicht mit einer Datengrundlage ausgestattet, sondern wird sozusagen blind Bilder einteilen. Dabei wird er die Unterschiede zwischen Bildern erkennen und Ähnlichkeiten feststellen. So werden auch bei dieser Methode als Ergebnis mehrere Klassen, hier besser Gruppen genannt, gefunden. Diese werden je nach Granularität und Einstellung ebenfalls auf Hunde, Katzen und Äpfel getrennt sein, auch wenn der ALgorithmus nicht weiß das sie als solche bezeichnet werden. Im Grunde genommen bedeutet Clustering also nichts anderes als die Einteilung von Dingen nach Merkmalen.

### Regression
* *Technik im Bereich supervised*
* *Zahlen als Eingabe, Zahl als Ausgabe*
* *Bsp: Wert eines Autos anhand bestimmter Parameter bestimmen*
### Association

### Evolutionary Algorithms
* *Das Prinzip der Evolution in der Natur in Form von Algorithmen*
* *bestimmtes Vorgehen um bestmögliches Ergebnis zufinden*
* *nicht perfekt, meist findet sich nur lokales Optimum*
### Natural Language Processing
* *großer Teilbereich, Spracherkennung*

# Einsatzgebiete: 
### BigData
* Big Data bezeichnet die Analyse großer Datenmengen aus vielfältigen Quellen in hoher Geschwindigkeit.
* Die 4 V's
  * Volume: Menge der Daten
  * Veracity: Zusammenhänge der Daten
  * Velocity: Geschwindigkeit
  * Variety: DDatenvielfalt
### Data-Mining
* systematische Anwendung statistischer Methoden auf große Datenbestänge 
* Ziel: neue Querverbindungen und Trends erkennen
### Robotik
* Interaktion mit der physischen Welt auf Prinzipien der IT/technisch machbare Kinetik übertragen
* Nachvollziehen von Verhaltensweisen
* z.B. Autos lackieren, Mienensuche

