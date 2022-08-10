# Ruby on Rails Community Chat Application

This is the application is inspired by the 
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/) to create a Twitter-Style app for people to chat about issues 
affecting them in their community.


## Getting started

To get started with the app, clone the repo and then install the needed gems:

```
$ gem install bundler -v 2.3.14
$ bundle _2.3.14_ config set --local without 'production'
$ bundle _2.3.14_ install
```

Next, migrate the database:

```
$ rails db:migrate
```

Finally, run the test suite to verify that everything is working correctly:

```
$ rails test
```

If the test suite passes, you'll be ready to run the app in a local server:

```
$ rails server
```

## License

All source code is available jointly under the MIT License and the Beerware License. See
[LICENSE.md](LICENSE.md) for details.

For more information, see the
[*Ruby on Rails Tutorial* book](https://www.railstutorial.org/book).