What is the difference between Git and GitHub?
Git is everything we’ve covered so far: a source code management tool, that comes with a command-line tool for its users.

GitHub is one of many services that provide at the same time:

a Git repository server to push your code to
a web UI to that view your repositories, with their files and commits
a number of extra features (managing your team and accesses, …) Two GitHub features you have to get familiarized with are:

Forks : you can fork any repository on GitHub, and it will duplicate the repository’s codebase into repository that you own. For instance, if you fork twbs/bootstrap, and your GitHub username is “my_username”, then it will create the my_username/bootstrap repository, and it will remember where it was forked from. Usually, you aren’t allowed to push on other people’s repositories, so that will give you a repository that you can push to, since you own it.

Pull requests: once you’ve pushed your code to your repository (or sometimes to a branch of the main repository, if you’re allowed), then you can create a pull request towards the main repository’s master branch. Somebody in charge of the main repository will review your pull request (potentially asking you to change a couple of things), and merge it if it’s suitable to be in the main product.

GitHub has many competitors, two of the main ones being GitLab and BitBucket (which provide very similar services). At Holberton School, we chose to make you use GitHub because that’s where most of the industry is (that way, you’ll be able to interact with them on their open-source projects), and it’s also where tech recruiters typically go check out to see what you’ve been up to.