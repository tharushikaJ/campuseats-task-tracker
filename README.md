# campuseats-task-tracker

cmnds
git clone https://github.com/tharushikaJ/campuseats-task-tracker —  downloads a full copy of the remote repo to your machine./n
cd campuseats-task-tracker 
git status — shows the current branch and whether there are uncommitted changes.
mkdir src — creates a new folder named src.
echo "// CampusEats task list" > src/tasks.js — creates tasks.js and writes that comment into it.
git remote -v — lists the remote repo URLs (fetch/push) linked to this local repo.
git switch -c feature/add-task-list — creates a new branch called feature/add-task-list and switches to it.
git add src/tasks.js — stages tasks.js so it's included in the next commit.
git commit -m "feat: add initial CampusEats task list" — saves the staged changes as a commit with that message.
git push -u origin feature/add-task-list — pushes the new branch to GitHub and sets it to track the remote branch (-u).
git switch main — switches back to the main branch.
git pull origin main — fetches and merges the latest changes from remote main into your local main.
git switch -c chore/add-ci — creates and switches to a new branch called chore/add-ci.
mkdir -p .github/workflows — creates the nested .github/workflows folder (the -p makes parent folders as needed).
touch .github/workflows/ci.yml — creates an empty ci.yml file.
git add .github/workflows/ci.yml — stages the new CI workflow file.
git commit -m "chore: add GitHub Actions CI workflow" — commits that file.
git push -u origin chore/add-ci — pushes this branch to GitHub and sets up tracking.
code src/tasks.js — opens tasks.js in VS Code for editing.
git status — shows tasks.js as modified but not yet staged.
git add src/tasks.js — stages the edited tasks.js.
git commit -m "refactor: improve task calculation security" — commits those edits.
ls — lists files/folders in the current directory.
find . -name "package.json" — searches recursively for a file named package.json (found none, since no output appeared).
