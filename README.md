# Experiment 5: Study of Prompt Templating Techniques for Automated Maintenance Report Generation

### NAME: DEEPIKA S
### REGISTER NUMBER : 212222230028

### Aim: 
To study and evaluate various prompt templating techniques for generating accurate, consistent, and comprehensive industrial maintenance reports. This experiment will demonstrate how different prompt patterns—such as Instructional, Comparison, Command, Q&A, Opinion, and Scenario—can be leveraged to automate distinct sections of a technical report, from raw data inputs to a finalized document.

---
### Algorithm
1. Step 1: Define the Use Case & Scope

   - Goal: Automate the generation of a maintenance report for an industrial HVAC (Heating, Ventilation, and Air Conditioning) unit.
   - Input Data: Technician's raw notes (e.g., component status, actions taken, meter readings).
   - Output: A structured, professional maintenance report.

2. Step 2: Design Prompt Templates for Each Pattern

   - Create specific prompt templates for each of the six patterns.

   - Each template will be designed to generate a specific part of the maintenance report (e.g., summary, recommendations, diagnostics).

3. Step 3: Execute Prompts & Generate Report Sections

   - Use the technician's raw notes as input for the prompt templates.
   - Generate outputs for each section of the report.

4. Step 4: Analyze & Review Outputs

   - Evaluate the clarity, accuracy, and relevance of the AI-generated content.
   - Compare the effectiveness of each pattern for its intended task.
  
   ---


###  Introduction
Manual creation of maintenance reports is often time-consuming, prone to human error, and can lead to inconsistent documentation across an organization. Automating this process with AI can significantly boost efficiency and standardization.

This experiment explores how prompt templating can create a robust system for report generation. By applying different prompt patterns, we can control the AI's output to fit the precise requirements of each section of a technical report, turning messy field notes into a polished, actionable document.

---

### AI Tools Required
- ChatGPT (or any LLM-based AI tool): The core engine for generating reports based on prompts.

- Text Editor (MS Word/Google Docs): For organizing the experiment, prompts, and outputs.

- Optional: JSON/CSV data source for structured inputs: For advanced scenarios where raw data might be pre-organized.

  <img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/a175a0dc-3ded-4287-81b7-c173bfad7aa2" />


---


### Concept Explanation: Prompt Templating
Prompt Templating is a technique where reusable, pre-defined prompt formats (templates) are created. These templates guide the AI to generate outputs that are consistent in structure, tone, and content, making them highly reliable.

In the context of automated maintenance reporting, templating helps to:

- Standardize Report Structure: Ensures every report follows the same format, regardless of the technician or issue.

- Reduce Human Errors: Minimizes omissions or inconsistencies that can occur in manual reporting.

- Improve Readability: Makes reports easier to understand and act upon.

- Save Time: Significantly speeds up the report generation process.
Here's a visual representation of how templating streamlines the process:
<img width="512" height="512" alt="image" src="https://github.com/user-attachments/assets/3381a7cf-1585-400e-a00a-9030763a961d" />

---

### Workflow of Prompt Templating
<img width="1024" height="1536" alt="image" src="https://github.com/user-attachments/assets/b0803ef3-42bc-49d4-888b-0c94c4061015" />



  ---

### Prompt Template Design
#### Template 1: Instructional Prompt

📌 Structure:

“Generate a maintenance report for [Machine/Equipment Name]. Include:

1. Date of service

2. Issue reported

3. Diagnostic steps taken

4. Actions performed for repair

5. Spare parts used (with part numbers if available)

6. Total downtime incurred

7. Preventive recommendations”
8. ✅ Ensures all critical sections are covered.

  ---

### Template 2: Structured/Tabular Prompt

📌 Structure:

“Create a structured maintenance report in table format with the following fields:

| Date | Equipment Name | Issue Reported | Actions Taken | Spare Parts Used | Downtime | Technician Name | Recommendations |”

✅ Highly scannable & database-friendly.

  ---

### Template 3: Scenario-Based Prompt

📌 Structure:

“Assume you are a senior maintenance engineer. Write a detailed report for [Machine Name] where the issue was [Specific Issue]. Include:

1. Problem description

2. Diagnostic process

3. Repair actions taken

4. Replaced components

5. 6. Final status of equipment

Long-term preventive measures”

✅ Produces a narrative, expert-level report.
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/29168745-334d-4289-a4b1-b82d3ca8f01b" />


---

### Test Scenarios
<img width="2364" height="1582" alt="image" src="https://github.com/user-attachments/assets/e52cf53e-d691-414c-a7fc-74aa0d4a4a41" />


### Outputs
#### Evaluation & Findings
- Naïve prompts consistently generate incomplete, vague, and professionally unusable reports. They lack the necessary detail for proper documentation or follow-up actions.
-  Template-based prompts ensure all critical data points are included, resulting in reports that are accurate, consistent, and adhere to a professional format.
-  Structured formats (like tables and lists) are highly effective for official maintenance documentation, as they present key information in a clear and easily digestible manner. give me this in a image format

<img width="320" height="180" alt="image" src="https://github.com/user-attachments/assets/d141f8be-4633-4c50-afd3-7db93418096f" />

---

### Result
The study of prompt templating techniques for automated maintenance report generation was successfully executed. It is clearly observed that templated prompts significantly improve the quality, clarity, and standardization of generated reports compared to naïve prompts. The use of specific templates (Instructional, Tabular, and Scenario-based) allows for precise control over the AI's output, ensuring that the final document is fit for its intended technical purpose. This methodology proves to be a valuable tool for streamlining documentation, reducing manual effort, and enhancing operational efficiency.



  








