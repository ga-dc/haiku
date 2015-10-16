# haiku
An exercise in forking and creating a pull requests.

## Learning Objectives
- Practice using the 'fork, clone, and pull request' model to submit assignments

## Instructions
You do not have the necessary rights to update this repository.  Therefore, you must fork it, make changes to your fork, and then send a pull request to the owners of this repository.

On https://github.com/ga-dc/haiku:

1. Fork this repo to your personal account.
2. Copy the "HTTPS clone URL" for your fork of this repo.

Starting in ~/wdi/exercises:

1. Clone the repository to your computer (make sure to use the url for your fork, and *not* this original repo), e.g. `git clone https://github.com/adambray/haiku.git`.  Note: The `git clone` command will create a new "haiku" dir and copy the repo into it.
2. Change to the newly create "haiku" dir (`cd haiku`).
3. You can see that the clone command has already setup your origin (`git remote -v`).
4. Open the current directory in your text editor (`atom .`).
5. Create a text file named `your_gh_username.txt`, e.g. `adambray.txt`.
6. Write a haiku on a topic of your choice, commit it, and push (sync) it to your remote.
7. You should see this commit on your forked repo on github.

Create a Pull Request:

1. Back on github.com (on your forked repo), create a pull request to the upstream (original) repository: `ga-dc/haiku master <- your_github_name/haiku master`.

Additional changes are added to the Pull Request:

1. Make additional local changes, and commit/push them to your remote.
2. Verify that the pull request is updated on github.
