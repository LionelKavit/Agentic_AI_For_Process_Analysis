# Agentic_AI_For_Process_Analysis

Transformed a steel parts firm’s process capability analysis by integrating an agentic
AI decision-support system, reducing a 2.5-hour manual workflow to 20 minutes. I implemented
responsible AI practices by standardizing analysis logic and governance frameworks using call
tools (MCP) and RAG, respectively, while maintaining human-in-the-loop oversight.

The implemented Azure AI solution integrates multiple Azure AI services:
• A fully functional Prompt Flow hosted in an Azure AI Hub Project.
• End-to-end data ingestion from Azure Blob Storage using a Python data access node.
• Parallel analytical branches for Process capability analysis and Process behavior (stability) analysis.
• A persistent, RAG-backed Aggregator Agent hosted in an Azure AI Foundry Project that
synthesizes results into a leadership-ready narrative.

If I had to explain the architecture to a non-technical manager, I would describe it as a decision
pipeline: raw process data goes in, specialized steps analyze stability and capability in parallel,
and a final expert step produces a clear recommendation. Each component does one job well,
which makes the system easier to understand and trust.

I see this pattern being valuable anywhere data-driven decisions require interpretation, not just
metrics – such as financial analysis or risk reviews.
