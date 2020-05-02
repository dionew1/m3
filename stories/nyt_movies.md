# NYT Movie Reviews

* [Documentation](https://developer.nytimes.com/)

# Stories

## Story 1

```
When I visit /movies/reviewer_search
And I select the name of a movie reviewer from a dropdown
And I click on Find Reviews
I see a list of movie reviews from that reviewer
And the reviews are split into two sections: Critics Picks, and Duds
And each review includes a headline, the name of the reviewer, the date of the review, the rating of the movie, and a short summary of film,
And the headline is a link to the full review.
```

Note: this list does not necessarily need to include every review from this author.

## Story 2

```
When I visit /movies/title_search
And I enter a search term in a Title input
And I click on Find Reviews
I see a list of movie reviews with the term I entered in the title
And the reviews are split into two sections: Critics Picks, and Duds
And each review includes a headline, the name of the reviewer, the date of the review, the rating of the movie, and a short summary of film,
And the headline is a link to the full review.
```

## Story 3

```
When I visit /movies/title_search
And I enter a search term in a Title input
And I select a decade from the dropdown (e.g. 1980's)
And I click on Find Reviews
I see a list of movie reviews with the term I entered in the title who opened in the decade that I selected on the previous page
And the reviews are split into two sections: Critics Picks, and Duds
And each review includes a headline, the name of the reviewer, the date of the review, the rating of the movie, and a short summary of film,
And the headline is a link to the full review.
```


