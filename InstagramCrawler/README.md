# InstagramCrawler

* Usage
- Hashtag : set 1 hashtag to crawl.
- DB info : set postgresql db info(id, pw) to store crawled data.

* Prerequisites
- Account info : set Instagram account info(client id, client secret, access token) at input file

* Dependensies
- jInstagram (maven, jar)
- postgresql lib

* Internal structure
- Multi-tasking : to reduce crawling time
- Task scheduling
avoid stop (with query limitation, other errors related with connection, etc)
split works with the other tasks which has completed the job already.

* Future tasks
- Update program
- Sort program by location, etc.