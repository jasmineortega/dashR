# dashR
Link to dashboard plot: 
https://jasmine-532r.herokuapp.com/

Ty Doris for instructions :heart:

1. Clone Joel's repo and copy over all files: https://github.com/UBC-MDS/dashr-heroku-deployment-demo
2. Make sure your app.R uses old pipes and the last line should be app$run_server(host = '0.0.0.0')
3. Add all packages to init.R
4. In terminal, navigate to your repo:

```bash
# login to Heroku
heroku login

git init

heroku create --stack container your-heroku-site-name

git push heroku main

```

Wait 15 minutes for ur fate to be decided
