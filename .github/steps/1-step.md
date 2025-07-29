## Step 1: Setting Up Copilot Instructions

You're a teacher at Mergington High School who creates homework assignments and coding exercises for students. You maintain a static website to share these assignments and want to establish general standards for AI assistants to ensure consistent code quality and project structure.

You've heard Copilot Instructions can help with that!

<details>
<summary>Website screenshot</summary><br/>

You will run this website in the first activity!

<img width="1122" height="784" alt="image" src="https://github.com/user-attachments/assets/d8551981-a90d-4a83-b11b-6e337d7896a1" />

</details>

### 📖 Theory: What are repository custom instructions?

Repository custom instructions let you provide Copilot with repository-specific guidance and preferences that help it understand your project context and standards. By creating a `.github/copilot-instructions.md` file, you can ensure that Copilot's suggestions consistently follow your project conventions and coding standards.

The complete set of instructions will be automatically added to all requests that you submit to Copilot Chat in your repository.

> [!TIP]
> Keep instructions short and focused on project purpose, folder structure, coding standards, and key tools used.
>
> See [GitHub Docs: Repository Custom Instructions](https://docs.github.com/en/copilot/how-tos/custom-instructions/adding-repository-custom-instructions-for-github-copilot) for more information.

### ⌨️ Activity: Explore the Educational Website Project

To work with custom instructions, let's first set up our development environment and explore the project structure.

1. Right-click the below button to open the **Create Codespace** page in a new tab. Use the default configuration.

   [![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/{{full_repo_name}}?quickstart=1)

1. Confirm the **Repository** field is your copy of the exercise, not the original, then click the green **Create Codespace** button.

   - ✅ Your copy: `/{{full_repo_name}}`
   - ❌ Original: `/skills/customize-your-github-copilot-experience`

1. Wait a moment for Visual Studio Code to load in your browser and for all extensions to install.

1. Right-click on `index.html` and select **Show Preview** to see the website in action.

1. Explore the project structure:
   - Browse the `assets/` folder to see the website assets (CSS, JavaScript, images)
   - Look at the `assignments/` folder to understand the existing assignment formats
   - Review `index.html` in the root directory to see the main website structure
   - Check out `config.json` in the root directory to see how the assignments are set up

> [!IMPORTANT]
> Keep the preview tab open as we'll be making edits to the website throughout the exercise and you can see the updates live.

### ⌨️ Activity: Create Repository Copilot Instructions

Now that you've explored the project, let's create custom instructions to help Copilot understand your educational website project.

1. In VS Code, create a new file called `.github/copilot-instructions.md`

   > ❕ **Important:** Make sure the file name is exactly `.github/copilot-instructions.md`. This specific filename is required for Copilot to recognize it as repository instructions.

1. Add the following content to describe this educational project:

   ```markdown
   # Project Description

   This project is an educational website for sharing homework assignments and coding exercises with students. Students can browse, view, and download assignments directly from the portal.

   ## Project Structure

   - [`assignments/`](../assignments/) Each homework assignment is stored in its own subfolder with a consistent structure.
   - [`templates/`](../templates/) Reusable templates for new content
   - [`assets/`](../assets/) Contains the website assets including CSS, JavaScript, images, and configuration files
   - [`index.html`](../index.html) The main website page that serves as a static portal for browsing and viewing assignments. Content is configurable via [`config.json`](../config.json) file to dynamically generate assignment lists and details.

   ## Project Guidelines

   - Maintain consistent styling across all pages
   - Keep file and folder names descriptive and organized

   ## Educational Standards

   When generating content for this project:

   - **Learning-focused**: All content should be designed with clear learning objectives and appropriate difficulty levels
   - **Student-friendly**: Use clear, encouraging language that motivates students
   ```

1. Test your instructions by asking Copilot Chat about the project:

   ```text
   Briefly explain this project to me
   ```

1. Observe how Copilot references your custom instructions in its response - you should see the `.github/copilot-instructions.md` file listed in the references section.

   <img width="504" height="183" alt="image" src="https://github.com/user-attachments/assets/2214ed9e-c165-4440-a23e-d2d33c0231a9" />

1. Commit the `.github/copilot-instructions.md` file to the `main` branch and push to GitHub.

1. Wait for Mona to prepare the next step!

<details>
<summary>Having trouble? 🤷</summary><br/>

- The `.github/copilot-instructions.md` file should be at the root of the `.github` folder
- Make sure you commited and pushed the changes.

</details>
