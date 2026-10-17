# Hi, I'm Anna

Business Informatics student (B.Sc., 5th semester) at the University of Hohenheim, focusing on data science and AI. Programming in Java since 2021, first at Hillel IT School and then at university.

## What I study

### Data and models
- Machine Learning
- Applied Artificial Intelligence
- Forecasting
- Statistics
- Business Mathematics

### Software
- Object-oriented programming with Java
- Databases
- Software Architecture

### Business and management
- Accounting
- Management Accounting and Finance
- Project Management

## Programming languages

| Language | Level | What I've built with it |
|---|---|---|
| Java | advanced | Text summarizer with TextRank, an HTTP API and JUnit tests ([text-summarizer](https://github.com/annakryzhanovska/text-summarizer)) |
| Python | intermediate | Machine learning on bank marketing data ([term-deposit-prediction](https://github.com/annakryzhanovska/term-deposit-prediction)) and a timetable generator ([railway-timetable-generator](https://github.com/annakryzhanovska/railway-timetable-generator)) |
| R | intermediate | Geospatial analysis and a Shiny app on vessel traffic ([ais-vessel-traffic-germany](https://github.com/annakryzhanovska/ais-vessel-traffic-germany)) |
| SQL | intermediate | Database design and queries in the Databases module |

## Libraries and tools

### Data science and ML
pandas, scikit-learn, PyTorch, matplotlib, seaborn

### Backend and data
FastAPI, SQL and NoSQL databases, HTML, XML

### Development environments
IntelliJ IDEA, PyCharm, Vim, RStudio, Jupyter, Altair AI Studio, Git and GitHub

## Methods

### Machine learning
Principal component analysis (PCA), k-means clustering, decision trees

### LLMs
Prompt engineering, tokenization, context window management, retrieval-augmented generation (RAG), handling hallucinations

## Featured projects

### [Vessel traffic on German rivers](https://github.com/annakryzhanovska/ais-vessel-traffic-germany)
Queried AIS position data from a PostgreSQL/TimescaleDB database through a REST API, matched ship positions to German rivers with H3 and visualized traffic density along the Rhine in a Shiny app. Deployed with Docker and NGINX.

Stack: R, sf, h3jsr, leaflet, Shiny, Docker

### [Text summarizer](https://github.com/annakryzhanovska/text-summarizer)
Picks the most important sentences of German or English texts with TextRank or word frequency scoring and extracts keywords with TF-IDF. Runs as a command line tool with parallel batch mode or as a web app with a JSON API. 50 JUnit tests.

Stack: Java 17, Maven, JUnit 5

### [Term Deposit Prediction](https://github.com/annakryzhanovska/term-deposit-prediction)
Predicts whether bank clients subscribe to a term deposit, on heavily imbalanced data (4.2% positives). Customer segmentation with PCA and k-means, decision trees tuned with stratified cross-validation and evaluated by F1. Found that the model relies almost entirely on call duration, which is only known after the call, so it cannot be used to decide whom to call.

Stack: Python, pandas, scikit-learn

### [Railway timetable generator](https://github.com/annakryzhanovska/railway-timetable-generator)
Turns a jTrainGraph XML timetable with 14 stations and 42 trains into printable HTML timetables for every train and every station, with unit tests for the weekday validity check.

Stack: Python, XML, HTML

## Contact

[crijanovschi22@gmail.com](mailto:crijanovschi22@gmail.com)
