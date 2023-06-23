# Einsatz von NoSQL Apache Cassandra zur Untersuchung von Studienabbrüchen

Dieses Repository enthält den Code und die Daten für eine Studienarbeit, die die Anwendbarkeit und Wirksamkeit von Apache Cassandra und maschinellem Lernen bei der Vorhersage von Studienabbrüchen untersucht.

## Voraussetzungen

* Docker installiert auf Ihrem Computer. Falls nicht, folgen Sie [diesen Anweisungen](https://docs.docker.com/get-docker/) um Docker zu installieren.

## Projektstruktur

```
.
├── data
├── datascience
│   ├── data
│   │   ├── assessments.csv
│   │   ├── courses.csv
│   │   ├── studentAssessment.csv
│   │   ├── studentInfo.csv
│   │   ├── studentRegistration.csv
│   │   ├── studentVle.csv
│   │   └── vle.csv
│   ├── Dockerfile
│   └── notebooks
│       ├── exploratory_data_analysis.ipynb
│       ├── load_data.ipynb
│       └── prediction_model.ipynb
├── docker-compose.yml
├── notebooks
└── README.md
```


## Anleitung zum Starten des Projekts

1. Navigieren Sie zum Repository-Ordner.
```
    cd your-repo
```

2. Starten Sie den Docker-Container
```
    docker compose up --build
```

3. Öffnen Sie Ihren Webbrowser und navigieren Sie zu http://localhost:8888. Sie sollten jetzt das Jupyter Notebook Interface sehen und können mit der Ausführung des Codes beginnen.