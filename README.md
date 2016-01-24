# go-appengine-example
Example of how to set up an appengine project

# Directory structure

Some of the examples in the documentation are out of date, when you see ```import "appengine"``` you know that it is out of date.

Instead, you should be importing from ```import "google.golang.org/appengine"```

    tree -L 3

    .
    ├── LICENSE
    ├── README.md
    └── src
        ├── dherbst
        │   ├── app.yaml
        │   ├── handlers.go
        │   ├── handlers_test.go
        │   └── web
        │        └── index.html
        ├── golang.org
        │   └── x
        └── google.golang.org
            └── appengine

# Setting your GOPATH
I like to set the GOTPATH to the project root directory

    cd myproject
    export GOPATH=`pwd`

# slides

https://go-talks.appspot.com/github.com/dherbst/go-appengine-example/doc/go-appengine-example.slide
