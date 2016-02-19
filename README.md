## Haskell GridFS

[GridFS](https://docs.mongodb.org/manual/core/gridfs/) is a convention for
storing large files in [MongoDB](https://www.mongodb.org/).

Most drivers from the MongoDB team include GridFS support.  The [Haskell
driver](https://github.com/mongodb-haskell/mongodb) does not.

This driver was initially provided as an attachment by Martin Norbäck Olivers at
https://jira.mongodb.org/browse/HASKELL-14.  The maintainers at MongoDB haven't
acted on it or provided their own GridFS implementation, so I'm packaging it as
a standalone library and putting it on Hackage to make it easier to use.
