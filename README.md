# Rasa Template: Installation & Configuration

Follow these steps to install and configure your Rasa project using this template:

## Prerequisites
Ensure you have the following installed on your system:
- Python 3.8 or later
- pip (Python package installer)
- Virtual environment tool (optional but recommended)

## Installation Steps

1. **Install Rasa**
   Follow the instructions on the [official Rasa installation guide](https://rasa.com/docs/rasa-x/installation-and-setup/).

2. **Create a Project Directory**
   Create a new directory for your project:
   ```bash
   mkdir project_directory
   cd project_directory
   ```

3. **Initialize Rasa**
   Initialize Rasa within your project directory by running:
   ```bash
   rasa init
   ```
   Follow the prompts to create a basic Rasa project.

4. **Replace Template Files**
   Download this template and replace the files in your `project_directory` with the ones from the template.

5. **Train the Bot**
   Train the bot with the following command:
   ```bash
   rasa train
   ```

6. **Evaluate the Bot**
   Test the bot in your terminal with the command:
   ```bash
   rasa test
   ```

## Optional Steps

7. **Run Custom Actions**
   If your template includes an `actions.py` file, you need to run the custom actions server. Open a new terminal and execute:
   ```bash
   rasa run actions
   ```

8. **Start Talking to the Bot**
   Interact with the bot in the terminal:
   ```bash
   rasa shell
   ```

## Troubleshooting
- Ensure all dependencies are correctly installed.
- Check the Rasa documentation for additional support.

---
Enjoy building with Rasa! If you encounter any issues, feel free to raise them in the issues section of this repository.
