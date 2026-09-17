** SURETRUST **

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<div style="padding: 20px; border: 2px solid #ddd; border-radius: 12px; width: 90%; margin: auto; background: #fafafa; font-family: Arial;">

<h2 style="color:#333;">Student Details</h2>

<div align="left" style="margin: 20px; font-size: 16px;">

<p><strong>Name:</strong> Manyam Geetha Sree</p>

<p><strong>Email ID:</strong>geethamsree9@gmail.com</p>



<p><strong>Branch/Specialization:</strong> Information Science Engineering</p>



</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />

<h2 style="color:#333;">Course Details</h2>

<div align="left" style="margin: 20px; font-size: 16px;">

<p><strong>Course Opted:</strong> Generative AI- SURE TRUST</p>

<p><strong>Instructor Name:</strong> prujith ramakrishnan</p>

<p><strong>Duration:</strong> 6 months</p>

</div>



</div>

</div>

<hr style="border: 0; border-top: 1px solid #ccc; width: 80%;" />



## **Overall Learning**

During my SURE ProEd Generative AI internship, I developed a practical understanding of Generative AI, Retrieval-Augmented Generation (RAG), embeddings, semantic search, agent-based workflows, and AI-assisted software development.

The internship provided hands-on exposure to understanding real-world problems, researching suitable AI techniques, designing system architectures, working with datasets, implementing retrieval pipelines, and documenting technical solutions.

As part of the internship, I worked on **DebugAssist: Intelligent Bug Diagnosis & Resolution**, an AI-powered system designed to assist developers in analyzing software bugs, identifying similar historical defects, determining possible root causes, and suggesting suitable resolutions.

Through this project, I strengthened my skills in:

- Generative AI concepts
- Retrieval-Augmented Generation (RAG)
- Text embeddings
- Semantic similarity search
- Historical defect analysis
- Multi-agent system design
- Python development
- Streamlit application development
- Data preprocessing and analysis
- Software debugging concepts
- Technical documentation
- Problem-solving and system design

---

## **Project Completed**

<div align="left" style="margin: 20px; font-size: 16px;">

<p>
<strong>
<a href="#project1">Project:</a>
</strong>
DebugAssist: Intelligent Bug Diagnosis & Resolution
</p>

</div>

---

<!-- Project 1 -->

<h2 id="project1">Project 1: DebugAssist – Intelligent Bug Diagnosis & Resolution</h2>

## **Project Introduction**

**DebugAssist: Intelligent Bug Diagnosis & Resolution** is an AI-powered software debugging assistance system designed to help developers analyze and resolve software defects more efficiently.

The system accepts bug reports, stack traces, error logs, or related debugging information and processes the submitted information to identify important characteristics of the defect.

It uses a combination of:

- Natural Language Processing
- Text embeddings
- Semantic similarity
- Retrieval-Augmented Generation concepts
- Historical defect analysis
- Multi-agent architecture

The system maintains a **Historical Defect Knowledge Base** created using publicly available software defect datasets from sources such as Mozilla, Apache, and Eclipse through Kaggle.

The historical defects are processed and converted into embeddings so that a newly submitted bug can be compared with previously reported defects.

The retrieved historical defects provide additional context that can help the system analyze the current issue and generate more relevant findings and possible resolutions.

## **How the System Works**

The overall workflow of DebugAssist can be represented as follows:

```text
                         User
                           |
                           v
              Bug Submission Module
                           |
                           v
        Bug Report / Stack Trace / Error Log
                           |
                           v
              Text Processing & Chunking
                           |
                           v
                    Text Embeddings
                           |
                           v
             Semantic Similarity Search
                           |
                           v
        Historical Defect Knowledge Base
                           |
                           v
                 Multi-Agent Pipeline
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v
   Triage Agent      Log Analysis Agent   Root Cause Agent
        |                  |                  |
        +------------------+------------------+
                           |
                           v
                 Duplicate Detection
                       Agent
                           |
                           v
                  Remediation Agent
                           |
                           v
              Structured Findings
                           |
                           v
                 Resolution Display
