## java-restaurant-menu-review
Solution for Java Unit studios 4.8 and 5.6

If you forked and cloned this repo to your local machine before I added all branches, you can set `upstream` to point to my original repo like this:

```
> git remote add upstream https://github.com/Carolista/java-restaurant-menu-review
```

After that, anytime you need your local machine to have knowledge of any new branches I may have added, run this command:

```
> git fetch upstream
```

To view all available branches:

```
> git branch -r
```

Then use `git checkout some-branch-name` as usual to create a local copy of the desired branch.

If I added new content to an existing branch and you want to merge it in, from some-branch-name:

```
git merge upstream/some-branch-name
```
