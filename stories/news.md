# News

* [Documentation](https://newsapi.org/)

# Stories

## Story 1

```
When I visit /news
I see a list of the top headlines as decided by the News API
And with each headline I see the author's name
And a short description of the article
And the headline itself is a link to the article.
```

## Story 2

```
When I visit /news/search_topic
And I fill in Topic with a string (e.g. Apple, or Congress, etc.)
And I click Search
I am redirected to /news
I see a list of the top headlines related to the topic I entered
And with each headline I see the author's name
And a short description of the article
And the headline itself is a link to the article.
```

## Story 3

```
When I visit /news/search_country
And I select a country name from a dropdown
And I click Search
I am redirected to /news
I see a list of the top headlines from that country
And with each headline I see the author's name
And a short description of the article
And the headline itself is a link to the article.
```

## Story 4

```
When I visit /news/search_source
And I enter a valid news source (e.g. cnn), or sources separated by a comma
And I click on Search
I am redirected to /news
I see a list of the top headlines from those sources
And with each headline I see the author's name
And a short description of the article
And the headline itself is a link to the article.
```

## Story 5

```
When I visit /news/search_source
And I enter an invalid news source
And I click on Search
I see an error message
And the form that I previously submitted is pre-populated with the search I entered.
```

## Story 6

```
When I visit /news/search_category
And I select a category from a dropdown there (e.g. business)
And I click on Search
I am redirected to /news
I see a list of the top headlines in that category
And with each headline I see the author's name
And a short description of the article
And the headline itself is a link to the article.
```
