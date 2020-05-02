# Chuck Norris Jokes

* [Documentation](https://api.chucknorris.io/)

# Stories

## Story 1

```
When I visit /chuck,
I see a random Chuck Norris fact.
```

## Story 2

```
When I visit /chuck/search,
And I fill in the Search Term with a word (e.g. 'cheetah'),
And I click 'Search',
I see a list of Chuck Norris facts with the search terms included.
```

## Story 3

```
When I visit /chuck/category_search,
And I select a category (e.g. food) from a dropdown
And I click 'Search',
I see a list of up to 10 Chuck Norris facts in the selected category.
```

Note: the categories should match the available categories from the Chuck Norris Jokes API and should not be hard coded into your application.

## Story 4 (extension)

Pagination

```
Given a category has more than 10 Chuck Norris facts,
When I visit /chuck/category_search,
And I select a category (e.g. food) from a dropdown
And I click 'Search',
And I click on a link '2',
I am taken to a second page of facts
```

Note: the number of numbered links is enough that I can see all of the facts in the category in slices of 10.

