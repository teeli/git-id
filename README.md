# Git identity changer

A very simple bash script to easily change between your work and personal git identities in a repository.

## Configure

Just modify the script with your own identities and save to any directory in your path (e.g. `/usr/bin/local`).

## Usage

`git-id [identity name]`

## Example

To start a new personal project on a computer that globally has your work git credentials:

```
$ git init
Initialized empty Git repository in /Users/teel/Projects/git-id/.git/

$ cd testrepo
$ git-id personal
Changing GIT identity in current repository to personal
Ok
```
