# techreview_arxiv_scrape

The data and partial code behind the story "<a href='https://www.technologyreview.com/s/612768/we-analyzed-16625-papers-to-figure-out-where-ai-is-headed-next/'>We analyzed 16,625 papers to figure out where AI is headed next</a>" on <a href='https://www.technologyreview.com/'>MIT Technology Review</a>.

## Files
* `arxivscraper.py`: A modified version of <a href='https://github.com/Mahdisadjadi/arxivscraper'>Mahdisadjadi/arxivscraper</a>
* `arxivscraper_all_cs_ai.ipynb`: The code for scraping metadata from the arXiv
* `cs_ai_through_2018-11-18.csv`: The metadata for all scientific papers published to the AI section of the arXiv through November 18, 2018
* `arxivscraper_ai_only_analysis.ipynb`: The code for calculating the terms with the greatest losses and gains in the top 100 words & bigrams

## Data columns
* `id`: arXiv paper id
* `title`: paper title
* `categories`: the arXiv categories under which the paper was filed
* `abstract`: paper abstract
* `doi`: digitial object identifier
* `created`: date of paper's upload
* `updated`: date of paper's latest update
* `authors`: paper authors last names
* `year`: year and month of paper's upload

## Source
* <a href='https://arxiv.org/'>arXiv.org</a> > <a href='https://arxiv.org/list/cs.AI/recent'>Artificial intelligence</a> 
