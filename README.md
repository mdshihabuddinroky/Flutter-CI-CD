# Build APK using GitHub Actions

This repository provides a GitHub Actions workflow to automate the process of building Flutter APKs whenever code is pushed to the main branch.

## Setup

To set up the code for building Flutter APKs using GitHub Actions, follow these simple steps:

1. **Fork the Repository**: Click the "Fork" button at the top-right corner of this repository to create your own copy.

2. **Copy the Workflow File**: In your Flutter project, copy the `.github/workflows/build-apk.yml` file from this repository.

3. **Paste the Workflow File**: Paste the copied `build-apk.yml` file into the `.github/workflows/` directory of your Flutter project.

4. **Commit and Push**: Commit the changes to your Flutter project repository.

5. **Enable GitHub Actions**: Go to your Flutter project repository on GitHub and navigate to the "Actions" tab. Enable GitHub Actions for the repository.

6. **Run the Workflow**: Once GitHub Actions is enabled, the workflow will automatically run whenever new code is pushed to the main branch.

7. **Download the APK**: After the workflow completes, you can download the generated APK file by going to the "Actions" tab, selecting the workflow run, and navigating to the "Artifacts" section.

That's it! Now your Flutter project is set up to automatically build APKs whenever you push new code to the main branch. You can find the generated APK in the "Artifacts" section of the workflow run in the GitHub Actions tab.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
