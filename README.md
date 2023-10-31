# Web  Q&A with Embeddings

Learn how to crawl your website and build a Q/A bot with the OpenAI API. You can find the full tutorial in the [OpenAI documentation](https://platform.openai.com/docs/tutorials/web-qa-embeddings).

Split the web-qa.py file into two files:

web-qa-scrape.py
This has top half of original code to scrape the site, create the embeddings and output files. It has been modified to meet the needs of my Wordpress 009co.com website. Mostly to ignore some urls eg files such as png, pdf, and some Wordpress comments and responses.

web-qa-answer.py
This has bottom half of original code to ask questions and retrieve answer using the embeddings.

The scraped text is in the text folder. The embeddings created from the scraped text are in the processed folder.