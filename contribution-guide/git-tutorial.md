## Git tutorial

We're following basic GitHub Flow. If you have ever contributed to an open source project on GitHub, you probably know it already - if you have no idea what we're talking about, check out [GitHub's official guide](https://guides.github.com/introduction/flow/). Here's a quick summary:

+ Fork the repository and clone to your local machine
+ You should already be on the default branch `master` - if not, check it out (`git checkout master`)
+ Create a new branch for your template (`git checkout -b my-new-template)
+ Write your template
+ Stage the changed files for a commit (`git add .`)
+ Commit your files with a useful commit message ([example](https://github.com/Azure/azure-quickstart-templates/commit/53699fed9983d4adead63d9182566dec4b8430d4)) (`git commit`)
+ Push your new branch to your GitHub Fork (`git push origin my-new-template`)
+ Visit this repository in GitHub and create a Pull Request.

