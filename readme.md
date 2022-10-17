https://www.youtube.com/watch?v=dVEjSmKFUVI&ab_channel=JulianNash

Tutorial notes

- uwsgi is Linux only and can't be installed on Windows you can manually add it to the requirements.txt file and it will be installed in the Docker container
- you won't be able to run the app locally with uwsgi, you can only run it in the Docker container
- but, you can run the flask app in the flask app folder with `flask run` and it will run on port 5000
- 