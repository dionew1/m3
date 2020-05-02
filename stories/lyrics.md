# Lyrics OVH

* [Documentation](https://lyricsovh.docs.apiary.io/#)

# Stories

## Story 1

```
When I visit /lyrics/search
And I fill in Artist with an artist name (e.g. The Beatles)
And I fill in Song with a song name (e.g. Hey Jude)
And I click on 'Search'
I see a page with the Artist Name, the Song Name, and the Lyrics to that Song on it.
```

## Story 2

```
When I visit /lyrics/search
And I fill in Artist with a misspelled artist name (e.g. Nirvona)
And I fill in Song with a song name (e.g. Smells Like Teen Spirit)
And I click on 'Search'
I see a message saying that no lyrics were found
And I see the form to search for lyrics pre-populated with the Artist Name and Song Name that I previously submitted.
```

## Story 3

```
When I visit /lyrics/search
And I fill in Artist with an Artist Name (e.g. Nirvana)
And I fill in Song with a song name that has no lyrics in the API (e.g. Teen Spirit)
And I click on 'Search'
I see a message saying that no lyrics were found
And I see the form to search for lyrics pre-populated with the Artist Name and Song Name that I previously submitted.
```

