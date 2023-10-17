# partnerarbeit1

<h1>Beschreibung<h/1><br><br>
<p>Unter den folgenden Punkten sieht man, wie wir die oben genannte Punkte in unserem Code eingewandt haben.
1. Definition der Basisklasse: Wir haben mit der Basisklasse begonnen, die die gemeinsamen Eigenschaften und Methoden für alle abgeleiteten Klassen definiert. In diesem Fall ist es die Media-Klasse.

2. Ableitungen erstellen: Dann haben wir die Unterklassen Movie und eBook, die von der Basisklasse erben, erstellt. Diese Klassen erben automatisch die Eigenschaften und Methoden der Basisklasse.

3. Überschreiben von Methoden: Zum Beispiel die Klassen „Movie“ und „eBook“, welche über spezielle Daten verfügen, deswegen haben wir die toString-Methode abgändert. Dies stellt sicher, dass die spezialisierten Klassen ihr Verhalten anpassen können.

4. Polymorphie nutzen: Wir haben eine Liste von Medien in unserer Library-Klasse erstellt und wir haben Polymorphie, um verschiedene Medientypen in derselben Liste zu speichern, erstellt. Dies ermöglicht es, auf die abgeleiteten Klassen (z. B. Movie und eBook) zuzugreifen, als wären sie Instanzen der Basisklasse (Media).

5. Dynamische Bindung: Bei der Verwendung von Polymorphie wird die Methode zur Laufzeit dynamisch gebunden. Das bedeutet, dass zur Laufzeit die richtige Methode der abgeleiteten Klasse aufgerufen wird, basierend auf dem tatsächlichen Typ des Objekts.

In dieser Implementierung wurden die zentralen Konzepte der Vererbung, des Überschreibens, der Ersetzbarkeit und der dynamischen Bindung genutzt, um eine polymorphe Lösung für die Verwaltung verschiedener Medientypen in einer Medienbibliothek zu erstellen.
Jeder Medientyp (z. B. Movie und eBook) erbt von der gemeinsamen Basisklasse (Media) und überschreibt bei Bedarf Methoden, um spezifisches Verhalten zu implementieren. Die dynamische Bindung stellt sicher, dass die richtige Methode zur Laufzeit aufgerufen wird, wenn auf Medien in der Bibliothek zugegriffen wird. Außerdem wurden auch andere Klassen (z. B. Genre, Urheber, Kommandozeilenmenü) erstellt, womit man den Code leichter erweiterbar macht.
</p>
