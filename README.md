ALXprodev Advanced Git
GitFlow Workflow Setup
This repository follows the GitFlow branching model for collaborative development.

GitFlow Branches
main/master: Production-ready code (stable releases).
develop: Integration branch for ongoing development.
feature/*: New features developed in isolation.
release/*: Preparation for production releases.
hotfix/*: Critical bug fixes for production.
Setup GitFlow
git flow init -d  # Initialize with default settings
Basic GitFlow Commands
Start a new feature:
git flow feature start <feature_name>
Finish a feature (merges into develop):
git flow feature finish <feature_name>
Create a release:
git flow release start 1.0.0
Deploy a release (merges into main and develop):
git flow release finish 1.0.0
License
This project is licensed under the ALX ProDEV Software Engineering Backend Program. To install hooks: cp git-hooks/* .git/hooks/
