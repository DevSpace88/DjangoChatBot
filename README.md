# DjangoChatBot
Chat with the Django Documentation. 

Made with LangChain using Open AI Rest-API.

You need to provide your own API-Key from Open AI in a .env file with something like this in it: `OPENAI_API_KEY = "secret_key here"`

Then run `db_builder.py`. This will scrape the contents page of the Django documentation and store all of it in a Chroma vector database.

run `db_query.py`
and ask the django documentation your questions, you can ignore the stuff in green.
