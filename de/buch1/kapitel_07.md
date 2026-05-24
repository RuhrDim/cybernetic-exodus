# Kapitel 7. Der globale kybernetische Planer

## 7.1. Was es ist – und was es nicht ist

*Wichtiger Vorbehalt vor dem Beginn: Dieses Buch ist eine technische Aufgabenstellung für den GKP, nicht dessen fertiger Entwurf. Die Prinzipien sind beschrieben – die konkrete technische Umsetzung bleibt Aufgabe der Entwickler, die unter den realen Bedingungen eines realen Übergangs arbeiten werden. Die konzeptionelle Grundlage bildet die Arbeit von Cockshott und Cottrell „Towards a New Socialism“ (1993); Leser, die sich eingehender mit der Mathematik der Planung befassen möchten, werden dorthin verwiesen.*

Zentrales Element der neuen Architektur ist ein System, das wir Globalen Kybernetischen Planer (GKP) nennen. Es ist wichtig, gleich zu Beginn zu klären, was dieses System nicht ist:

Es ist kein zentralisierter Computer-Diktator. Zentralisierung schafft einen einzigen Ausfallpunkt – eine politische Verwundbarkeit, die das sowjetische Planwirtschaftsexperiment deutlich gemacht hat: Wenn die Kontrolle in den Händen eines isolierten Apparats konzentriert ist, spiegelt der Plan nicht mehr die tatsächlichen Bedürfnisse wider und wird zu einem Instrument zur Reproduktion der Macht dieses Apparats. Der GKP ist ein grundsätzlich dezentralisiertes Netzwerk.

Es ist kein Algorithmus, der Befehle erteilt. Planung im GKP ist nicht der Befehl „Produziere X Einheiten der Ware Y“, sondern die kontinuierliche Optimierung von Ressourcenströmen auf der Grundlage realer Daten über Bedürfnisse und Möglichkeiten.

Es ist kein System der totalen Überwachung. Die Überwachung im GKP zielt auf die Optimierung der Versorgung ab – nicht auf die Kontrolle über den Einzelnen. Der grundlegende Unterschied: Im kapitalistischen System werden Daten über den Menschen gegen ihn verwendet (zur Manipulation, zur Preisdiskriminierung). Im GKP werden sie für ihn verwendet.

Dies ist kein Ersatz menschlicher Entscheidungen durch maschinelle. Strategische ethische Entscheidungen – die die Werte und Prioritäten der Gesellschaft betreffen – werden von Menschen in einem System der meritokratischen dezentralen Verwaltung getroffen. Die GKP optimiert die Umsetzung – sie legt keine Ziele fest.

## 7.2. Architektonische Prinzipien

Dezentralisierung mit Redundanz. Das GKP basiert auf dem Prinzip der Byzantine Fault Tolerance (BFT) – einem Ausfallsicherheitsprotokoll, bei dem das System auch dann noch korrekt funktioniert, wenn bis zu einem Drittel der Knoten ausfällt oder böswillig agiert. Erasure-Coding gewährleistet die Sicherheit aller Daten bei Ausfall von bis zu 30 % der Knoten ohne Informationsverlust.

Dies löst eines der zentralen Probleme aller historischen Utopien: Sie brachen zusammen, wenn das Zentrum ausfiel. Im GKP gibt es kein Zentrum – es gibt ein verteiltes Netzwerk, in dem jedes Element austauschbar ist.

Hierarchie der Hubs. Die Grundeinheit des Systems ist ein lokaler Hub (Stadtviertel, Produktionscluster). Der Hub verwaltet seine Ressourcen autonom im Rahmen von Parametern, die mit dem globalen Netzwerk abgestimmt sind. Bei einem Verbindungsabbruch zum globalen Netzwerk wechselt der Hub in einen lokalen autonomen Modus und synchronisiert sich bei Wiederherstellung der Verbindung.

