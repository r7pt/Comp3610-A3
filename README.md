# Comp3610-A3

**# NYC Taxi Intelligence System 🚖

This project is a RAG system that helps users analyze NYC Taxi data. It can calculate math from a massive database and read complex policy documents at the same time.

The project can distingish types of quries and determine what model to use based on your question.

1.  Ask a Question: You type a question in plain English.
2.  Route: The system decides if it needs **Data** (Spark), **Documents** (RAG), or **Both**.
3.  Process Runs code to calculate stats.
   Document path Searches PDFs for the right paragraph.



**setup**
1.  Load the yellow_taxi_data.parquet.
2.  Add your PDF documents to the /documents folder.
3.  Run the process_query() function 
