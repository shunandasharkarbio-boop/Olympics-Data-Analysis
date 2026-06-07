This tutorial aims to familiarize me with the Galaxy user interface, with a special focus on highlighting Galaxy’s many RDM (Research Data Management) features.

Galaxy has over 10,000 available tools in its Tool Shed, covering a wide variety of scientific domains, ranging from life sciences to astronomy and digital humanities, and covering techniques from simple text manipulation to advanced machine learning and other complex algorithms.

To keep this tutorial accessible for people with different backgrounds, I perform a toy analysis on a tabular dataset, namely a table of all athletes competing in the Olympics. The question we ask ourselves is “What is the age distribution of Olympic athletes?”. In addition, I want to make sure our analysis is reproducible, so that it can be easily repeated on different datasets and shared with others.

Agenda
In this tutorial, I will cover:

Overview
The Research Data Life Cycle
Galaxy as part of the RDM Life Cycle
Watch
Scope
The Galaxy Web Interface
Create an account on a Galaxy instance/server
What does Galaxy look like?
Collect: Data import
The Galaxy History
Upload a dataset
Dataset attributes (metadata)
Process: Data preparation and QC
Use a tool
Tool provenance
Visualise a dataset
Re-run a tool
Troubleshooting errors
Keeping your history clean
Optional: Use an Interactive Tool
Scaling up
Analyse: Calculate results
Plan our approach
Get summary statistics for our age column
Create a histogram
Extract workflow from our history
Run workflow on all Olympics
Preserve: Export data, history, and workflow
Downloading your history
Exporting your history to a repository
Exporting tool citations
Exporting your workflows
Share: Share or publish data and workflow
Reuse: Find and run workflows shared by others
Where to find Galaxy Workflows
Showcase 1: WorkflowHub
Showcase 2: IWC