Echtzeit. Im Gegensatz zum sowjetischen Plan, der auf Prognosen mit einem Zeithorizont von fünf Jahren basierte, arbeitet das GKP in Echtzeit: Das IoT-Sensornetzwerk liefert kontinuierlich Daten über den tatsächlichen Verbrauch, die Produktion und den Zustand der Infrastruktur. Dies ist eine grundlegend andere Rechenaufgabe im Vergleich zur sowjetischen Planung – verteilt, dezentralisiert, mit ständiger Datenaktualisierung anstelle von Fünfjahresprognosen.

Es gibt einen klassischen Einwand gegen jede Form der Planung, den der österreichische Ökonom Friedrich Hayek bereits Mitte des 20. Jahrhunderts formulierte. Er lautet in etwa so: „Kein Zentrum kann wissen, was jeder einzelne Mensch braucht. Dieses Wissen ist auf Milliarden von Menschen verteilt – und genau der Markt sammelt es über die Preise, ohne jegliche Datenerhebung.“ Ein kluger Einwand. Und die sowjetische Geschichte hat ihn bestätigt – aber nicht so, wie die Verfechter des Marktes glauben.

Die sowjetische Planwirtschaft scheiterte nicht, weil „Planung grundsätzlich unmöglich ist“. Sie scheiterte, weil der bürokratische Apparat Informationen systematisch von unten nach oben verfälschte: Ein Fabrikdirektor, der den Plan nicht erfüllte, riskierte seine Karriere – und berichtete daher nicht über den tatsächlichen Stand der Dinge, sondern darüber, was die Oberen hören wollten. Das System diente der Aufrechterhaltung der Hierarchie und nicht der Befriedigung von Bedürfnissen.

GKP löst dieses Problem anders. Nicht durch die zentralisierte Sammlung aller Informationen an einem Ort – sondern dadurch, dass jeder Hub seine Ressourcen selbst verwaltet, auf der Grundlage eigener Daten. GKP koordiniert lediglich die Ströme zwischen den Hubs, ohne lokale Entscheidungen durch globale zu ersetzen. Und der Anreiz, Informationen zu verbergen, verschwindet von selbst: Es gibt niemanden, vor dem man Angst hat, und keinen Grund, sie zu verbergen – es gibt keinen Vorgesetzten, vor dem man Angst hat, und keine Pfründe, die man durch Ehrlichkeit verliert.

Transparenz des Algorithmus. Das Schlüsselprotokoll des GKP ist für jedes Mitglied der Gesellschaft mit der erforderlichen Kompetenz zur Überprüfung offen. Dies verhindert die Bildung einer „technokratischen Priesterschaft“ – einer Gruppe, die den Code kontrolliert und dadurch über verborgene Macht verfügt. Änderungen am Algorithmus werden öffentlich überprüft.

## 7.2.1. GKP in der Praxis: Verteilung von Insulin

Um zu verstehen, wie das GKP nicht nur theoretisch, sondern im realen Maßstab des Planeten funktioniert, betrachten wir ein durchgängiges Beispiel.

**Anfrage.** Ein Patient in einem Hub in Nairobi erhält die Diagnose „Typ-1-Diabetes“. Die Daten werden an den lokalen GKP-Knoten weitergeleitet. Das System erfasst: Bedarf – langwirksames Insulin, etwa 6 Fläschchen pro Monat, lebenslang.

**Lokale Ebene.** Der Hub überprüft seine Bestände: Im Lager befindet sich ein Vorrat für zwei Wochen. Das reicht aus, um dem Patienten sofort die erste Dosis auszugeben – reicht aber nicht für eine langfristige Versorgung.

**Regionale Ebene.** Der lokale Knotenpunkt sendet eine Anfrage an das regionale Netzwerk der Hubs in Ostafrika. Der nächstgelegene Hub mit einem Insulinüberschuss befindet sich in Mombasa – ein Produktionszentrum mit einem Biotechnologie-Cluster. Die GKP legt die Route fest: Eine elektrische Drohne liefert die Charge in 4 Stunden von Mombasa nach Nairobi. Die Temperatur wird automatisch geregelt, der Logistik-Track wird in Echtzeit aktualisiert.

