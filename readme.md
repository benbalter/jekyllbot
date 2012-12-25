JekyllBot
=========

Listens for GitHub post-recieve service hooks messages, runs jekyll, and pushes the results back to GitHub. Designed to be run on Heroku to generate JSON representations of postdata for ben.balter.com.

Usage
-----

1. `git clone`
2. `heroku create`
3. Add resulting URL to Repo's settings
4. `heroku config::set GH_USER=YOUR_GITHUB_USER_NAME GH_PASS=YOUR_PASSWORD

Will automatically fire on each commit
