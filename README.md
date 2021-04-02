# Show and Tell

Now that you have a [Dotfiles repository](https://github.com/eieioxyz/dotfiles_macos), it's time to join the community with a little [Show and Tell](https://en.wikipedia.org/wiki/Show_and_tell_(education)). Follow the instructions below to [*show* us your repo and *tell* us a bit more about yourself](ROLL-CALL.md).

To see when other students add their repos, choose **All Activity** from the **Watch / Unwatch** dropdown above. You'll learn even more if you click through to a few other student's repos and watch their changes as well.

## Instructions

The three sections below will have corresponding videos in [the course](http://dotfiles.eieio.xyz/ "Dotfiles from Start to Finish-ish"). Until those are published, you can [preview the lessons on YouTube](https://youtu.be/9LsQboYpvYI).

### Add yourself and create a pull request

1. Navigate to [ROLL-CALL.md](ROLL-CALL.md).
2. Click the pencil icon to **Fork this project and edit this file**.
3. Add yourself to the list by linking to your Dotfiles repo and by telling us a little about yourself.
4. **Preview Changes** to make sure you like how it looks.
5. Under **Propose Changes**, add a message that says `Add <Your Username>`. This is equivalent to a commit message for this change.
6. Also under **Propose Changes**, if you'd like me to submit a pull request to your repository please say so in the description. This is part of a learning exercise covered in the [third set of instructions below](#accept-pull-request-and-resolve-merge-conflict).
7. Click **Propose Changes**.
8. After "comparing changes," click **Create pull request**.
9. Before opening the pull request, review the [Contribution Guidelines](CONTRIBUTING.md).
10. While there's no need to change the title or description, you might want to adjust these just to see the difference between the *Pull Request Message* and the original *Commit Message*.
11. Click **Create pull request** *again* to open the pull request.

### Update and then delete your fork

1. Wait for me to merge your pull request and then revisit its page.
2. **Delete your branch**, but don't delete your fork yet.
3. Navigate to the home of *my repository*. Consider watching this repository as well as a few repos of your classmates.
4. Navigate to the home of *your fork*. Your master will be behind the master on eieioxyz, so try to create a new **Pull request**.
5. **Switch the base** to pull in the opposite direction. Since your repo is now the base, you'll be able to complete the merge on your own.
6. Click **Create pull request**.
7. Since this feels like [Deja Vu](https://youtu.be/XfEuxRDYiyc), you may want to change the title and description of the pull request to help everything make sense.
8. Click **Create pull request**, *again*.
9. Under **Merge pull request**, choose **Create a merge commit**. Later you'll see why you might prefer **Rebase and merge** instead.
10. After clicking **Merge pull request** you'll be asked to enter commit information for the merge. Change the description to your liking or accept the default.
11. **Confirm merge** to add the merge commit.
12. Navigate to your fork's home page. You are ahead of master because of the merge commit. This is one reason you might want to favor the **Rebase and merge** option.
13. Navigate to the commit history of your fork. If you consider the merge commit superfluous, this is another reason **Rebase and merge** could be a better option.
14. Navigate to the **Settings** of your fork, scroll to the bottom, and **Delete this repository**.

### Accept pull request and resolve merge conflict

This part assumes you requested a PR. Additionally, I can't cover every scenario in Git. We will resolve a simple conflict from your remote to local master. You are likely to be working with branches, in which case merging will be a bit different, and you'll be on your own to figure that out ([you can do it!](https://youtu.be/VZ2HcRl4wSk)).

1. Wait for me create a pull request in your Dotfiles repository.
2. Navigate to my pull request within your repo.
3. Open the **Files changed** tab and inspect the changes.
4. Click **Review changes**, write a comment, and approve the changes. Your comment will appear in the PR conversation.
5. This time, choose **Rebase and merge** and then confirm the rebase and merge.
6. Navigate to the commit history and note there's no extra merge commit.
7. In your Terminal App, make an intentional conflict with the TODO I added and commit the change.
8. Attempt a `git push`.
9. Get the remote changes with `git pull`.
10. Open and edit the file to resolve the conflict.
11. Add, commit, and push your changes.

## What is this?

This repository is part of the course [Dotfiles from Start to Finish-ish](http://dotfiles.eieio.xyz/) where you'll learn about the command line, Homebrew, zsh, git, macOS, and more, while you create a [Dotfiles repo](https://github.com/eieioxyz/dotfiles_macos).

For a primer on Dotfiles, watch [***~/.dotfiles in 100 Seconds***](https://youtu.be/r_MpUP6aKiQ) and check out the [corresponding repository](https://github.com/eieioxyz/Beyond-Dotfiles-in-100-Seconds).

Keep an eye on [Twitter](https://twitter.com/EIEIOxyz "Follow @EIEIOxyz on Twitter") and [YouTube](https://www.youtube.com/channel/UCcZZOzRKMbql7IEL0midfgQ "Subscribe to EIEIO on YouTube") for updates to the course.
