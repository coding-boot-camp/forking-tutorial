# forking-tutorial🍴
This repo is used as a demo for the in-class git fork guide

## About forks
Forking a repository makes an exact copy another project that resides on your personal account. This acts as a connection between your own repo and the owner's repo. Additionally, this allows the owner to protect their own code by preventing users from pushing to it directly but still giving developers a way to contribute in a non-intrusive way. Forking is very common in open-source software development.

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