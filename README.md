# Digital Portfolio Artifact: AI Medic Bot

## Professional Bio  
I am a Product Design Engineer with multiple years of experience in data-driven product development, system validation, and cross-functional technical problem-solving. 
My work focuses on translating performance requirements and complex datasets into actionable decisions that improve product safety, functionality, and design outcomes. 
As I expand into graduate-level study in data analytics and artificial intelligence, 
I  intend to  build on this foundation by applying machine learning and intelligent automation to real-world, time-critical domains.

## Personal Value Proposition  
I combine multi-year experience as a Product Design Engineer with emerging expertise in AI and data analytics to develop tools that enhance decision-making in high-stakes environments. 
My strength is converting complex technical and data-driven requirements into practical, efficient, and user-centered systems that reduce risk, accelerate insight, and support smarter operational outcomes.

---

## Artifact #1  
### Title  
AI Medic Bot – A Clinical Decision-Support Chatbot for Emergency Room Scenarios

### Introduction  
This artifact demonstrates the design and development of an AI-enabled clinical support tool intended to assist medical teams during emergency room preparation. 
The project reflects an integration of technical engineering discipline, machine learning concepts, and human-centered system design.

### Description  
AI Medic Bot is a retrieval-augmented generative (RAG) chatbot that processes uploaded medical records and surfaces critical patient risk factors in seconds.
By converting patient files (CSV, PDF, JSON, TXT) into vector embeddings and storing them for semantic retrieval, the system enables rapid access to medically relevant information such as comorbidities, allergies, age-based risks, 
and medication conflicts—reducing the time required for manual chart review in high-pressure situations.

### Objective  
The objective of this project is to demonstrate how natural language processing, embeddings, and user-driven AI interfaces can be combined to support faster, safer decision-making in emergency clinical environments. 
This artifact also serves as evidence of competency in applied machine learning, data ingestion workflows, and AI-aligned product thinking.

### Process  
1. Defined the core problem: time delays and cognitive overload in ER record review.  
2. Mapped essential clinical risk factors based on medical literature and triage standards.  
3. Built a Streamlit interface for file upload and interaction.  
4. Implemented the Gemini text-embedding model to convert data into searchable vectors.  
5. Stored embeddings locally to enable low-latency retrieval and context injection.  
6. Integrated a conversational LLM to generate structured, medically relevant summaries.  
7. Tested the workflow with mock patient datasets to validate extraction accuracy.  
8. Documented ethical scope, limitations, and future improvement pathways.

### Tools and Technologies Used  
- Python  
- Streamlit (user interface)  
- Google Gemini Embedding Model (`text-embedding-004`)  
- Gemini LLM (`gemini-2.5-flash`)  
- Pandas, NumPy (data processing)  
- PyPDF + JSON parsing  
- Local vector database prototype  
- GitHub + Markdown documentation

### Value Proposition  
This system provides clinicians with accelerated access to critical medical information without altering clinical judgment or workflow. 
Its value lies in reducing manual review time, minimizing oversight risk, and enhancing clarity during rapid-response situations.

### Unique Value  
Unlike symptom-checking chatbots or static EHR dashboards, AI Medic Bot is designed as a **context-aware summarization tool**, not a diagnostic model. 
It supports expert users by condensing relevant data, rather than attempting to replace medical expertise.

### Relevance  
- **Academic** – Demonstrates mastery of data ingestion, machine learning application, and artifact-based learning.  
- **Professional** – Bridges engineering experience with AI product development in a regulated, safety-critical industry.  
- **Career Alignment** – Supports transition into AI-integrated product roles within med-tech, decision-support systems, and intelligent automation.  
- **Portfolio Requirement** – Fully satisfies artifact structure and documentation requirements for graduate-level portfolio evaluation.

### References  
Braun, L. & Clarke, V. (2023) *Clinical Decision Support Systems: Frameworks and Applications.* Elsevier Health.  
Jiang, F. et al. (2024) ‘Artificial intelligence in healthcare: Past, present and future’, *Journal of Medical Systems*, 48(2).  
Topol, E. (2019) *Deep Medicine: How Artificial Intelligence Can Make Healthcare Human Again.* Basic Books.  
U.S. Department of Health and Human Services (2022) *Guidance on HIPAA and Machine-Based Clinical Tools.*



