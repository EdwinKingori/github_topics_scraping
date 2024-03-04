Scraping Trending Githun Topics and their Repositories 

Using Python and its ecosystem of libraries to scrape trending github topics including their repositories and creating a dataset of CSV file(s).


Introduction (TO DO):

    - Browse through the github topic site and select the top topics to scrape.
    - Identify the information you'd like to scrape from the site. Decide the format of the output CSV file.
    - Summarize the project idea and outline your strategy in a Juptyer notebook.
    - Tools used include (Python, pandas, BeautifulSoup, requests)

Project Outline:

    - The site to scrape https://github.com/topics
    - Extracting a list of topics from the site. For each topic, I'll extract the topic title, topic page URL and topic description
    - For each topic, I'll get the top 25 repositories in the topic from the topic page.
    - For each repository, I'll grab the repo name, username, stars and repo URL
    - For each topic I'll create a CSV file in the following format:

    Repo Name,Username,Stars,Repo URL
    three.js,mrdoob,69700,https://github.com/mrdoob/three.js
    libgdx,libgdx,18300,https://github.com/libgdx/libgdx
