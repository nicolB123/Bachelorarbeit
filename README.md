# Vergleichende Analyse von Retrieval-Konfigurationen und Bewertung der Antwortgenerierung für ein RAG-System

**Abstract:**

Das moderne Umfeld von Retrieval-Augmented Generation ist sehr vielfältig. Das Ziel dieser Arbeit ist 
das Testen verschiedener Retrieval-Konfigurationen durch ein speziell dafür ausgelegtes und imple
mentiertes RAG-Webapp System sowie die Bewertung der finalen Antwortgenerierung des Large Lan
guage Models im RAG-Generator. Durch die Retriever Analyse können Retrieval Modelle anhand der 
Fraunhofer IRB SCHADIS Datenbank nach Information Retrieval spezifischen Metriken auf Performance 
verglichen werden. Sie basiert auf einem Expertendatensatz. Die Generator Analyse basiert auf einer 
LLM-as-a-Judge Methodik und bewertet als auch vergleicht die RAG-Antwort mit der externen Ausgabe 
eines Large Language Models der gleichen Abfrage und bringt Schlüsse zur Verbesserung des produktiv 
RAGs hervor.

**Themengebiete und Tätigkeiten:**

Generelles Theme von RAG: Verbindung von Algorithmik mit narrativen LLM Fähigkeiten.

**-> Business Analytics:**

Performance Analyse von Retriever-Konfigurationen nach Information Retrieval Metriken (Precision, Recall, F1, MRR, NDCG) und Ergebnisanalyse des Generators nach LLM-as-a-Judge Verfahren

Auswerten und Interpretieren der Metriken

**-> Business Intelligence:**

Visualisierung der Retriever und Generator Ergebnisse in Visuals aufgrund ihres Datenmodells mit Calculated Columns, Measures und Filter

**-> Software-Engineering:**

Komplette Überarbeitung der RAG-Webapp in Frontend und Backend + Modifizieren des Retriever

**-> Backend:**

Neue Code-Struktur und Pipeline, um automatisiert Retrieval-Konfigurationslinien zu initialisieren (Chunking, Embedding, Indexing, Scoring)

Bewertungssystem mit Endpunkt für den Export der Ratings (Join von relationaler SQLite mit Milvus Vektordatenbank zur Export Laufzeit)

Endpunkt um Ratings vom Frontend an das Backend zu schicken und in SQLite zu schreiben

**-> Frontend:**

Webapp UI-Rail für Evaluierung der Chunks

Frontend Logik in Bezug auf das Rail, Container und Webstruktur

**-> Modelle und Algorithmen:**

Retriever Komponenten (Chunking Strategien, Embedding Modelle, Indexing Verfahren, Scoring Modelle)

Suchalgorithmen für Ähnlichkeitssuche

**-> Datenbanken:**

Vektordatenbank Milvus

Relationale Datenbank SQLite

**-> Large Language Models:**

Funktionsweise Input, Intermediate, Output Layer

Augmentation in Input, Intermediate, Output Layer

Prompt-Engineering
