# ​💻 Windows Tailscale Remote Desktop 🚀
This repository serves as a step-by-step guide on how to set up a Tailscale Remote Desktop (RD) using GitHub Actions.

# ​🛠️ Steps on How to Deploy
​Follow these simple steps to get your Windows Tailscale RD running:
​Prerequisites (You Need):
​✅ A Tailscale Account.
​🔑 A Tailscale Auth Key.
​🐙 A GitHub Account with GitHub Actions enabled.
​Deployment Process:
​➡️ Go to the GitHub repository where you want to deploy the Tailscale Windows RD.
​⚙️ Add a Repository Secret:
​Navigate to your repository Settings \rightarrow Secrets \rightarrow Actions.
​Click on New repository secret.
​Name the secret exactly: "TAILSCALE_AUTH_KEY".
​Paste your Tailscale key into the Value field and save.
​⬇️ Get the Workflow File:
​Download the .yml file from this repository:
​Path: 1/.github/workflows/
​Direct Link: https://github.com/clowny-louis/1/blob/main/.github/workflows/main.yml
​⬆️ Add the .yml File to Your Repository:
​Upload the downloaded .yml file to the path .github/workflows/ in your repository, or simply copy the code and create the file manually.
# Enjoy! 🎉 
​That's all there is to it! Your GitHub Action should now run and provision your Tailscale node.
# ​⚠️ Important Note 
If your GitHub account happens to get banned, the suggested next step is to create a new one, perhaps using an Outlook email address.
