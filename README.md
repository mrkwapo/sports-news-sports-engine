
1.	Go to news API web page and create and account to get a news API key: https://newsapi.org/
It will say :
Search worldwide news with code
Get breaking news headlines, and search for articles from over 30,000 news sources and blogs with our news API
Get API key


2.	 Register for API key
3.	Click the Back to Home link
4.	 Browse through APIs and select one you would like to work with.
5.	Your API key will be prefixed on the url of the API
Example key: 01234yourapikeycharactershere
Example url: https://newsapi.org/v2/everything?q=bitcoin&from=2019-03-14&sortBy=publishedAt&apiKey=01234yourapikeycharactershere

6.	Download the latest Jquery at: https://jquery.com/download/ and place in your working directory or use a link to jquery in a script tag such as:     <script data-require="jquery@3.2.1" data-semver="3.2.1" src="https://cdn.jsdelivr.net/npm/jquery@3.2.1/dist/jquery.min.js"></script>
7.	To create a preloader I used mark up found at https://materializecss.com/preloader.html. In the search bar type in preloader and choose the preloader of your choice. But I used the following called Indeterminate:
<div id="loader" style="display:none;">
        <div class="progress">
          <div class="indeterminate"></div>
        </div>
      </div>
