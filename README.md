# Social Media Scrapper
A powerfull social media web crawler/web scrapper that dumps images, tweets, captions, external links and hashtags from Instagram and Twitter in an organized form. It also shows the most relevant hashtags with their frequency of occurrence in the posts.

![alt text](https://github.com/the-javapocalypse/Social-Media-Scrapper/blob/master/SocialMediaScrapper.png)


## Getting Started

#### Video Based Tutorial
[Watch Tutorial](https://www.youtube.com/watch?v=flQ_jxgHou8)

##### 1. Dependencies
Download or Clone the repo, Navigate to the directory containing the files and run the following command in cmd.
```
python setup.py install
```
##### 2. Web Driver
After downloading or cloning the repo, Download [chrome webdriver](https://sites.google.com/a/chromium.org/chromedriver/downloads) or [firefox webdriver](https://github.com/mozilla/geckodriver/releases) and extract it in the root folder of project.

##### 3. Twitter App
For scrapping Twitter, we need to setup a Twitter App. First of all login from your Twitter account and goto [Twitter Apps](https://apps.twitter.com/). Create a new app [(How to create twitter app)](http://www.letscodepro.com/twitter-sentiment-analysis/), goto **Keys and access tokens** and copy Consumer Key, Consumer Secret, Access Token and Access Token Secret. We will need them later.




## Usage
Once you have created a Twitter App and installed the dependencies, you are good to go. Following are the details of the variables used to initialize the scrappers.


| Variable | Default | Description |
| ------ | ------ | ------ |
| tag | Null | The keyword to search |
| limit  | 20 | Number of posts to scrape  |
| Consumer_Key | Null | Consumer Key of Twitter App |
| Consumer_Secret | Null | Consumer Secret of Twitter App |
| Access_Token | Null | Access Token of Twitter App |
| Access_Token_Secret | Null | Access Token Secret of Twitter App |
| lang | 'en'  | Language of tweets to retrieve  |
| browser | 'chrome'  | Either chrome or firefox to use |

## Built With
- Python 3.x
- Tweepy
- Selenium
- Urllib
- openpyxl


## Contributing
- Fork it
- Create your feature branch: git checkout -b my-new-feature
- Commit your changes: git commit -am 'Add some feature'
- Push to the branch: git push origin my-new-feature
- Submit a pull request


## Author
Muhammad Ali Zia

## License
This project is licensed under the MIT License

