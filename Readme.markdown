# Sam's Tweets

These are all my tweets. See them at [tweets.soff.es](http://tweets.soff.es).

You can also clone the repository and open [index.html](index.html).

In the [data](data) folder, my Twitter archive is present in two formats: JSON and CSV exports by month and year.

* CSV is a generic format that can be imported into many data tools, spreadsheet applications, or consumed simply using a programming language.
* The JSON export contains a full representation of your Tweets as returned by [v1.1 of the Twitter API](https://dev.twitter.com/docs/api/1.1).
* The JSON export is also used to power the [archive browser interface](index.html).
* To consume the export in a generic JSON parser in any language, strip the first and last lines of each file.
