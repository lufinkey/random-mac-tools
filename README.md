A collection of random tools and scripts for different things in macOS

#### Installation

```
git clone https://github.com/lufinkey/random-mac-tools
cd random-mac-tools
./install.sh
```

# git-split

Creates a git worktree for a branch and opens Terminal windows for it, with one running Claude

### Usage

```
git-split <branch>
```

If the branch already exists, it will be reused. Otherwise, a new branch is created. Two Terminal windows are opened in the worktree directory — one plain and one running `claude`.

# git-split-done

Removes the current git worktree

### Usage

```
git-split-done
```

Must be run from within a worktree (not the main repository). Removes the worktree and exits the directory.
