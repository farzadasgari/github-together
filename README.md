# **github-together**
A comprehensive guide to collaborating effectively on GitHub projects, covering workflows, best practices, and tips for a smooth and productive experience. 
![GitHub stars](https://img.shields.io/github/stars/farzadasgari/github-together)

<hr><br>

## **Prerequisites**
- An existing GitHub repository created by the owner (admin).
- Collaborators must have a GitHub account with write access to the repository.

<hr><br>

## **Forking the Repository**
- Go to the repository on GitHub.
- Click on the "Fork" button in the top right corner. This will create a copy of the repository in your own GitHub account.

<br>

### **Making Changes Locally (in a Branch)**

#### **Clone your Fork**
- Navigate to your forked repository on GitHub.
- Click on the green "Code" button and choose `SSH` or `HTTPS` depending on your preference. This will provide the URL to clone the repository.
- Open your terminal or command prompt and use the `$ git clone` command followed by the URL you copied. This will create a local copy of your forked repository on your computer.

#### **Create a New Branch**
- Open your terminal and navigate to your local repository directory.
- Use the command `$ git checkout -b <branch_name>` to create a new branch. Replace `<branch_name>` with a descriptive name that reflects your changes (e.g., "fix_bug_x").

#### **Make Changes**
- Open your local repository in your preferred code editor like `PyCharm`, `VSCode`, `Atom`, etc.
- Make your desired changes to the codebase.

#### **Commit Changes**
- In your code editor terminal, use the `Git` integration to stage your changes and commit them with clear messages.

#### **Push Changes to Your Branch**
- After committing, use the Git integration or the terminal to push your changes to your newly created branch on GitHub.
- The command would be `$ git push origin <branch_name>`, where `<branch_name>` is the name you assigned in step 2.

<hr><br>

## **Creating a Pull Request**

#### **Go to GitHub**
- Navigate to your forked repository on GitHub.

#### **Initiate Pull Request**
- Click on the `Pull requests` tab.
- Click on the green `New pull request` button.

#### **Compare Branches**
- GitHub will ask you to choose the base branch (usually the original repository's `master` or `main`) and the compare branch (your newly created branch). Select them accordingly.

#### **Write a Description**
- In the pull request description, clearly explain the changes you made and why they are beneficial to the project. Mention that you made the changes in a separate branch (`<branch_name>`).

#### **Request Review (Optional)**
- You can optionally request a review from other collaborators by mentioning them using the `@` symbol followed by their username. However, with the setup explained later, this won't affect the merging process.

#### **Submit Pull Request**
- Once you're satisfied with the description, click on the `Create pull request` button.

<hr><br>

## **Enforcing Owner-Only Merging (Using Branch Protection Rules)**

> Note: This step requires the owner (admin) access to the repository settings.

#### **Go to Repository Settings**
- On the main page of the repository, navigate to `Settings` and then `Branches`.

#### **Enable Branch Protection**
- Click on the desired branch (often `master` or `main`) and locate the `Branch protection rules` section. Click on `Edit`.

#### **Require Review (Optional)**
-You can enable the `Require a pull request before merging` option and set the minimum number of approving reviews required (e.g., 1). This ensures code review but won't restrict merging itself.

#### **Restrict Merging**
- Under `Protect matching branches`, select the option `Require review from Code Owners`.

#### **Save Changes**
Click on the `Save changes` button at the bottom of the page.

#### **Review and Merging**
- The owner (admin) will be notified about your pull request.
- They can review your changes, discuss them with you (if needed), and ultimately decide whether to merge your contribution into the main repository.
- Since only the owner has permission to merge, other collaborators with write access cannot accidentally or intentionally merge your pull request, maintaining control over the codebase.

<hr><br>

Here are some additional tips for collaborating effectively on a ***GitHub*** project:

#### **General Workflow**
- **Stay updated**: Regularly use `$ git fetch` to download the latest changes from the main repository and keep your local branch in sync. This helps avoid merge conflicts when you push your changes.
- **Communicate**: Discuss your planned changes with the owner or other collaborators beforehand. This helps avoid duplicate efforts and ensures your contribution aligns with the project's direction.
**Small, focused changes**: Break down larger contributions into smaller, focused pull requests. This makes them easier to review and merge, and reduces the risk of introducing bugs.

#### **Code Quality**
- **Follow coding standards**: If the project has a coding style guide, adhere to it to maintain code consistency and readability.
- **Write clean code**: Aim for well-structured, well-documented, and maintainable code. This makes it easier for others to understand and work with your contributions.
- **Test your code**: Thoroughly test your changes locally before creating a pull request. This helps identify and fix any issues before they impact the main repository.

#### **Pull Requests**
- **Descriptive titles and descriptions**: Craft clear and concise pull request titles and descriptions that summarize the changes you made and their purpose. This helps reviewers understand what your contribution is about.
- **Respond to feedback**: Pay close attention to comments and feedback from reviewers. Address their concerns promptly and professionally.
- **Use labels**: If the project uses labels to categorize pull requests (e.g., bug fix, new feature), use appropriate labels to help with organization.

#### **Maintaining a Positive Collaboration Environment**
- **Be respectful**: Maintain a professional and respectful tone in your communication with other collaborators.
- **Be open to feedback**: Be receptive to constructive criticism and suggestions for improvement.
- **Celebrate contributions**: Acknowledge and appreciate the work of others, fostering a collaborative spirit.

#### **Branching Strategy**
- **Use Feature Branches**: Create separate branches for each new feature or bug fix to isolate changes and facilitate parallel development.
- **Merge Regularly**: Merge changes from the main branch into your feature branches regularly to stay up-to-date and minimize conflicts.

#### **Documentation**
- **Document Changes**: Update relevant documentation, such as README files or code comments, along with code changes to keep project documentation accurate and up-to-date.
- **Use Wiki or Docs**: Utilize project wikis or documentation files to provide additional context, guidelines, or usage instructions for contributors.

#### **Continuous Integration/Continuous Deployment (CI/CD)**
- **Set up CI/CD Pipelines**: Implement automated testing and deployment pipelines to ensure code quality and streamline the release process.
- **Monitor Builds**: Monitor CI/CD pipelines for failures or errors and address them promptly to maintain a stable development environment.

#### **Code Reviews**
- **Conduct Code Reviews**: Encourage peer code reviews to catch bugs, ensure adherence to coding standards, and share knowledge among team members.
- **Provide Constructive Feedback**: Offer constructive feedback during code reviews to help contributors improve their code and learn from each other.

#### **Community Guidelines**
- **Establish Contribution Guidelines**: Define clear contribution guidelines, including coding standards, issue labeling conventions, and pull request review processes, to streamline collaboration and maintain project consistency.
- **Welcome New Contributors**: Create a welcoming environment for new contributors by providing guidance, mentorship, and support as they navigate the project.

These additional tips cover various aspects of collaborative development, from branching strategies to community engagement, and can further enhance the effectiveness of collaboration on ***GitHub*** projects.

<hr><br>

# **Contact**
If you have any questions, feel free to contact me at std_farzad.asgari@alumni.khu.ir or farzad.developer13@gmail.com.

<br>

# **Links**
[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://farzadasgari.ir/)

[![Google Scholar Badge](https://img.shields.io/badge/Google%20Scholar-4285F4?logo=googlescholar&logoColor=fff&style=for-the-badge)](https://scholar.google.com/citations?user=Rhue_kkAAAAJ&hl=en)

[![ResearchGate Badge](https://img.shields.io/badge/ResearchGate-0CB?logo=researchgate&logoColor=fff&style=for-the-badge)](https://www.researchgate.net/profile/Farzad-Asgari)

[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/farzad-asgari-5a90942b2/)
