# URL-Shortener

URL Shortener with multiple features 

## Features:

🎈 With Short URLs you can save the description of the URL in form of Notes

🎈 Added a clicks count (for each Short URL) tracker to keep track of the number of times people access any website using a short link created by the project website.

🎈 Kept a table on the home page with a list of all the URLs made so far.




## Tech Stacks

🦕 **Client:** HTML, CSS, Bootstrap, JS, EJS

🦕 **Server:** Node, Express

🦕 **Database:** MongoDB

## Run Locally

Go to project directory

```bash
  cd URL Shortner
```

Clone the project

```bash
  git clone https://github.com/Ukriyte/URL-Shortner.git
```

Initialize package.json

```bash
  npm init -y
```

Install dependencies

```bash
  npm i mongoose express shortid ejs
```

Install node and mongodb compass on your device locally and add the path of there respective bin files to your device environment variables.
Note: Your mongodb application should be running in the background.

Edit the following code present in the beginning of server.js file and put the mongodb host url shown in mongodb compass

```bash
  //Mongo db connection
mongoose.connect('mongodb://127.0.0.1:27017', {
    useNewUrlParser: true, useUnifiedTopology: true
})

```
Start the server

```bash
  node .\server.js
```

Search the following in the browser and URL shortner will open up

```bash
  http://localhost:5000
```
```
## Resources used:

### Youtube Tutorials:

https://www.youtube.com/watch?v=oSIv-E60NiU&ab_channel=CodeWithHarry

https://www.youtube.com/watch?v=SccSCuHhOw0&ab_channel=WebDevSimplified

https://www.youtube.com/watch?v=XlvsJLer_No&list=PLZlA0Gpn_vH8jbFkBjOuFjhxANC63OmXM&ab_channel=WebDevSimplified

https://www.youtube.com/watch?v=IqpfBGsALqc&list=PL7sCSgsRZ-slYARh3YJIqPGZqtGVqZRGt&ab_channel=WalkThroughCode

### Documetations:

https://mongoosejs.com/docs/index.html

https://getbootstrap.com/docs/5.3/getting-started/introduction/

## Key Takeaways:

💫 The URL shortener project allowed for the practical application of full-stack development, integrating frontend (HTML, CSS, Bootstrap, EJS) and backend (Node.js, Express, MongoDB) technologies.

💫 Learning outcomes included integrating MongoDB for database functionality, and exploring URL shortening techniques, search functionality, and user interface design.

💫 The project emphasized error handling, documentation, project organization, and provided opportunities for continuous improvement and future enhancements.

## THANK YOU✌️.

