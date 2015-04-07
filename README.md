WTF
---------------
An empty starting point for a stateless Ruby API using the rails-api gem, with a React client side app. To fit the definition of stateless, the API does not include action-view, sprockets, or sessions. Roughly speaking, React replaces action-view, Webpack replaces sprockets, and JWT replaces sessions.

Installation
---------------
There's a detailed tutorial on how to build this project at: http://fredguest.com/2015/03/06/building-a-stateless-rails-api-with-react-and-twitter-oauth/

Demo
---------------
There's a live demo of the finished project at: https://blabs.herokuapp.com

Installing your PostgreSQL
---------------
* Install using homebrew
```bash
$ brew install postgresql
```
* If this your first time installing PostGres with Homebrew, you may need to run this
```bash
$ initdb /usr/local/var/postgres -E utf8
```
* Run this command below (change [POSTGRE_VERSION] with your postgre version)
```bash
$ mkdir -p ~/Library/LaunchAgents
$ cp /usr/local/Cellar/postgresql/[POSTGRE_VERSION]/homebrew.mxcl.postgresql.plist ~/Library/LaunchAgents/
```
* Install lunchy
```bash
$ gem install lunchy
```
* Finally start/stop PostgreSql
```bash
$ lunchy start postgres
$ lunchy stop postgres
```
