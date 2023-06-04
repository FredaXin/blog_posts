# Automate your GitHub commits with GitHub Actions
This blog post offers an introduction to GitHub Actions and GitHub Actions templates, including an example of a template. By reading this, you will gain the knowledge needed to automate your daily GitHub commits.


## What is GitHub Actions? 
GitHub Actions is a CI/CD tool which allows you to define custom workflows and automate various tasks directly within your GitHub repositories. With GitHub Actions, you can create workflows that respond to events (such as code pushes, pull requests, or issue creation), build and test your code, deploy applications, and much more. Workflows are defined using YAML files and can be easily customized to meet your specific needs.

## What is GitHub Actions Templates? 
GitHub Actions Templates are pre-defined GitHub Actions workflows that can be reused across multiple repositories or shared with the GitHub community. These templates provide a starting point for creating workflows and can save you time and effort by providing commonly used actions and configuration options. They are essentially a collection of steps, jobs, and actions configured to perform a specific task or automate a particular process. GitHub Action templates can be easily imported into your repository and customized based on your requirements.


## An Example Template: *It's Lit*
[*It's Lit*](https://github.com/FredaXin/itslit) is a template which you can use to create automated git commits daily, so your GitHub Contribution Graph will be green as a summer field throughout the year. It utilizes a GitHub action, defined in the [*gitlit*](https://github.com/FredaXin/gitlit) repo. The action can be set on a cron schedule, or triggered manually. The GitHub action will make a randomized number of empty git commits.


## How to use it? 
1. Create a repository from the *It's Lit* template:
   - Click the green "Use this template" button in the upper right.
   - Select "Create a new repository"

2. In your new repo, edit the [`.github/workflows/main.yml`](./.github/workflows/main.yml) file and add in your GitHub username and email.  
(Optional) Edit the cron expression to your desired schedule.     
(Optional) Edit the upper bond and lower bond of the total number of commit per action.  

3. Ensure the Workflow has the correct permissions:  
In GitHub UI, navigate to your newly created repo, go to `settings -> Actions -> Workflow permissions`, choose `Read and write permissons` and then `save`. 


## Cool template, but why? 
"Why do I need this template", you might ask? GitHub has become a hybrid repo host and social network that incentivizes user engagement by [gamification](https://shesho.medium.com/why-gamification-is-broken-and-how-to-fix-it-f12987840eb7). It might appear very productive to make frequent commits to keep your GitHub Contribution graph green, it might even give you some dopamine boosts during your daily GitHub routine, but can it translate into meaningful work and deep engagement? 

Think of *It's Lit* as an automatic lawn sprinkler system: it keeps your graph green and maintains the curb appeal of your GitHub profile; it frees you from busy work so you can do the work that matters.

Let the roots of your thoughts grow deeper, the trunks of your projects grow taller. We can all use more trees than lawns. :evergreen_tree: :evergreen_tree: :evergreen_tree: