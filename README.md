# hng_dragonglass_ui

Frontend Work for team_dragon_glass HNG Internship 5.

---

## Contributing

- Fork the repository
- Clone your forked copy using

```
git clone https://github.com<your_username>/hng_dragonglass_ui.git
```

- Change into the `hng` subfolder

```
cd hng_dragonglass_ui/hng/
```

- Start the local server by running

```
php -S localhost:8000
```

- Visit localhost:8000 in your browser

### Making changes

- First set the original repo as your upstream remote. This will allow
  you to easily pull updates from the original repo. Run

```
git remote add upstream https://github.com/dragonglass-fe/hng_dragonglass_ui.git
```

- Next, use the `develop` branch. Run `git branch` to see the branch
  you are in. If there is no asterisk next to `develop`, then run

```
git checkout develop
```

- Create a new php file if you're working on a new page, or open an existing php page file to make updates
  (Note: Observe file structure and patterns, include head/nav.php where necessary)
- Use git status to check modifications
- Stage and commit the files modified by running

```
git add <filename>
git commit -m "Commit message"
```

### Pushing changes

- When ready to push your changes to GitHub, first ensure that there
  are no conflicts with the original repo. Run

```
git pull upstream develop
```

- If there are merge conflicts, please resolve them, ensuring not to
  overwrite the work that came from the repo (unless that's the change
  you are making).

- After resolving any conflicts, push your changes to your forked repo by running either

```
git push -u origin develop // first time you're pushing to the repo
```

or

```
git push // you've already previously done git push -u origin develop
```

### Making Pull Requests

- Follow the steps in the [Making changes](#making-changes) section
  to make changes, and in the [Pushing changes](#pushing-changes) section
  to push them to your forked repo.
- Go to https://github.com/dragonglass-fe/hng_dragonglass_ui/pulls
- Select new request.
- Choose compare across forks.
- Choose base repository as **develop** and choose head repository as
  **develop** of your forked copy
- Create pull request. Please ensure that you do this only after
  resolving any merge conflicts. See the [Pushing changes](#pushing-changes)
  section for instructions.

---
