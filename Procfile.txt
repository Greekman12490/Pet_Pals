$ heroku ps:scale web=1

web: gunicorn pet_pals.app:app
