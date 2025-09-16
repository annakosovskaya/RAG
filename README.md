<h2 align="center">Building a minimal Retrieval-Augmented Generation pipeline</h2>

<p align="center">
  <img src="https://python.langchain.com/assets/images/rag_concepts-4499b260d1053838a3e361fb54f376ec.png"
       width="640" alt="RAG concepts">
  <br>
  <sub><a href="https://python.langchain.com/docs/concepts/rag">Source</a></sub>
</p>


This repo provides an RAG tutorial. You will build a simple Retrieval-Augmented Generation pipeline using the [ETH Zurich Degree Programmes PDF](https://ethz.ch/content/dam/ethz/main/education/bachelor/studiengaenge/files/ETH-Zurich-Degree-programmes.pdf) as the corpus. We begin by showing why plain LLM queries on this document don't always work, continuing with setting up the RAG pipeline.

⚠️ This notebook uses the 2025 release of the corpus file. If it has changed, the exact version we used is included in this repository. Please note that the current questions target 2025 figures and won’t match the file updates.
