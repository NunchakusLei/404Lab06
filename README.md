# 404Lab06
Course work for CMPUT 404 - Web Applications and Architect (Winter 2017), Lab 06 @ University of Alberta, Canada 

# Heroku Note
## 1. Login to Your Heroku Account:
```
heroku
```

You might need to use the follow command if your computer says heroku command not found.
```
export PATH="$PATH:$PWD/heroku/bin"
```

## 2. Run local web
```
cd <your project root>
heroku local web
```

## 3. Deployed to Heroku server
```
git push heroku master
```

## 4. Run command on Heroku
For example,
```
heroku run python manage.py migrate
```

