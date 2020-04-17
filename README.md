# gitrelease

I can't take credit for the majority of this code.

I took the code from 2 separate authors that I found who posted solutions in a forum.

If you don't want to set the token for each project, you can `export GITHUB_TOKEN=[YOUR TOKEN]`.

## Usage:

- Copy `gitrelease` to somewhere in your `$PATH`
- `gitrelease [VERSION NUMBER] <version name>`

```
##############################################################################
# Settings > Developer Settings > Personal access tokens > Generate new token
# git config --global github.token [YOUR_TOKEN]
# USAGE: ./gitrelease [VERSION_TAG] [RELEASE DESCRIPTION]
##############################################################################
```

---

I also made this easier for MacOS Homebrew developers, which was my primary reason for creating it.

If you `export CASK=1`, then the last few lines will be formatted perfectly to copy/paste into a Homebrew Cask formula.

Otherwise, the last few lines will be perfectly formatted to copy/paste into a regular Homebrew formula.

That being said, this script is not just for MacOS.

It's for anyone with who uses `bash` and `git` and wants to publish a GitHub release from the command line.
