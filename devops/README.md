# update version

example of fetching tags from upstream:

- Repo: someuser/myframework
- Fork: superteam/myframework

Track:

```bash
git clone https://github.com/superteam/myframework.git
cd myframework
git remote add upstream https://github.com/someuser/myframework.git
```

Update:

```bash
git fetch upstream
git rebase upstream/master
git push
git push --tags
```
