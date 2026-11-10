# Web  Q&A with Embeddings

Learn how to crawl your website and build a Q/A bot with the OpenAI API. You can find the full tutorial in the [OpenAI documentation](https://platform.openai.com/docs/tutorials/web-qa-embeddings).

Split the web-qa.py file into two files:

web-qa-scrape.py
This has top half of original code to scrape the site, create the embeddings and output files. It has been modified to crawl my static website at https://curtispokrant.com/ and ignore non-HTML resources such as PNG and PDF files.

web-qa-answer.py
This has bottom half of original code to ask questions and retrieve answer using the embeddings.

The scraped text is in the text folder. The embeddings created from the scraped text are in the processed folder.

The `text/009co.com/` directory and the existing processed CSV files are historical snapshots of the previous website. Run the scraping and embedding steps again to build a corpus for the current site.
