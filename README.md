Last login: Thu Oct  2 16:02:22 on console
swayam@MacBookAir ~ % /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
==> Checking for `sudo` access (which may request your password)...
Password:
==> This script will install:
/opt/homebrew/bin/brew
/opt/homebrew/share/doc/homebrew
/opt/homebrew/share/man/man1/brew.1
/opt/homebrew/share/zsh/site-functions/_brew
/opt/homebrew/etc/bash_completion.d/brew
/opt/homebrew
/etc/paths.d/homebrew

Press RETURN/ENTER to continue or any other key to abort:
==> /usr/bin/sudo /usr/sbin/chown -R swayam:admin /opt/homebrew
==> Downloading and installing Homebrew...
remote: Enumerating objects: 7607, done.
remote: Counting objects: 100% (2282/2282), done.
remote: Compressing objects: 100% (66/66), done.
remote: Total 7607 (delta 2236), reused 2216 (delta 2216), pack-reused 5325 (from 2)
==> /usr/bin/sudo /bin/mkdir -p /etc/paths.d
==> /usr/bin/sudo tee /etc/paths.d/homebrew
/opt/homebrew/bin
==> /usr/bin/sudo /usr/sbin/chown root:wheel /etc/paths.d/homebrew
==> /usr/bin/sudo /bin/chmod a+r /etc/paths.d/homebrew
==> Updating Homebrew...
==> Downloading https://ghcr.io/v2/homebrew/core/portable-ruby/blobs/sha256:c6946ba2c387b47934e77c352c2056489421003ec7ddb2abf246cef2168ec140
######################################################################### 100.0%
==> Pouring portable-ruby-3.4.7.arm64_big_sur.bottle.tar.gz
Updated 2 taps (homebrew/core and homebrew/cask).
==> Installation successful!

==> Homebrew has enabled anonymous aggregate formulae and cask analytics.
Read the analytics documentation (and how to opt-out) here:
  https://docs.brew.sh/Analytics
No analytics data has been sent yet (nor will any be during this install run).

==> Homebrew is run entirely by unpaid volunteers. Please consider donating:
  https://github.com/Homebrew/brew#donations

==> Next steps:
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh

swayam@MacBookAir ~ % brew install git

==> Fetching downloads for: git
✔︎ Bottle Manifest git (2.52.0)                     [Downloaded   20.6KB/ 20.6KB]
✔︎ Bottle Manifest libunistring (1.4.1)             [Downloaded    7.3KB/  7.3KB]
✔︎ Bottle Manifest gettext (0.26_1)                 [Downloaded   13.8KB/ 13.8KB]
✔︎ Bottle Manifest pcre2 (10.47)                    [Downloaded   10.4KB/ 10.4KB]
✔︎ Bottle pcre2 (10.47)                             [Downloaded    2.4MB/  2.4MB]
✔︎ Bottle libunistring (1.4.1)                      [Downloaded    1.9MB/  1.9MB]
✔︎ Bottle gettext (0.26_1)                          [Downloaded    9.6MB/  9.6MB]
✔︎ Bottle git (2.52.0)                              [Downloaded   21.5MB/ 21.5MB]
==> Installing dependencies for git: libunistring, gettext and pcre2
==> Installing git dependency: libunistring
==> Pouring libunistring--1.4.1.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/libunistring/1.4.1: 59 files, 5.8MB
==> Installing git dependency: gettext
==> Pouring gettext--0.26_1.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/gettext/0.26_1: 2,428 files, 29.6MB
==> Installing git dependency: pcre2
==> Pouring pcre2--10.47.arm64_sequoia.bottle.tar.gz
🍺  /opt/homebrew/Cellar/pcre2/10.47: 244 files, 7.3MB
==> Installing git
==> Pouring git--2.52.0.arm64_sequoia.bottle.tar.gz
==> Caveats
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.
==> Summary
🍺  /opt/homebrew/Cellar/git/2.52.0: 1,718 files, 59.8MB
==> Running `brew cleanup git`...
Disable this behaviour by setting `HOMEBREW_NO_INSTALL_CLEANUP=1`.
Hide these hints with `HOMEBREW_NO_ENV_HINTS=1` (see `man brew`).
==> Caveats
zsh completions and functions have been installed to:
  /opt/homebrew/share/zsh/site-functions
==> git
The Tcl/Tk GUIs (e.g. gitk, git-gui) are now in the `git-gui` formula.
Subversion interoperability (git-svn) is now in the `git-svn` formula.
swayam@MacBookAir ~ % git --version

git version 2.39.5 (Apple Git-154)
swayam@MacBookAir ~ % cd ~/swayam/Yt script     
cd: string not in pwd: /Users/swayam/swayam/Yt
swayam@MacBookAir ~ % cd "/Users/swayam/Yt Script"

swayam@MacBookAir Yt Script % git init

Initialized empty Git repository in /Users/swayam/Yt script/.git/
swayam@MacBookAir Yt Script % git remote add origin https://github.com/SWAYAM-RANPISE/YoutubeScripts
swayam@MacBookAir Yt Script % git add .

swayam@MacBookAir Yt Script % git commit -m "Initial upload of YouTube scripts"

[main (root-commit) d126bff] Initial upload of YouTube scripts
 Committer: swayam <swayam@MacBookAir.lan>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 4 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Amityvilla.pdf
 create mode 100644 Ratan Tata.pdf
 create mode 100644 The fall of nokia.pdf
 create mode 100644 The hunt for Osama.pdf
swayam@MacBookAir Yt Script % git branch -M main
git push -u origin main

Username for 'https://github.com': SWAYAM-RANPISE
Password for 'https://SWAYAM-RANPISE@github.com': 
remote: Invalid username or token. Password authentication is not supported for Git operations.
fatal: Authentication failed for 'https://github.com/SWAYAM-RANPISE/YoutubeScripts/'
swayam@MacBookAir Yt Script % git push -u origin main

Username for 'https://github.com': SWAYAM-RANPISE
Password for 'https://SWAYAM-RANPISE@github.com': 
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 8 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 1.65 MiB | 1.89 MiB/s, done.
Total 6 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/SWAYAM-RANPISE/YoutubeScripts
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
swayam@MacBookAir Yt Script % nano README.md

  UW PICO 5.09                    File: README.md                     Modified  


For collaboration, suggestions, or inquiries, reach out at:

**Email:** contact.gowithsameer@gmail.com
**GitHub:** [SWAYAM-RANPISE](https://github.com/SWAYAM-RANPISE)

---
   
*Created by Swayam Ranpise | 2025*







   
   


^G Get Help  ^O WriteOut  ^R Read File ^Y Prev Pg   ^K Cut Text  ^C Cur Pos   
^X Exit      ^J Justify   ^W Where is  ^V Next Pg   ^U UnCut Text^T To Spell  
