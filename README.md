# Jekyll-Intro
 An introduction to the Jekyll static site generator.

 ## If you are Elias

```sh
git add .
git commit -m "pls work"
git push
```

## Installation

Jekyll is a Ruby gem. With Ruby installed, install Jekyll from the terminal:

```sh
gem install jekyll bundler
```

Create a new `Gemfile` to list your project's dependencies:

```sh
bundle init
```

Edit the `Gemfile` in a text editor and add jekyll as a dependency:

```ruby
gem "jekyll"
```

Run `bundle` to install jekyll for your project.

You can now prefix all jekyll commands listed in this tutorial with `bundle exec`
to make sure you use the jekyll version defined in your `Gemfile`.

Remove this line.