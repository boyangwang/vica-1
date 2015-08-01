vica
========

> This README would normally document whatever steps are necessary to get the
application up and running.

## Getting Started

Have **Ruby >= 2.2.0** and **Rails 4.2.3** installed. Have [Postgres](postgresapp.com) running.

Fork this project, and do a `git clone` from your fork.

```
cd vica
bundle
rake db:create
rails s
```


## Development Guidelines

Here is our development worflow, roughly based [Github Flow](https://guides.github.com/introduction/flow/) and this [branching model](http://nvie.com/posts/a-successful-git-branching-model/):

1. Pick up a Trello card (assign yourself to the card)
2. Create a feature branch <u>**in your own fork**</u> from `dev` branch
3. Write Code + accompanying Tests
4. Make a Pull Request from your branch to `dev` branch
5. Discuss and review your code with at least 1 other person
6. Make changes based on reviews
7. Reviewers merge once reviews are done
8. Changes are merged to `dev`

## Deployment Guidelines

We're hosted on [Heroku](https://devcenter.heroku.com/articles/getting-started-with-rails4). To deploy yourself, you'll have to install the Heroku toolbelt and be a collaborator to the Heroku project.

We deploy multiple times a day from `master` or `release-x.x.x` branches.