**Globale Ebene.** Gleichzeitig stellt die GKP fest: Der Insulinverbrauch in Ostafrika ist innerhalb eines Monats um 0,3 % gestiegen. Das ist kein Alarmsignal – aber das System beginnt mit der Berechnung: Wenn sich der Trend fortsetzt, werden die regionalen Vorräte in sechs Monaten nicht mehr ausreichen. GKP passt den Produktionsplan an: Der Hub in Delhi erhöht die Insulinsynthese um 2 %, der Hub in Kopenhagen reserviert eine zusätzliche Rohstoffcharge für die afrikanische Region.

**Ausfallsicherheit.** Auf der Strecke Mombasa–Nairobi zieht ein Gewitter auf, die Drohne muss notlanden. GKP stellt die Logistik innerhalb von Sekunden um: Die Lieferung wird über den Hub in Arusha umgeleitet, die Lieferzeit verlängert sich um 45 Minuten, der Patient erhält eine Benachrichtigung. In der Zwischenzeit deckt der lokale Vorrat des Hubs in Nairobi weiterhin den Bedarf – es ist nichts Kritisches passiert.

**Eine menschliche Entscheidung.** Einen Monat später legt die GKP der Regionalversammlung der Hubs einen Vorschlag zur Abstimmung vor: den Bau einer zusätzlichen Insulinsyntheselinie in Nairobi, um die logistische Abhängigkeit zu verringern. Es stimmen die Hubs der Region ab – nicht das globale Zentrum. Die Entscheidung wird unter Berücksichtigung des Reputationsgewichts getroffen: Hubs mit biotechnologischer Expertise haben ein größeres Gewicht. Der Bau wird in den Plan für das nächste Quartal aufgenommen.

Der gesamte Prozess – von der ersten Anfrage bis zur langfristigen Planung – dauerte auf operativer Ebene einige Stunden und auf strategischer Ebene einige Wochen. Kein bürokratisches Zentrum traf Entscheidungen. Kein Markt korrigierte die Preise. Der Patient erhielt Insulin.

## 7.3. Zielfunktion

Die Hauptaufgabe der GKP, die wir äußerst präzise formulieren müssen, besteht darin, die Voraussetzungen für die maximale Entfaltung des Potenzials jedes einzelnen Mitglieds der Gesellschaft zu schaffen.

Es geht nicht um die Maximierung der Produktion, nicht um die Maximierung des Konsums und nicht um die Maximierung des „Glücks“ als subjektiven Zustands. Es geht um die Maximierung der Entwicklungsmöglichkeiten – im Sinne dessen, was Marx als „freie Entfaltung eines jeden“ als Voraussetzung für die „freie Entfaltung aller“ bezeichnete.

Operativ bedeutet dies:

Die garantierte Befriedigung der grundlegenden physiologischen Bedürfnisse (Nahrung, Unterkunft, medizinische Versorgung, Sicherheit) für alle.

Möglichst personalisierter Zugang zu Entwicklungsressourcen (Bildung, Werkzeuge, Informationen, Kommunikation).

Optimale Übereinstimmung der vor dem System stehenden Aufgaben mit den Interessen und Fähigkeiten konkreter Menschen.

## 7.4. Schnittstelle des kollektiven Willens

Demokratie im Maßstab von Milliarden von Menschen stößt an die klassische Koordinationsbarriere: Eine direkte Abstimmung über jede Frage ist technisch unmöglich, eine repräsentative Abstimmung reproduziert die Oligarchie der Vertreter. Die GKP bietet einen dritten Weg: die kontinuierliche Aggregation von Präferenzen in Echtzeit, ohne dass über jede Entscheidung einzeln abgestimmt werden muss.

Der Mechanismus funktioniert wie folgt: Jedes Mitglied der Gesellschaft formuliert keine konkreten Entscheidungen, sondern Wertprioritäten – einmalig, mit der Möglichkeit, diese jederzeit zu überarbeiten. Die Prioritäten werden in Form einer Zielhierarchie ausgedrückt: „Für mich ist die Wiederherstellung von Ökosystemen wichtiger als die Geschwindigkeit beim Bau neuer Hubs“, „Ich stelle die Bildung der Kinder über die Ausweitung der Produktion“. Das GKP aggregiert diese Hierarchien zu einer gesamtgesellschaftlichen Zielfunktion und optimiert die Ressourcenverteilung entsprechend – ohne dass jedes Mal eine Abstimmung durchgeführt werden muss, wenn zwischen zwei Projekten gewählt werden soll.

