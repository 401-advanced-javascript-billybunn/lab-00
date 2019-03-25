![CF](http://i.imgur.com/7v5ASc8.png) LAB
=================================================

<!-- LINKS -->
<!-- Replace the link for each in brackets below -->
<!-- PR (working into submission) -->
[1]: https://github.com/401-advanced-javascript-billybunn/lab-00/pull/1
<!-- travis build -->
[2]: https://travis-ci.com/401-advanced-javascript-billybunn/lab-00/builds/105609572
<!-- back-end -->
[3]: https://billybunn-401-lab-00.herokuapp.com/
<!-- front-end -->
[4]: https://billybunn-401-lab-00.herokuapp.com/
<!-- swagger -->
[5]: http://xyz.com
<!-- jsdoc-->
[6]: heroku-link/docs 

## Lab: Deployment Workshop

### Author: Billy Bunn

### Links and Resources
* [PR][1]
* [travis][2]
<!-- (when applicable) -->
* [back-end][3]

## Requirements

### Get this code up and running Travis and Heroku!

- Create a git repo (fork this one) - **[Repo link](https://github.com/401-advanced-javascript-billybunn/lab-00)**

- Create a branch rule disallowing merges to master unless Travis builds are green. - **see image**

![Imgur](https://i.imgur.com/LfRtBCP.png)

- Connect Travis to your git account - **see image**
  - It should find this repo

![Imgur](https://i.imgur.com/S2q7ukF.png)

- Connect your Heroku to your git repo - **see image**
  - Set it to auto deploy from master (or any named branch)
  - Optionally, set it to require CI (this will cause Heroku not to deploy without a passing travis build)

![Imgur](https://i.imgur.com/jsPudij.png)

<!-- (when applicable) -->
<!-- * [front-end][4] -->

<!-- #### Documentation -->
<!-- API assignments only -->
<!-- * [swagger][5] -->
<!-- (All assignments) -->
<!-- * [jsdoc][6] -->

<!-- ### Modules
#### `modulename.js`
##### Exported Values and Methods

###### `foo(thing) -> string`
Usage Notes or examples

###### `bar(array) -> array`
Usage Notes or examples

### Setup
#### `.env` requirements
* `npm i`
* `PORT` - assign a port number
* `MONGODB_URI` - URL to the running mongo instance/db


#### Running the app
* `npm start`
* Endpoint: `/`
* Endpoint: `/foo/bar/`
  * Returns a JSON object with abc in it.
* Endpoint: `/bing/zing/`
  * Returns a JSON object with xyz in it.
  
#### Tests
* How do you run tests?
  * `npm run test`
  * `npm run lint`
* What assertions were made?
* What assertions need to be / should be made?

#### UML
Link to an image of the UML for your application and response to events -->
