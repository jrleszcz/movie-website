A Python module which dynamically generates a [simple website](http://jrleszcz.github.io/movie-website) to display a collection of movies and play their trailers.  Movie data is read from a JSON file and then automatically inserted into the new HTML page.


### Usage

* Input your favorite movies into `favorite_movies.json`.
* `python entertainment_center.py output-page-name.html`


### Requirements

My Movie Library requires Python >2.7 and <3.0.

[Kitchen](https://pythonhosted.org/kitchen/) module (for working with utf-8 encoded strings)


### favorite_movies.json

[favorite_movies.json](favorite_movies.json) contains the data that entertainment_center uses to generate your page. The file is a dictionary of Movie objects:
```
"inside_llewyn_davis": {
        "title":"Inside Llewyn Davis",
        "storyline":"A week in the life of a young singer as he navigates the Greenwich Village folk scene of 1961.",
        "poster_image":"http://upload.wikimedia.org/wikipedia/en/d/df/Inside_Llewyn_Davis_Poster.jpg",
        "trailer_youtube_url":"https://www.youtube.com/watch?v=LFphYRyH7wc"
    }
```