# Disney Movies Wikipedia WebScraper

[![GitHub contributors](https://img.shields.io/github/contributors/sinjoysaha/Disney-Movies-Wiki-WebScraper.svg)](https://GitHub.com/sinjoysaha/Disney-Movies-Wiki-WebScraper/graphs/contributors/)
[![GitHub forks](https://img.shields.io/github/forks/sinjoysaha/Disney-Movies-Wiki-WebScraper.svg)](https://GitHub.com/sinjoysaha/Disney-Movies-Wiki-WebScraper/network/)
[![GitHub stars](https://img.shields.io/github/stars/sinjoysaha/Disney-Movies-Wiki-WebScraper.svg)](https://GitHub.com/sinjoysaha/Disney-Movies-Wiki-WebScraper/stargazers/)
[![GitHub watchers](https://img.shields.io/github/watchers/sinjoysaha/Disney-Movies-Wiki-WebScraper.svg)](https://GitHub.com/sinjoysaha/Disney-Movies-Wiki-WebScraper/watchers/)
[![GitHub issues](https://img.shields.io/github/issues/sinjoysaha/Disney-Movies-Wiki-WebScraper.svg)](https://GitHub.com/sinjoysaha/Disney-Movies-Wiki-WebScraper/issues/)
[![Profile views](https://gpvc.arturio.dev/sinjoysaha)](https://GitHub.com/sinjoysaha/)
[![GitHub followers](https://img.shields.io/github/followers/sinjoysaha.svg)](https://github.com/sinjoysaha?tab=followers)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat-square&logo=linkedin&color=545454)](https://linkedin.com/in/sinjoysaha)
[![Twitter](https://img.shields.io/badge/-Twitter-blue.svg?style=flat-square&logo=twitter&color=b3e0ff)](https://twitter.com/SinjoySaha)

## Table of Contents

* [About the Project](#about-the-project)
  * [Tasks](#tasks)
  * [Built With](#built-with)
* [Fork the Repo and Contribute](#Fork-the-Repo-and-Contribute)
* [Contact](#contact)

## About the Project

In this [`Webscraping Project`](https://github.com/sinjoysaha/Disney-Movies-Wiki-WebScraper) Jupyter notebook, we scrape the Wikipedia pages for Disney movies to create a Disney Movies dataset. We scrape data like `Title`, `Directed by`, `Produced by`, `Written by`, `Narrated by`,  `Music by`, `Cinematography`, `Edited by`, `Production company`, `Distributed by`, `Release date`, `Running time`, `Country`, `Language` from Wikipedia. We also work with OMDb API to get `imdb`, `metascore`, `rotten_tomatoes` data. The data is stored as JSON and CSV and intermediately using Pickle library in Python.

[![Project Image](docs/images/Disney-Movies-Wiki-WebScraper-projectimage.png)](https://github.com/sinjoysaha/Disney-Movies-Wiki-WebScraper)

### Tasks

* Task 1: Scrape info box from Toy Story 3 Wiki page and save in python dictionary.
* Task 2: Scrape info box for all Disney movies and save in list of python dictionaries.
* Task 3: Clean the data!
  - Strip out all references ([1], [2], etc)
  - Split up long strings
  - Convert 'Running time' field to integer
  - Convert 'Budget' and 'Box office' fields to floats
  - Convert dates to datetime objects
  - Save data using Pickle
* Task 4: Attach IMDb, Rotten Tomatoes, Metascores to dataset using OMDb API.
* Task 5: Save final dataset as JSON and CSV files.

### Built With

* Jupyter Notebook
* Beautiful Soup
* Requests
* Pickle
* Pandas

## Fork the Repo and Contribute

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project (click on `Fork` in the top-left corner)
2. Create your Feature Branch (`git checkout -b feature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature`)
5. Open a Pull Request

## Contact

Sinjoy Saha 
  * [LinkedIn](https://linkedin.com/in/sinjoysaha)
  * [Twitter](https://twitter.com/SinjoySaha)

