### Worldpackers Mobile Challenge : )

Your goal is to create a search result screen based on our app layout and API (by this time, you've already downloaded our app, right?)

Get inspired and let's go!
You're allowed to use anything you want to build it. The only requirement is to use Swift and send us a link to your GitHub repository.

##### Endpoint:
* GET https://staging-worldpackersplatform.herokuapp.com/api/search?q=TEXT
  * TEXT is the term searched by the user.
  * Headers:
    * Accept: application/vnd.worldpackers.com.v11+json
    * Authorization: bearer 9e5a86cfca45eba00668e1baf15fd8dd65c15ad760e00845b81995d242844cdd
    * Accept-Language: 'en-US'

#### Bonus points:

* Result pagination (infinite scroll)
* For Android Developers:
  * Using Android Data Binding