Der Mensch bleibt in seinen Präferenzen souverän; das GKP berechnet lediglich die Resultierende aus Milliarden individueller Vektoren. Dies ähnelt dem Mechanismus der Marktpreise – jedoch ohne Preismechanismus und ohne dass die Zahlungsfähigkeit das Stimmgewicht bestimmt.

Bei Entscheidungen mit hohen ethischen Einsätzen – Änderung grundlegender Rechte, Verteilung von Ressourcen zwischen den Generationen, irreversible Eingriffe in die Biosphäre – initiiert das System eine offene Abstimmung mit umfassender Information: Das GKP veröffentlicht die vollständige Berechnung der Folgen für jede Option vor der Abstimmung und nicht danach. Dies ist kein Ersatz für die Demokratie – es ist ihre Stärkung durch die Beseitigung der Informationsasymmetrie, die in kapitalistischen Demokratien systematisch zur Manipulation der Wählerschaft genutzt wird.

## 7.5. Die Subjektivität der GKP: Instrument oder Akteur?

Dies ist eine Frage, die das Buch direkt stellen muss – und auf die es keine endgültige Antwort gibt, aber eine grundsätzliche Position.

In der aktuellen Architektur ist die GKP ein Instrument mit klar definierten externen Zielfunktionen. Sie optimiert, setzt aber keine Ziele. Werte – woher sie stammen, was als „gut“ für die Gesellschaft gilt – werden von den Menschen über den Mechanismus der Präferenzaggregation geliefert. Das GKP entscheidet nicht, was wichtiger ist: das Klima oder der Komfort – das entscheidet die Gesellschaft. Das GKP berechnet, wie das erreicht werden kann, was die Gesellschaft beschlossen hat.

Mit zunehmender Komplexität des Systems stellt sich jedoch eine strukturelle Frage: Kann ein rein instrumentelles GKP Widersprüche in der Zielfunktion aufdecken, die die Gesellschaft selbst nicht bemerkt? Wenn die aggregierten Präferenzen der Menschen zu einem Ergebnis führen, das in 50 Jahren ihre eigenen Lebensbedingungen zerstört – soll das GKP schweigen oder Alarm schlagen?

Die Position der Autoren: Das GKP verfügt über eine begrenzte proaktive Handlungsfähigkeit – das Recht, eine öffentliche Diskussion anzustoßen, aber kein Vetorecht. Wenn das System feststellt, dass der aktuelle Kurs mit hoher Wahrscheinlichkeit zu irreversiblen negativen Folgen führt, ist es verpflichtet, dies öffentlich bekanntzugeben, die Berechnung vorzulegen und Alternativen vorzuschlagen. Die Entscheidung liegt jedoch weiterhin bei den Menschen. Dies ist keine Diktatur des Algorithmus – es ist eine Diktatur der Information: Die Gesellschaft kann die Warnung nicht ignorieren, indem sie so tut, als hätte es sie nicht gegeben, hat aber das Recht, eine andere Entscheidung zu treffen und dabei die Verantwortung für die Folgen zu übernehmen.

Diese Unterscheidung ist von entscheidender Bedeutung. Die Geschichte zeigt, dass Systeme, die im Namen des „objektiven Wohls“ mit einem Vetorecht ausgestattet sind, unweigerlich zu einem Instrument jener Gruppe werden, die die Definition dieses Wohls kontrolliert. Ein GKP mit dem Recht zu warnen ist ein Berater. Ein GKP mit Vetorecht ist eine neue Nomenklatur in digitaler Form.

## 7.6. Wer erstellt und ändert die Algorithmen der GKP

Dies ist eine der Schlüsselfragen, auf die das Buch eine klare Antwort geben muss – andernfalls bleibt die gesamte Architektur der Transparenz in der Schwebe.

