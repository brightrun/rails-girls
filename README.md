README
======

This is the rails application from http://guides.railsgirls.com/app.

Testing and Code Profiling
--------------------------

This version is modified with several additional gems for testing, performance,
and code smells.

See [Gemfile](Gemfile) for for the added gems to use.

### Bullet

https://github.com/flyerhzm/bullet

See the [initializer](config/initializers/bullet.rb) for Bullet. This turns on
logging of N+1 queries.

Bullet will automatically turn on for `development` or `test` and produce
`bullet.log` in the logs directory.

###  rack-mini-profiler

https://github.com/MiniProfiler/rack-mini-profiler

`rack-mini-profiler` will add a small javascript display in the top left
while browsing in the app with profile information to view.

### traceroute

https://github.com/amatsuda/traceroute

`traceroute` analyzes routes and controllers for routes with no controller
action and controller actions with no routes.

Use rake to run `traceroute`:

```shell
rake traceroute
```

### rails\_best\_practices

https://github.com/flyerhzm/rails\_best\_practices

`rails_best_practices` points out code that could be refactored to follow
Rails best practices.

Configuration is in
[config/rails_best_practices.yml](config/rails_best_practices.yml).

Run from the root of the project/app:

```shell
rails_best_practices
```

### rubocop

https://github.com/bbatsov/rubocop

`rubocop` provides several different linters to enforce code style

### reek

https://github.com/troessner/reek

`reek` points out code smells that break object-oriented design or lead to
complex, harder to maintain code.

Run from the root of the project:

```shell
reek
```

### flay

https://github.com/seattlerb/flay

`flay` points out similar code and duplicative code that might be better
refactored as a separate method or helper.

Run from the root of the project:

```shell
flay .
```

### flog

https://github.com/seattlerb/flog

`flog` points out complex code that might be better refactored into separate
classes, more methods and utlities, etc.

Run from the root of the project:

```shell
flog .
```

