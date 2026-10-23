## Installing Git and My First Repository

### 1. Install Git
- **Windows:** Download from https://git-scm.com/
- **Verify:** `git --version`

### 2. Basic Terminal Commands
- `pwd` - Shows the current directory.
- `cd foldername` - Moves into a folder.
- `cd ..` - Moves up one directory.
- `ls or dir` - Lists files and folders.(lis for mac and dir for windows)
- `mkdir foldername` - Creates a folder.
- `touch filename` - Creates a new file.

### 3. Create Your First Repository

```bash
mkdir my-first-repo
cd my-first-repo
git init
git status
```

- `git init` - Initializes a Git repository.
- `git status` - Shows the current repository status.
- `.git` - Hidden folder that stores Git data and history.

### 4. Set Git Identity

```bash
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Sets your name and email for commits.

### 5. Key Takeaways
1. Install Git and verify it using `git --version`.
2. Use terminal commands to navigate and manage files.
3. `git init` initializes a repository.
4. Git identity should be configured before your first commit.
