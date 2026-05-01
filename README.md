<h2 align="center">Building a minimal Retrieval-Augmented Generation pipeline</h2>

🔗 [Colab notebook](https://colab.research.google.com/drive/1Gs8v3nVyJz-kTvGbhUh8KPFEiuAUIg3M?usp=sharing) • [Colab notebook with solution](https://colab.research.google.com/drive/1fEY4CUTnM-3yCb80GEJBnfeT2zKp0gNX?usp=sharing)

<p align="center">
  <img src="https://i.ibb.co/DPH4LDL3/RAG-picture.png"
       width="640" alt="RAG concepts">
  <br>
  <sub><a href="https://python.langchain.com/docs/concepts/rag">Source</a></sub>
</p>


This repo provides an RAG tutorial. You will build a simple Retrieval-Augmented Generation pipeline using the [ETH Zurich Degree Programmes PDF](https://ethz.ch/content/dam/ethz/main/education/bachelor/studiengaenge/files/ETH-Zurich-Degree-programmes.pdf) as the corpus. We begin by showing why plain LLM queries on this document don't always work, continuing with setting up the RAG pipeline.

⚠️ This notebook uses the 2025 release of the corpus file. If it has changed, the exact version we used is included in this repository. Please note that the current questions target 2025 figures and won’t match the file updates.
