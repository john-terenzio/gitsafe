gitsafe
-------

gitsafe wraps the `git` command in an effort to stop bad behavior, namely force pushing to branches named "master" or "production". It will issue a warning if it sees this happen. Otherwise it will stay out of your way. Pull requests welcome.

![gitsafe in action](https://raw.github.com/jterenzio/gitsafe/master/screenshot.png)

### Install
```bash
git clone https://github.com/jterenzio/gitsafe.git
cd gitsafe/
sudo sh install
# follow post-install instructions to add alias
```