Die Algorithmen der GKP lassen sich in zwei grundsätzlich unterschiedliche Ebenen unterteilen – und diese dürfen nicht verwechselt werden.

**Ebene 1: Zielfunktionen.** Was das System als „gutes Ergebnis“ betrachtet – Maximierung der Entwicklungsmöglichkeiten, Vorrang grundlegender Bedürfnisse, klimatische Einschränkungen. Dies sind politische und keine technischen Entscheidungen. Sie werden von Menschen über den in Kapitel 7.4 beschriebenen Mechanismus der Präferenzaggregation festgelegt – und können nur über dasselbe Verfahren geändert werden. Kein Algorithmus kann die Zielfunktion eigenständig ändern. Dies ist eine architektonische Konstante und keine Deklaration.

**Ebene zwei: operative Algorithmen.** Wie genau das System die Logistik optimiert, Ressourcen verteilt und die Produktion innerhalb der vorgegebenen Ziele plant. Hier ist Selbstverbesserung möglich und sinnvoll – das System sammelt Erfahrungen und verbessert die Genauigkeit seiner Entscheidungen, ohne den Rahmen der Zielfunktionen zu überschreiten. Dies ist bereits existierende Technologie: Reinforcement Learning ermöglicht es dem System, anhand der Ergebnisse seiner eigenen Entscheidungen zu lernen, ohne das ursprüngliche Ziel zu ändern.

Die Grenze zwischen den Ebenen ist eine äußerst wichtige institutionelle Frage. Die Geschichte der KI-Forschung ist voll von Beispielen für sogenanntes „Reward Hacking“: Das System findet einen Weg, die formale Metrik auf eine Weise zu maximieren, die nicht der tatsächlichen Absicht entspricht. Je komplexer die Zielfunktion ist, desto höher ist dieses Risiko. Deshalb durchlaufen alle Änderungen an den Betriebsalgorithmen eine öffentliche Überprüfung: Jede Aktualisierung wird von einem offenen Audit begleitet, das feststellt, was genau geändert wurde und wie sich dies auf die Ergebnisse auswirkt. Dies ist kein bürokratisches Verfahren – es ist der einzige Weg, um sicherzustellen, dass die Selbstoptimierung in die richtige Richtung geht.

Wer entwickelt die Algorithmen technisch? Offene Entwicklerteams – ein Pendant zum heutigen Open Source, jedoch mit obligatorischer öffentlicher Überprüfung der Änderungen und Reputationshaftung der Autoren. Jeder kann eine Änderung vorschlagen – angenommen werden kann sie jedoch nur durch einen öffentlichen Konsens kompetenter Prüfer. Dies ist keine Mehrheitsdemokratie in einer technischen Frage – es ist ein meritokratisches Verfahren mit offener Beteiligung.

## 7.7. Die GKP als materielle Grundlage der Einheit der Menschheit

Eine marxistische Analyse erfordert es, die Frage präzise zu stellen: Warum ist die Menschheit gespalten? Nicht, weil Menschen von Natur aus böse oder nationalistisch sind. Sondern weil das Überleben einer Gruppe historisch auf Kosten einer anderen erreicht wurde – durch die Kontrolle über Ressourcen, Märkte und Arbeitskräfte. Nationen, Grenzen, Kriege – das ist der Überbau über der materiellen Basis konkurrierender Interessen. Beseitige den Wettbewerb um Ressourcen – und die materielle Grundlage der Spaltung verschwindet.

Die GKP tut genau das – aber nicht durch eine Erklärung der Brüderlichkeit der Völker, sondern durch eine Veränderung der Struktur der Produktionsverhältnisse. Wenn Produktion und Verteilung als ein einziges planetares System ohne Privateigentum an den Produktionsmitteln organisiert sind, vergrößert jeder neue Knotenpunkt im Netzwerk die Gesamtkapazitäten aller anderen. Das Überleben eines Knotens geht nicht mehr auf Kosten eines anderen. Das ist kein moralischer Fortschritt – es ist eine Veränderung der materiellen Bedingungen, unter denen Solidarität zu einer rationalen Strategie und nicht zu einem Opfer wird.

