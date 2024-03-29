# [Institute for Advanced Analytics](https://analytics.ncsu.edu/)
Cloud AI & Machine Learning - Dan Zaratsian, March 2024


---
## IAA Module - Session 1 - Course Intro

[**Slides**](https://docs.google.com/presentation/d/1CC03MXct8pW9DblZ4i7sICcYlbXg81xgyB1DLtDh_ig/edit?usp=sharing)

* Intro and Module Agenda
* Class Poll
* Trends in AI/ML
* ML Architectures
* [Google Colab Notebook Environment](https://colab.sandbox.google.com/)
* [Google BigQuery Sandbox](https://console.cloud.google.com/bigquery)

---
## IAA Module - Session 2 - SQL and NoSQL Services

[**Slides**](https://docs.google.com/presentation/d/1zB7K2ud91WOKuCENic4WNLz6lSqJ0yUbijYQJ3HbFU0/edit?usp=sharing)

* SQL Databases
* NoSQL Databases
* BigQuery (Serverless SQL)
* [BigQueryML](https://cloud.google.com/bigquery-ml/docs/introduction)
* Google Cloud Firestore (NoSQL)

**Assignments**
* [Assignment 1 SQL](./session_02/Assignment_1_SQL.md)
  - Due on Thursday, March 14, 2024 at 11:59pm EST
  - Please complete as an individual assignment
  - Email your code and answers to d.zaratsian@gmail.com

* [Assignment 2 NoSQL](https://colab.research.google.com/drive/1Fp8OYxF9cyY-WIinV4w4IXOxCIRMW0v3?usp=sharing)
  - Due on Thursday, March 14, 2024 at 11:59pm EST
  - Please complete as an individual assignment
  - No need to email your code for assignment #2 unless you want specific code / syntax feedback. I'll be able to see the submitted results within the Firestore DB.

---
## IAA Module - Session 3 - Spark Data Processing & Machine Learning

[**Slides**](https://docs.google.com/presentation/d/1JG4nMPv1ryovSpZG62XGS0frzpb0c82EEincZZ7acMU/edit#slide=id.g7167105720_0_348)

* [Apache Spark](https://spark.apache.org/) Overview
* Spark Machine Learning ([MLlib](https://spark.apache.org/docs/latest/ml-guide.html))
* [ML Pipelines](https://spark.apache.org/docs/latest/ml-pipeline.html)
* Building and deploying Spark machine learning models
* Considerations for ML in distributed environments
* Spark Code Walk-through (within Google Colab)

**Assignment**
* [Assignment 3 - SparkML](https://colab.research.google.com/drive/1AVRfN0SUVBiX5V7YpaMyn4BFu4dmr3Ht?usp=sharing)
  - Due on Friday, March 22 at 11:59pm EST
  - Please complete as a team/group assignment (or if you prefer, you're welcome to complete on your own).
  - Email your code to d.zaratsian@gmail.com and include the names of everyone on your team.

---
## IAA Module - Session 4 - Cloud Services for Generative AI

[**Slides**](https://docs.google.com/presentation/d/1tMwEf6bC5CYKCqaFMnJvEAVhoVe8rNujV_OelGFInuA/edit?usp=sharing)

* [GenAI on Google Cloud](https://cloud.google.com/vertex-ai/generative-ai/docs/learn/overview)
* [Google Gemini Multimodal Models](https://cloud.google.com/vertex-ai/generative-ai/docs/multimodal/overview)
* [Langchain](https://python.langchain.com/docs/get_started/introduction)
* [Huggingface Models](https://huggingface.co/models)
* [Langchain Integration with Google Cloud](https://python.langchain.com/docs/integrations/platforms/google)
* [Google Gemma Open Model](https://ai.google.dev/gemma) (on Huggingface: [Gemma](https://huggingface.co/google))

**Assignment**
* Assignment 4 - GenAI
  - Due on Friday, March 22 at 11:59pm EST
  - Assignment Details:
    1. Select a Generative AI use case that interests you.
    2. Describe how you would solve the use case. 
        - What technology and framework(s) would you use
        - what prompt design would you consider
        - what LLM would you use
        - what challenges do you anticipate in solving it. 
    3. (Bonus) Prototype the use case by developing GenAI code that starts to prove out your idea. The goal here is to encourage you to start to programatically interact with the GenAI models, work on prompting, and integrate supporting framework or LLM techniques to help you solve your use case. 
    4. Submit your answers using this code and associated structure: 
        ```
        import requests
        payload = {
            "code": "I_WILL_GIVE_THIS_TO_YOU_IN_CLASS",
            "name": "John Smith",
            "use_case": "Using Generative AI to generate a workout plan",
            "tech_stack": "Python, Google Vertex AI Gemini, Flask, Langchain, Spanner, GKE",
            "prompt_design": "I would use prompt ...",
            "llm": "Google Gemini Pro",
            "challgenges": "I foresee a challenge when impelmenting xyz...",
            "link_to_colab_notebook_or_github_page": "https://colab.sandbox.google.com/"
        }
        response = requests.post("https://genai-hw-t3njo4m6mq-uc.a.run.app/submit_hw", json=payload)
        if response.status_code == 200:
            print(f'{response.text}')
        else:
            print(f'{response.text} Status Code: {response.status_code}.')
        ```
  - Please complete as an individual assignment.
  - I'll be able to see you submission when you send it using the code that I provided above. Please be sure to include your name as part of the payload.

---
## IAA Module - Session 5 - Cloud Machine Learning

[**Slides**](https://docs.google.com/presentation/d/11Eu-KjMMDK98c_bMu4qhPhCL4j1wyeOVMiB9bJFONQM/edit?usp=sharing)

* Overview of Google Cloud Machine Learning Services
* [AutoML](https://cloud.google.com/automl)
* [BigQueryML](https://cloud.google.com/bigquery-ml/docs/introduction)
* [Google Vertex AI Platform](https://cloud.google.com/vertex-ai/docs/start/introduction-unified-platform)
* [Google Vertex Notebooks (Workbench)](https://cloud.google.com/vertex-ai/docs/workbench/introduction)
* [Google Deep Learning Containers](https://cloud.google.com/deep-learning-containers/docs/choosing-container)

---
## IAA Module - Session 6 - Cloud Services for ML & Serverless

[**Slides**](https://docs.google.com/presentation/d/1avRm-Ezi4Zj4GiAMR55OgfWN13C7pnvWy6Ck4kya7zQ/edit#slide=id.g7167dab5d9_0_348)

* Overview of Google Cloud Services
* [Cloud Functions](https://cloud.google.com/functions)
* [Cloud Run](https://cloud.google.com/run)
* [Docker](https://docs.docker.com/)
* Open Q&A

---

## References:

* [Google Colab Notebooks](https://colab.sandbox.google.com)
* [Google Vertex AI Platform](https://cloud.google.com/vertex-ai/docs/start/introduction-unified-platform)
* [Google Vertex Notebooks](https://cloud.google.com/vertex-ai/docs/workbench/notebook-solution)
* [Apache Zeppelin Notebooks](https://zeppelin.apache.org/)
* [Apache Spark Docs](https://spark.apache.org/docs/latest/)
* [Google BigQuery](https://cloud.google.com/bigquery/what-is-bigquery)
* [Google BigQuery Sandbox](https://console.cloud.google.com/bigquery)
* [Apache Hive Docs](https://cwiki.apache.org/confluence/display/Hive/GettingStarted)
* [Google Cloud Firestore](https://cloud.google.com/firestore/docs)
* [Apache HBase Docs](https://hbase.apache.org/book.html)
* [Apache Phoenix Docs](https://phoenix.apache.org/)
* [Google Cloud PubSub](https://cloud.google.com/pubsub/docs/concepts)
* [Apache Kafka Docs](https://kafka.apache.org/20/documentation.html)
* [Apache NiFi Docs](https://nifi.apache.org/docs.html)
* [Docker Docs](https://docs.docker.com/)
* [Google Deep Learning Containers](https://cloud.google.com/deep-learning-containers/docs/choosing-container)
