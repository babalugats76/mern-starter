## Deploying to Heroku
- Edit as appropriate the `engines` values in your `package.json`
- Create a Github project for your code, i.e., create a repo, initialize it, etc.
- Check in your code
- Login to Heroku using CLI: `heroku login`
- Create named application using Heroku command-line utility: `heroku create colestock-mern-starter`. Afterwards, you will see it in the Heroku Dashboard. Alternatively, you can use the website GUI.
- Set any needed production configuration values using the Heroku Dashboard. Alternatively, you can do it in the CLI, e.g., `heroku config:set mongoURI=connectstringgoeshere`
- Deploy to Heroku: `git push heroku main`

