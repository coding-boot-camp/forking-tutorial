# forking-tutorial🍴
This repo is used as a demo for the in-class git fork guide

## About forks
Forking a repository makes an exact copy another project that resides on your personal account. This acts as a connection between your own repo and the owner's repo. Additionally, this allows the owner to protect their own code by preventing users from pushing to it directly but still giving developers a way to contribute in a non-intrusive way. Forking is very common in open-source software development.

# Git Fork

Now that you have become familiar with Git and Github, you may find yourself wanting to contribute to an open source project. You may also want to use a project as a starting point for your own, in the case of something like a boilerplate application. Luckily, there is a feature in Github and many other version control systems called forking.

Forking a repository makes an exact copy another project that resides on your personal account. This acts as a connection between your own repo and the owner's repo. Additionally, this allows the owner to protect their own code by preventing users from pushing to it directly but still giving developers a way to contribute in a non-intrusive way. Forking is very common in open-source software development.

In this activity we will be using a test repository to help you grasp the fork and pull request workflow

* Getting started: visit [forking-tutorial](https://github.com/coding-boot-camp/forking-tutorial)

## Fork and Clone

1. To fork this project, click the "fork" button at the top of the repository

2. Choose your personal account when asked `Where should we fork?"

3. After a few seconds you will be taken to *your* copy of the repository

4. Visit the fork that you just created on GitHub can copy the URL of your fork.

5. Clone your fork of the repository to your local machine and move into that directory:

    ```sh
    git clone git@github.com:<YOUR_GITHUB_USERNAME>/forking-tutorial.git && cd forking-tutorial
    ```

6. Run the following command to see that the remote URL for the repository is set to your own personal Github

    ```sh
    git remote -v
    ```

## Contribute and Pull Request

1. Create a branch of your own

    ```sh
    git checkout -b <branch name>
    ```

2. Make some additions or changes to the readme file and stage and commit your work.

    ```sh
    git add readme.md
    git commit -m "make it better"
    ```

3. Push your changes to the remote branch

    ```sh
    git push origin <branch name>
    ```

4. Back on the forked repository page, you should see a yellow bar at the top with a button to "Compare and Pull Request". Click that button.

   * After clicking that button, take some time to enter in a good description to help the owner of the project decide what it is we are trying to contribute.

   * We will see a list of commit messages and that our branch is "ahead" of the master branch.

5. Click "Create Pull Request". The owner of the project will get an email notification that some changes have been made and that a pull request is ready for their review.

   * The owner can approve or reject the pull request and optionally add some additional comments for your review. While this is a simple edit we are making to the `readme.md` file, you can imagine a situation where your code would require some additional review.

## Review

You have successfully created your own fork, cloned it to your local machine, made some changes and created a pull request to the owner's repository. This is a workflow that you will become familiar with as you get deeper into your experience as a software engineer. It may seem a little confusing at first, but now you can move forward with confidence knowing that you have forked and contributed to a repository yourself.
