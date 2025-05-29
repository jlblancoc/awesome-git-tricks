# awesome-git-tricks
Put this in your PATH and get new handy Git commands

## Install

```bash
cd ~/code  # put here some workspace/code/work directory you like
git clone https://github.com/jlblancoc/awesome-git-tricks.git
cd awesome-git-tricks

# Add to .bashrc
echo "export PATH=$(pwd):\$PATH" >> ~/.bashrc

# activate it:
. ~/.bashrc
```

## Command list

`git clean-removed-in-origin`

Deletes all local branches corresponding to branches that were
already removed in `origin`.

`git push-this-branch [optional flags]`

Pushes the current branch only to the default remote.
