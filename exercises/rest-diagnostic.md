# REST Diagnostic

This file is a markdown file. Markdown is a special way of formatting text, and one that's used by GitHub in its README files.

### Question 1

In your own words, define what REST is. In your answer, be sure to cite any
relevant sources you consulted in your search.

```md
<!--Rest or Resful is responsible to build an API with a correct or a good architecture -->
```

### Question 2

Imagine you are designing an API that will deal with a resource called
`movies`, what would the appropriate RESTful routes be for sending requests to
that API? Please list the path next to the HTTP verb it would be associated
with.

```md
<!-- INDEX =   GET      Display all the movies               Movie.find()
     NEW =     GET      Display form to add a new movie      
     CREATE=   POST     Add new movies to database           Movie.creat()
     SHOW=     GET      Shows info about one movie           Movie.findById()
     EDIT=     GET      Show edit form for one movie         Movie.findById()
     UPDATE=   PUT      UpDate a particular movie            Movie.findByIdAndUpDate()
     DESTROY=  DELETE   Delete a particular movie            Movie.findByIdAndRemove()

     
     
        -->
```

## Question 3

What are some of the benefits of using an architectural style like REST when
developing an API? When might you NOT want to use the RESTful style?

```md
<!-- When it already has an API, it will break the API and will make it slow  -->
```