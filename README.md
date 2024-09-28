# gitExperiment
This repository is for experimenting with workflows for git
Its companion fork on sourceforge is callahanpa/gitExperiment

We're going to try the following:

clone git@github.com:callahanp/gitExperiment.git

    git remote remove origin
    git remote add origin ssh://callahanpa@git.code.sf.net/p/callahanpa/gitExperiment
    git config branch.next.remote origin
    git config branch.next.merge refs/heads/master
    git remote add upstream git@github.com:callahanp/gitExperiment.git
