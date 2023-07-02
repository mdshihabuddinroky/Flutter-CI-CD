# Build APK using GitHub Actions

This repository provides a GitHub Actions workflow to automate the process of building Flutter APKs whenever code is pushed to the main branch. Follow the steps below to set up this workflow in your Flutter project.

## Prerequisites

- Flutter SDK installed on your development machine.
- Git installed on your development machine.
- A GitHub account.

## Getting Started

1. **Fork the Repository**: Click the "Fork" button at the top-right corner of this repository to create your own copy.

2. **Clone the Repository**: Clone the forked repository to your local development environment:

   ```shell
   git clone https://github.com/your-username/build-apk.git
   cd build-apk
Copy the Workflow File: Copy the .github/workflows/build-apk.yml file from this repository to the root directory of your Flutter project.

Update the Workflow: Open the copied build-apk.yml file and make any necessary modifications to suit your project's needs. For example, you can customize the Flutter channel or adjust the target platforms for the APK build.

Commit and Push: Commit the changes to your Flutter project repository:

git add .
git commit -m "Add build APK workflow"
git push origin main


3. Enable GitHub Actions: Go to your Flutter project repository on GitHub and navigate to the "Actions" tab. Enable GitHub Actions for the repository.

4. Run the Workflow: Once GitHub Actions is enabled, the workflow will automatically run whenever new code is pushed to the main branch. You can check the workflow status and logs in the "Actions" tab.

5. Retrieve the APK: After the workflow completes, the generated APK file will be available as an artifact. You can download the APK by going to the "Actions" tab, selecting the workflow run, and navigating to the "Artifacts" section.
