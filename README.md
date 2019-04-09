# Android_Projects_2019
Android Assignment Alpha data, New York Times Application

app to hit the NY Times Most Popular Articles API and show a list of articles,
that shows details when items on the list are tapped (a typical master/detail app).
We'll be using the most viewed section of this API.

http://api.nytimes.com/svc/mostpopular/v2/mostviewed/{section}/{period}.json?api-
key=sample-key

To test this API, you can use all-sections for the section path component in the URL above
and 7 for period (available period values are 1, 7 and 30, which represents how far back, in
days, the API returns results for).

http://api.nytimes.com/svc/mostpopular/v2/mostviewed/all-sections/7.json?api-
key=sybDZly7rUqL8GuOtTFGBKNmcihhCQEX

--You can find base URL in gradle file
--Get service communication.NetworkService.class
