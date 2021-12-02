# favicon-crawler
Favicon crowler for backend tipping in aeternity superhero. A nodeJS webservice fetching icon from websites.



This webservice is using an optional cache system with [redis](http://redis.io). A seven day cache is used before refreshing the cache icon.

## usage
You need to install [Node](http://nodejs.org/) and [Grunt](http://gruntjs.com/) in order to download dependencies and run the server via the command line.
Optionnaly [redis](http://redis.io) is used to cache icons from domains.

1. Fork and clone the repo
2. `cd` into the `favicon-crawler` folder
3. run `yarn install` to install dependencies
3. start your local redis datastore
4. run  `yarn grunt` to run the server
5. run `curl htpp://127.0.0.1:3031/get?domain=google.com`

## Requirements
to run the command line tools
* [Node](http://nodejs.org/)
* [Grunt](http://gruntjs.com/)

## Credits
* default Icons are coming from [iconfinder](https://www.iconfinder.com/Vecteezy) by [Vecteezy](http://www.vecteezy.com/free-vector/icons)

