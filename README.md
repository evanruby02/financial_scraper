# financial_scraper
  # V1
  # V1 is a barebones scraper, which pulls headlines and links into a CSV file.
  
  # V2
  # V2 is a more thorough scraper which pulls headlines using newspaper3k.
  # Also incorporates a fallback scraper using BeautifulSoup.
  # The CSV output now includes a column for article text.
  # If the scrapers pick up a small, boilerplate response (less than 100 characters, currently)
  # The line item will be removed from the CSV output.

  # V3
  # V3 will incorporate the OpenAI API by passing the CSV file with a prompt through ChatGPT
  # V3 is ...

  # V4
  # V4 may expand on V3 by formatting the output as a newsletter, report, etc.
