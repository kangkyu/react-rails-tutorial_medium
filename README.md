README
===

Follow rails + react tutorial for server side rendering

+ https://medium.com/@olance/isomorphic-reactjs-app-with-ruby-on-rails-part-1-server-side-rendering-8438bbb1ea1c

```
bundle install
rails server
```
+ [http://localhost:3000?noprerender=1](http://localhost:3000?noprerender=1)
+ [http://localhost:3000?nojs=1&noprerender=1](http://localhost:3000?nojs=1&noprerender=1)
+ [http://localhost:3000?nojs=1](http://localhost:3000?nojs=1)

> the server has done its job rendering it for us before sending the HTML to the browser.

```
cd ~/old_code/isomorphic-reactjs
```
