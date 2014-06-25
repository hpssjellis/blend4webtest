

$ git init

$ git remote add origin https://github.com/hpssjellis/blend4webtest.git


# update public key


git remote -v

# Verify new remote
# origin  https://github.com/user/repo.git (fetch)
# origin  https://github.com/user/repo.git (push)

git config user.name "jerteach"
git config user.email "jellis@hpssapps.com"

git add .
git commit -m "initial commit"
git push origin master

# will ask for github suername then password




To create a new Heroku project and push the remote to your project:

heroku create

git remote -v
# Verify new remote (you will see heroku and origin now
# heroku     git@heroku.com:falling-wind-1624.git (fetch)
# heroku     git@heroku.com:falling-wind-1624.git (push)
# origin  https://github.com/user/repo.git (fetch)
# origin  https://github.com/user/repo.git (push)

git push heroku master
# will ask for github suername then password

