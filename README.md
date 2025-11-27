

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

NAME: DARSHAN B
REGISTER NUMBER : 212222080013

Aim:
To study and evaluate various prompt templating techniques for generating accurate, consistent, and comprehensive industrial maintenance reports. This experiment will demonstrate how different prompt patterns—such as Instructional, Comparison, Command, Q&A, Opinion, and Scenario—can be leveraged to automate distinct sections of a technical report, from raw data inputs to a finalized document.

Algorithm
Step 1: Define the Use Case & Scope

Goal: Automate the generation of a maintenance report for an industrial HVAC (Heating, Ventilation, and Air Conditioning) unit.
Input Data: Technician's raw notes (e.g., component status, actions taken, meter readings).
Output: A structured, professional maintenance report.
Step 2: Design Prompt Templates for Each Pattern

Create specific prompt templates for each of the six patterns.

Each template will be designed to generate a specific part of the maintenance report (e.g., summary, recommendations, diagnostics).

Step 3: Execute Prompts & Generate Report Sections

Use the technician's raw notes as input for the prompt templates.
Generate outputs for each section of the report.
Step 4: Analyze & Review Outputs

Evaluate the clarity, accuracy, and relevance of the AI-generated content.
Compare the effectiveness of each pattern for its intended task.
Introduction
Manual creation of maintenance reports is often time-consuming, prone to human error, and can lead to inconsistent documentation across an organization. Automating this process with AI can significantly boost efficiency and standardization.

This experiment explores how prompt templating can create a robust system for report generation. By applying different prompt patterns, we can control the AI's output to fit the precise requirements of each section of a technical report, turning messy field notes into a polished, actionable document.

AI Tools Required
ChatGPT (or any LLM-based AI tool): The core engine for generating reports based on prompts.

Text Editor (MS Word/Google Docs): For organizing the experiment, prompts, and outputs.

Optional: JSON/CSV data source for structured inputs: For advanced scenarios where raw data might be pre-organized.

image
Concept Explanation: Prompt Templating
Prompt Templating is a technique where reusable, pre-defined prompt formats (templates) are created. These templates guide the AI to generate outputs that are consistent in structure, tone, and content, making them highly reliable.

In the context of automated maintenance reporting, templating helps to:

Standardize Report Structure: Ensures every report follows the same format, regardless of the technician or issue.

Reduce Human Errors: Minimizes omissions or inconsistencies that can occur in manual reporting.

Improve Readability: Makes reports easier to understand and act upon.

Save Time: Significantly speeds up the report generation process. Here's a visual representation of how templating streamlines the process:

image
Workflow of Prompt Templating
image
Prompt Template Design
Template 1: Instructional Prompt
📌 Structure:

“Generate a maintenance report for [Machine/Equipment Name]. Include:

Date of service

Issue reported

Diagnostic steps taken

Actions performed for repair

Spare parts used (with part numbers if available)

Total downtime incurred

Preventive recommendations”

✅ Ensures all critical sections are covered.

Template 2: Structured/Tabular Prompt
📌 Structure:

“Create a structured maintenance report in table format with the following fields:

| Date | Equipment Name | Issue Reported | Actions Taken | Spare Parts Used | Downtime | Technician Name | Recommendations |”

✅ Highly scannable & database-friendly.

Template 3: Scenario-Based Prompt
📌 Structure:

“Assume you are a senior maintenance engineer. Write a detailed report for [Machine Name] where the issue was [Specific Issue]. Include:

Problem description

Diagnostic process

Repair actions taken

Replaced components

Final status of equipment
Long-term preventive measures”

✅ Produces a narrative, expert-level report. image

Test Scenarios
Outputs
Evaluation & Findings
Naïve prompts consistently generate incomplete, vague, and professionally unusable reports. They lack the necessary detail for proper documentation or follow-up actions.
Template-based prompts ensure all critical data points are included, resulting in reports that are accurate, consistent, and adhere to a professional format.
Structured formats (like tables and lists) are highly effective for official maintenance documentation, as they present key information in a clear and easily digestible manner.

Result
The study of prompt templating techniques for automated maintenance report generation was successfully executed. It is clearly observed that templated prompts significantly improve the quality, clarity, and standardization of generated reports compared to naïve prompts. The use of specific templates (Instructional, Tabular, and Scenario-based) allows for precise control over the AI's output, ensuring that the final document is fit for its intended technical purpose. This methodology proves to be a valuable tool for streamlining documentation, reducing manual effort, and enhancing operational efficiency.
