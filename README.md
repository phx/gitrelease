# gitrelease

I can't take credit for the majority of this code.

I took the code from 2 separate authors that I found who posted solutions in a forum.

I made the last part easier for MacOS Homebrew developers.

If you `export CASK=1`, then the last few lines will be formatted perfectly to copy/paste into a Homebrew Cask formula.

Otherwise, the last few lines will be perfectly formatted to copy/paste into a regular Homebrew formula.

This is not just for MacOS. It's for anyone with who uses `bash` and `git` and wants to publish a cli GitHub release.

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
