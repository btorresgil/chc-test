# Contributing guidelines

Contributions to this project are very welcome!

Use these steps to create a pull request on this project:

Step 1: Fork this repo

In GitHub, click the fork button in the top right of this repo to fork it into your own personal account.

Step 2: Clone your fork

```
git clone [your-forked-repo-url]
cd [directory]
```

Step 3: Add the upstream repo

This is how you'll get upstream changes and keep your fork in-sync.

```
git remote add upstream [original-repo-url]
```

Step 4: Create a branch

This is where all your changes will go

```
git checkout -b feature/my-feature-name
```

Step 5: Make your changes

We recommend [VSCode](https://code.visualstudio.com/) for TypeScript projects. It's free!

Format and build your work and run it to make sure it works.

```
npm run build
npm run start
```

Step 6: Test your work

Run the test suite to ensure nothing broke. Make sure you add tests for anything you created.

```
npm run test
```

Step 7: Save your changes to git

```
git add -A
git commit -m "Description of the changes"
```

This will also format your code according to our code style.
You can do this multiple times to save several changes.

Step 8: Push to your fork

This uploads your changes to your personal fork in the branch you created.

```
git push -u origin feature/my-feature-name
```

Step 9: Create a pull request

In GitHub, navigate to your fork and you should see an alert that a new branch was created. There is a button to create a pull request. Click it and give the PR a good description so we can review and merge it!

Thanks for your help!
