## How to contribute?

### Pre-requisites
- Register for the [Open Source Contributor Program](https://bit.ly/3F8Jsjr) so we can add you to the team of contributors in the Naas GitHub organization. To start working on our repository, you must be a part of our [open-source contributors team](https://github.com/orgs/jupyter-naas/teams/opensource-contributors). Please check your email and validate the invitation before you begin working on a new issue.
- Create your [GitHub personal access token](https://github.com/settings/tokens). Select “No expiration” and tick only the first section repository and keep your token safe as you won’t be able to generate it again.
- Open a [free account on Naas Lab](https://app.naas.ai/) so we can test the templates in a similar environment.

### Step 1: Create or Select an Issue

Identify or propose an issue you wish to work on. It could be a snippet of Python code, an API integration with a tool you are using, or an automation leveraging existing templates with our scheduler, asset, or webhook features. Before you begin working on it, prepare the issue:

- Ensure the description is clear.
- Tag yourself in the Assignees section.
- Change the status to 'In Progress' in the Projects section/Community Roadmap.
- Create a branch in the Development section.

### Step 2: Technical Setup

Clone the awesome-notebooks repository on your Naas Cloud account and switch to the branch you created.
If a draft of a template (generated with our AI system) has been already created, you can directly start working on it.

Otherwise, you kick start manually:
- Create a folder named with the source tool (if it's not already created).
- Copy/Paste template.ipynb at the root of the repository.
- Rename the template following this format: `Toolname_Function.ipynb`.

### Step 3: Work on Your Notebook

Start working on your notebook. Commit your work every time you make significant progress. You can use the UI interface inside your Naas Lab server to do this.

- All new files will be found in the untracked section, all modified files in the unstaged section.
- Once you want to commit, add your notebook to staged by clicking on the + and create a commit message. We recommend following the commit convention and starting your message with “feat:” if it's an improvement or “fix:” if it's a bug fix, followed by a clear commit message. Here are some examples:
    - feat: update tags, author, and description
    - feat: developing function in model to…
    - fix: adding try except to manage error on…
- Once you're satisfied with the result, push to the branch by clicking on the icon on top (make sure you use a GitHub personal access token and not a password, otherwise, it won’t work).
- Ensure the notebook respects the framework.

### Step 4: Open a Pull Request

Open a Pull Request and add a Templates Maintainer as Reviewer: Florent (FlorentLvr), Srini (srini047) or Jérémy (jravenel).

- Change the status of this Issue to “Review” in the Projects section and comment on the Pull Request with a brief summary of what you've done.
- You will now discuss your work on the PR. If any changes are made, ensure you pull the branch before working on it again by clicking on the button at the top.
- Expect feedback and merge within the next 48-72 hours.

### Step 5: Promote Your Work

Once merged, promote your work on LinkedIn, Twitter, and other social media channels! (Optional, but people need to know you are awesome 😉). Explain why you did this notebook and how it could be useful. You can use the certificate generated once the PR is merged to display your work and add the tag open source contributor on your LinkedIn profile. We will be happy to have you in our community.

Thank you!

### Step 6: Become a Templates Maintainer

If you want to contribute more frequently to Naas, you can become a templates maintainer. This status will offer you the right to be sponsored by Naas for your contributions done every month, ranging from $50 to $250. To become a templates maintainer, you must have completed at least 5 notebooks (which ensures you've mastered our process) and created 5 social media content promoting your template or Naas.

Then, you will be introduced to our template maintainer program and will have a dedicated team with the core team to assist you in developing integrations, automations, or AI systems.
