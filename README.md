# NewsApp

This is just a simple Android native app written in Kotlin for searching news headlines based on NewsApi.org's API. 

# Api

NewsApi.org provides a simple and easy way to fetch news headlines for different topics and sources with its REST api. To fetch news from them, you just need to sign up for a free developer account and get an API key. All you need to do is make a simple HTTP request by providing the following parameters and it’ll return results in JSON.


Parameters required for NewsAPI HTTP request

q = the text or topic to query
from – the date published in the format of yyyy-MM-dd
sortBy – how you want to sort the news, you can just simply use publishedAt, meaning sorting by its published date
apiKey – this is your API_KEY after you’ve signed up and signed into your developer account.
language – and you can specify the language of the news e.g. en is English

# Android components

* RecyclerViewAdapter
* SearchViewOnChangeListener
* NewsResult 
* Article 
* Glide
* AsyncTask
* NewsFetchedListener

<p><img width="400" height="822" src="https://user-images.githubusercontent.com/67858418/88122235-a0e75880-cbfa-11ea-9bd7-11c977b47d6e.gif" border=0 /></p>