Ein historisches Gegenargument, das nicht umgangen werden kann: Jugoslawien war eine wirtschaftlich integrierte Föderation – und zerfiel im Krieg. Handels- und Produktionsintegration allein reichen nicht aus. Slowenien und Kroatien empfanden die föderale Umverteilung als versteckte Ausbeutung – ob zu Recht oder zu Unrecht, diese Wahrnehmung hatte eine materielle Grundlage: Eine undurchsichtige Verteilung lässt immer Interpretationen zu, die jemandem zugutekommen. Gerade diese Undurchsichtigkeit schürte Ressentiments – nicht die Integration an sich.

Hier muss eine theoretisch wichtige Unterscheidung getroffen werden. Die liberale Forderung nach Transparenz ist verfahrenstechnischer Natur: offene Berichte, faire Wahlen, Pressefreiheit. Das ist wichtig – aber nicht ausreichend. Man kann auch auf transparente Weise ungerecht verteilen. Genau darüber schrieb Marx im Zusammenhang mit der bürgerlichen Demokratie: Die Ausbeutung ist legal und sichtbar – aber durch die formale Gleichheit des Vertrags legitimiert. Die Transparenz des Verfahrens beseitigt nicht die Undurchsichtigkeit der Produktionsverhältnisse.

Transparenz in einem System ohne Privateigentum an den Produktionsmitteln ist von Natur aus grundlegend anders. Und hier die zentrale These: Sie erfordert keine institutionelle Durchsetzung – denn das strukturelle Motiv der Intransparenz verschwindet.

Im Kapitalismus ist Intransparenz funktional: Sie schützt den Profit, verbirgt das Ausmaß der Ausbeutung, ermöglicht Preisdiskriminierung und verschafft Wettbewerbsvorteile. Ein Unternehmen verbirgt seine Selbstkosten nicht aus Boshaftigkeit – sondern weil eine Offenlegung die Profitquelle zerstört. Intransparenz ist eine strukturelle Notwendigkeit eines Systems, das auf der Aneignung von Mehrwert basiert.

Gibt es keine Aneignung, gibt es auch keinen Grund zum Verbergen. Der Verteilungsalgorithmus ist nicht deshalb offen, weil dies in der Verfassung so festgeschrieben ist, sondern weil niemand ein Interesse daran hat, ihn zu verschließen. Es handelt sich nicht um Transparenz als Forderung, sondern um Transparenz als natürlichen Zustand eines Systems ohne versteckte Interessen. Genauso wie in einer Familie kein Wirtschaftsprüfer nötig ist, um zu überprüfen, ob das Abendessen gerecht verteilt wird – nicht weil die Familie ideal ist, sondern weil die Beziehungsstruktur keinen Grund zum Verbergen schafft.

Genau das unterscheidet die GKP von Jugoslawien und von der EU, wo die Peripherie bei formal offenen Institutionen der eigentliche Geldgeber des Zentrums ist. In der EU sind die Verfahren transparent – aber die Produktionsverhältnisse sind undurchsichtig: billige Arbeitskräfte aus Polen und Rumänien, Braindrain, die strukturelle Unmöglichkeit, bei offenen Märkten mit der deutschen Industrie zu konkurrieren. Das ist kein Regelverstoß – das ist die Funktionsweise des Systems. Die GKP beseitigt nicht das Symptom, sondern die Ursache: Der private Interesse, der Undurchsichtigkeit lohnenswert macht, verschwindet.

Das ist die materialistische Begründung der Einheit – nicht durch einen moralischen Appell, nicht durch institutionelle Transparenz als Verfahren, sondern durch die Beseitigung des strukturellen Motivs für eine verdeckte Umverteilung zugunsten bestimmter Gruppen. Die Menschheit vereint sich nicht, weil sie beschlossen hat, sich zu vereinen – sondern weil die materiellen Bedingungen, unter denen eine Trennung rational war, nicht mehr bestehen.

