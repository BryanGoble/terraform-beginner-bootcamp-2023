# Terraform Beginner Bootcamp 2023

# Using GitPod

## Branching

- Use branches to work on new features until ready to merge and to address specific issues.
- `git checkout -b <branch-name>` - When choosing a branch name, try to start it with the issue number and a short reference to the Issue being addressed.
- Once you're ready to commit, start your message with a pound sign, `#`, followed by the Issue number then you can continue with the commit message as normal.
	- This will assign your commit as an addressal to the specified issue.

## Tags

- You can use tags to track your versions in GitHub, `git tag <version>`.
	- After you create the tag, use `git push --tag` to assign the tag to the current branch.

### Semantic Versioning :mage:

The general format: **MAJOR.MINOR.PATH**, eg. `1.0.1`

1. **MAJOR** version when you make incompatible API changes
2. **MINOR** version when you add functionality in a backward compatible manner
3. **PATCH** version when you make backward compatible bug fixes

> Additional labels for pre-release and build metadata are available as extensions to the **MAJOR.MINOR.PATCH** format.

## Bash Scripts
- `chmod u+x <file>` - Modifies the user permissions with the executable permission
- `.sh` or other executable script extensions are not required as they are not *technically* semantically correct and are already defined after the Shebang, `#!`, eg. `#!/usr/bin/env bash`

# Resources :link:
1. [Install Terraform CLI | Hashicorp](https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli) - Used for the Terraform CLI Install commands as the original install instructions were outdated. Terraform made the addition of the gpg keyring.
2. [Oh My Bash | GitHub](https://github.com/ohmybash/oh-my-bash) - Bash CLI Prettify