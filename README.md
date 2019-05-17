# How To Run This #
1. Spin up your virtual environment
2. Obtain OAuth Credentials from [Google's API Console](https://github.com/jaredasch/OAuth-SQLAlchemy-Demo.git) and add them to the config file
3. Install all of the dependencies in requirements.txt
4. Run the terminal command `export OAUTHLIB_INSECURE_TRANSPORT=1`, which allows OAuth to work over an insecure connection to localhost
5. Run `flask db init`, then `flask db migrate`, then `flask db upgrade`
6. Run the terminal command `export FLASK_APP=run.py`
7. Run `flask run` to start your app on localhost