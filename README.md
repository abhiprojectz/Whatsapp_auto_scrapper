# Hello there,

This is the Whatsapp web scraper that can scrap the whatsapp chats messages from both:

+ Groups
+ Contacts 

# Getting started

Install all the requirements.

Just locate the driver (or the driver path under `driver_path` variable) into the whatsapp_scrape package.

> Remember: it will be placed there in that same directory.

(you can also change the paths easily)


# Features

+ Login onces and use it forever!
+ Extra customizations added inorder to customize it easily.
+ Save to CSV File
+ Save to SqliteDB
+ Save to JSON



# Examples

Just run the following code to test it:

```py
from whatsapp_scrape.scraper import locate_chat

def main():
	locate_chat() # Type here the name to scrap


if __name__ == '__main__':
	main()

```

This will locate your chat!

Further more, you can also run all the testcases.

# Key note

Remember before running the test cases be sure to run the `scrape.py` first.