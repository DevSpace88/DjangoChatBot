# DjangoChatBot
Chat with the Django Documentation (or any other docs). 

Made with LangChain using Open AI Rest-API.

You need to provide your own API-Key from Open AI in a .env file with something like this in it: `OPENAI_API_KEY = "secret_key here"`

Then run `db_builder.py`. This will scrape the contents page of Django and store all of it in a Chroma vector database.

You can use any other documentation or website, if you like, you just have to change the `root_url` in `scraper.py` with a page that provides links

run `db_query.py`
