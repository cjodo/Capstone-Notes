# Collaboration Workflow

- We will use the official method provided by github: [Github Flow](https://docs.github.com/en/get-started/using-github/github-flow) 

You can use either the github CLI or Github Desktop, the methodology won't change

1. All work will be done in seperate feature branches.  Never on the main branch.  This is to keep work seperate and to minimize conflict in production.
2. After the changes are made, and pushed to your branch, a pull request should be opened. This can be done on github.
3. After a pull request is opened, a code review will happen, any changes needed to be done will be written in the comments.
4. After all fixes are done, the feature will be merged into the main branch.

    These are the steps needed to do this effectively.

    1. Clone the repo with `git clone <url>`
    2. Checkout a new branch off main: `$ git checkout -b my-feature`
    3. Commit as frequently as you can - this usually is after every change you make. Make sure commit messages are meaningful and descriptive.
        - For example: "add helper function to extract price from product" or "fix typo"
        - Never have a commit message that just says "some updates"
    4. Push code to your branch: `$ git push origin my-feature`
    5. Then the code review process will start.
    6. Finally the code is merged into main and the changes should be live in production

### Final step after all work is done is to delete your branch.
