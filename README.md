# fragments-ui
web app to manage authentication with User Pool and test back-end fragments microservice
will need sign-up & sign in before testing requests.

Choose the type of fragment you wish to `POST` first.

`GET FRAGMENT` will return a list of fragment ids belongs to the logged in user in the console.

`GET FRAGMENT EXPAND` will return a list fragment's metadata belongs to the logged in user in the console.

`GET DATA` will return the fragments data in the console with respect to the fragment id provided.

`GET DATA INFO` will return the fragments metadata in the console with respect to the fragment id provided.


`GET DATA` allows user to convert fragment's data from `text/markdown` to `text/html` by adding `.ext` at the end of the id.

More conversions of fragments are still under development..