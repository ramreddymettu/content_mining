<h1>Twitter Streaming Data</h1>
<h4>Content Mining</h4>

This is a project that collects twitter streaming data to build database of Twitter tweet data.
One can provide interested Tags as filters to collect only tweets related to those tags. 
Ex: List drug names to collects tweets on drugs.

## Run the Project
<ul>
  <li>
    Replace Twitter secrets.
  </li>
  <li>
    Create Postgres Database. Replace with the correponding credentials in Notebook. 
  </li>
</ul>

## Tweet object
<ul>
  <li>
    Twitter API returns tweet json as a reponse. Please read <strong>tweet.json</strong> file for better understading.
  </li>
  <li>
    For more information on tweet json object <a href="https://developer.twitter.com/en/docs/tweets/data-dictionary/overview/intro-to-tweet-json.html">click here</a>. 
  </li>
</ul>

<h2>Major Dependencies</h2>
<ul>
  <li>Python 3.5+</li>
  <li>psycopg2</li>
  <li>tweepy</li>
</ul>
