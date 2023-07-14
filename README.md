# GitHub Actions Importer Full Guide 🚀

GitHub Actions Importer helps plan, test, and automate your migration to GitHub Actions from the following platforms:

- Azure DevOps 🔄
- Bamboo (currently in beta) 🎋
- CircleCI 🔄
- GitLab 🔄
- Jenkins 🔄
- Travis CI 🔄

## How to Request Support ❓

If you need assistance, you can file a support ticket [here](https://example.com/support).

## Getting Started 🚀

GitHub Actions Importer is distributed as a Docker container and this extension to the official GitHub CLI to interact with the Docker container.

### Prerequisites ✅

The following requirements must be met to be able to use the GitHub Actions Importer:

- The Docker CLI must be installed and running. 🐳
- The official GitHub CLI must be installed. 💻
- You must have credentials to authenticate with the GitHub Container Registry. 🔑

### Installation ⬇️

Next, the GitHub Actions Importer CLI extension can be installed via this command:


$ gh extension install github/gh-actions-importer

### Configuration⚙️
New versions of the GitHub Actions Importer are released on a regular basis. To ensure you're up to date, run the following command:
$ gh actions-importer update

In order for GitHub Actions Importer to communicate with your current CI/CD server and GitHub, various credentials must be available for the command. These can be configured using environment variables or a .env.local file. These environment variables can be configured in an interactive prompt by running the following command:
$ gh actions-importer configure
? Enter value for 'GITHUB_ACCESS_TOKEN' (leave empty to skip): 
...
You can find detailed information about using environment variables in the platform-specific documentation.

### Documentation📖
Detailed information about how to use GitHub Actions Importer can be found in the documentation.

### Recordings▶️
You can access recorded demos of GitHub Actions Importer performing migrations to Actions from the following CI/CD platforms:

- Azure DevOps
- CircleCI
- GitLab
- Jenkins
- Travis CI
- Self-guided learning📚
The GitHub Actions Importer labs repository contains platform-specific learning paths that teach you how to use GitHub Actions Importer and how to approach migrations to GitHub Actions. To learn more, see the GitHub Actions Importer labs repository.

### Product roadmap  🚧
To learn about new features coming to GitHub Actions Importer, see the GitHub Public Roadmap.

## How to offer feedback or make a feature request 📣

If you would like to offer feedback or make a feature request, please create a new discussion [here](https://github.com/github/gh-actions-importer/discussions/new/choose). 

Feel free to reach out! 😊 [Click me](https://linktr.ee/ADV_Indian_coder) ADV Indian Coder Vinay Kumar Java Developer


