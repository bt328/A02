# How to Use Git and GitHub with Visual Studio Code
## Section 1: Installations
- Download Git: https://git-scm.com/install/
- Create a GitHub account: https://github.com/signup
- Download Visual Studio Code: https://code.visualstudio.com/download
- Install the GitHub Pull Requests and Issues extension in VS Code: https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github
  - In Visual Studio Code, click the GitHub icon in the Activity Bar and sign in with your GitHub account.

## Section 2: Setting Up the Repository
- On GitHub, click your profile, then Repositories, and then New.
- Enter a repository name and basic information, then click Create repository.
- To clone an existing repository:
  - Open the Command Palette with Ctrl + Shift + P
  - Select Git: Clone
  - Paste the repository URL and choose a local folder

## Section 3: Making Changes, Branches, and Commits
- Open the Command Palette and use Git: Rename Branch to rename your branch.
- Click the Source Control icon to view file changes.
- Enter a short message describing your changes before committing.
- Use Git: Create Branch to create a new branch.
- To merge branches:
  - Click the three dots (…) in the Source Control menu
  - Select Branch → Merge
- Click the branch name in the bottom-left corner to switch between branches.

## Section 4: Definitions
- Branch: A divergence in code from a starting point, allowing independent changes and commits without altering the main codebase.
- Clone: To copy an existing repository from GitHub to your local machine.
- Commit: A saved record of changes made to files in a branch.
- Fetch: Downloads updates from a remote repository without applying them to your local files.
- Git: A version control system that tracks changes to files and allows multiple people to collaborate on the same project.
- GitHub: A cloud-based platform that stores Git repositories and allows users to share code, collaborate, and manage projects online.
- Merge: Combines the changes from one branch into another branch.
- Merge Conflict: Occurs when two branches change the same part of a file differently and Git cannot decide which change to keep. The conflict must be resolved manually.
- Push: Uploads local commits to the remote repository on GitHub.
- Pull: Downloads and applies changes from the remote repository to your local repository.
- Remote: A version of the repository hosted on another server (usually GitHub).
- Repository: A project folder that contains files, code, and the history of changes tracked by Git.

## Section 5: Sources
- https://code.visualstudio.com/docs/sourcecontrol/github