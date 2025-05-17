# Lesson 1: What Do Data Engineers Do?

## Assignment

> Imagine that you are hired to enable data analytics; where would you start? How would you go about gathering requirements? 
> 
> **Hint:** Think backward from what the business may need. Share your assignment with me by creating a repo [(like this one if you haven't already)](https://github.com/josephmachado/sde_de101_josephmachado) and writing down your notes/code under the folder for lesson 1.

---

## Answer

### 1. Stakeholder Engagement & Requirements Gathering
The first step is to meet with the various stakeholders to define business needs and answer the following questions:

- **What is the data strategy of the company?**
- **What data is going to be collected and how will it be collected and stored?**
- **Will the data architecture need to evolve with business needs?**
- **Who are the end users, and what information do they need to use the data effectively?**
- **Will the data be shared externally? If yes, what data will be shared?**

#### Prioritizing & Reconciling Requirements
After gathering these requirements, it's crucial to prioritize them based on business impact and technical feasibility. This involves:
- Identifying critical business needs that drive immediate value
- Assessing technical complexity and resource requirements
- Creating a phased implementation plan
- Establishing a process for handling conflicting stakeholder needs, such as:
  - Documenting all requirements and their business justification
  - Facilitating discussions between stakeholders to align on priorities
  - Creating a scoring system to objectively evaluate requirements
  - Setting up regular review meetings to adjust priorities as needed

---

### 2. Data Strategy & Modeling
Once a comprehensive view of the data strategy is established, the next step is to choose a data warehouse and create a data model. Considerations include:
- Ensuring data quality
- Designing for efficient queries
- Planning for scalability from the start

---

### 3. ETL & Data Pipeline Planning
- Plan ETL and storage for each stage
- Choose data sources and establish agreements with source system managers
- Ensure changes in source systems won't break the pipeline
- Decide on data transformation according to business needs
- Plan how data will be loaded into the destination system

---

### 4. Pipeline Scheduling, Execution & Monitoring
- Plan the schedule, execution, and monitoring of the pipeline
- Decide how the scalable pipeline will be run (scheduled or event-driven)
- Assign necessary permissions
- Monitor for failures, jams, or long-running tasks
- Track metadata (run time, completion time, reasons for failures)

---

### 5. Data Serving & Access
- Design dashboards or data visualizations if necessary
- Decide how permissions will be granted according to the principle of least privilege
- If applications or external clients need API access, plan to set up a server to send data to an endpoint
- If a client requires a data dump, plan a pipeline for this process

---

## Summary

Enabling data analytics begins with a deep understanding of business needs through stakeholder engagement and careful requirements gathering. By prioritizing and reconciling these needs, designing robust data models and pipelines, and planning for secure, scalable data access, a data engineer ensures that data solutions are both effective and aligned with organizational goals.

---

## Reference
- [6 Responsibilities of a Data Engineer](https://www.startdataengineering.com/post/n-job-reponsibilities-of-a-data-engineer/)