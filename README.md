Entwicklung und Validierung eines Diabetesvorhersagemodells durch logistische Regression


Dieses Projekt bietet einen eingehenden Einblick in die Entwicklung und Validierung eines Diabetesvorhersagemodells mittels logistischer Regression. Hierfür wird ein Datensatz mit vielfältigen Gesundheitsmerkmalen wie Glukosekonzentration, Blutdruck und BMI verwendet, um das Diabetesrisiko einer Person vorherzusagen. Neben der Untersuchung von logistischer Regression und Klassifikationsprozessen hinsichtlich Erfolgsmetriken und Modellvalidierungsmethoden befasst sich das Projekt mit einer End-to-End-Maschinenlernklassifizierungsaufgabe, basierend auf einem realen Datensatz und einem realen Problem. Das Ziel besteht darin, das Diabetesvorhersagemodell mittels logistischer Regression zu entwickeln und seine Leistung anhand von Erfolgsmetriken und Modellvalidierungsmethoden zu bewerten. Die EDA (Explorative Datenanalyse) und das Feature Engineering werden in diesem Projekt nur kurz behandelt, da sie bereits in einem anderen Projekt zu diesem Datensatz ausführlich behandelt wurden.

Das Datenset ist ein Teil einer umfangreichen Datenbank, die am National Institute of Diabetes and Digestive and Kidney Diseases in den USA gepflegt wird. Es
handelt sich um Informationen, die im Rahmen einer Diabetesstudie an Pima-Indianerinnen über 21 Jahren in Phoenix, der fünftgrößten Stadt des Bundesstaates
Arizona, gesammelt wurden. Das Datenset besteht aus 768 Beobachtungen und 8 numerischen unabhängigen Variablen. Die Zielvariable "outcome" gibt an, ob ein
Diabetes-Testergebnis positiv (1) oder negativ (0) ist.

Variablen:
Pregnancies: Anzahl der Schwangerschaften
Glucose: Blutzuckerspiegel
BloodPressure: Blutdruck
SkinThickness: Hautdicke
Insulin: Insulinspiegel
BMI: Body-Mass-Index
DiabetesPedigreeFunction: Funktion zur Berechnung des Diabetesrisikos basierend auf familiärer Vorgeschichte
Age: Alter (Jahre)
Outcome: Diabetesstatus der Person. Betroffen (1) oder nicht (0)


Inhalte:
•	Explorative Datenanalyse (EDA): Durchführung explorativer Datenanalysen, um die Struktur des Datensatzes zu verstehen, die Verteilung der Zielvariable zu visualisieren und die Beziehung zwischen den verschiedenen Variablen zu untersuchen.
•	Analyse unabhängiger Variablen: Untersuchung der unabhängigen Variablen im Datensatz, um ihre Verteilungen und potenziellen Einflüsse auf die Zielvariable zu verstehen.
•	Beziehungsanalyse: Untersuchung der Beziehung zwischen der Zielvariablen und den unabhängigen Variablen, um zu verstehen, welche Variablen das Risiko für Diabetes stärker beeinflussen.
•	Datenverarbeitung: Durchführung von Datenverarbeitungsschritten, um fehlende Werte zu behandeln, Ausreißer zu erkennen und zu skalieren, um den Datensatz für die Modellierung vorzubereiten.
•	Modellierung und Evaluierung: Erstellung eines logistischen Regressionsmodells und Vorhersagen. Verwendung verschiedener Metriken wie der Konfusionsmatrix, dem Klassifikationsbericht und der Fläche unter der ROC-Kurve (ROC AUC) zur Bewertung der Modellleistung. Einsatz der Holdout-Methode zur Validierung des Modells und abschließende Evaluierung mithilfe der 10-fachen Kreuzvalidierungsmethode.
•	Vorhersage für neue Beobachtungen: Treffen von Vorhersagen für neue Beobachtungen durch Auswahl einer zufälligen Beobachtung und Anwendung des Modells zur Vorhersage ihrer Klasse.
