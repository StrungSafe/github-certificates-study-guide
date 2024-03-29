# Domain 2: Working with GitHub Repositories

## Understanding GitHub Repositories

1. Describe the components of a good README and the recommended repository files (LICENSE, CONTRIBUTING, CODEOWNERS)
    - README is a welcome page of the project, it generally provides information on how to get started using the project, it's also common to add information on how to engage w/ the community
    - CODEOWNERS file assigns team members or teams as code owners, they are required for pull-request reviews
    - CONTRIBUTING provides guidance on how to contribute to the project including how the contribution process works and includes details on how to set up your dev environment
    - LICENSE describes how the project can and cannot be used
    - CODE_OF_CONDUCT sets ground rules for community members and helps make the community a safe and welcoming environment
1. Explain basic repository navigation
    - Code allows for browsing the source
    - Issues are used to track the projects' various changes that are needed or requested
    - Pull requests are used to find open and closed PRs
    - Actions are used to view automation for the repo
    - Projects are used to organize and plan
    - Security helps to identify any problems that might exist in the repo
    - Insights is used to inspect information about the repo usage
    - Settings allows owners to manage the repo
1. Explain how to create a new repository
    - From GitHub.com, go to your user's or organization's repositories page and click "New"
    - From GitHub.com, click the "+" symbole in the header and then "New Repository"
    - From Visual Studio, click File->New->Repository
    - From Visual Studio, Select Repository (lower right)->{meatballs}->Create Git Repository
1. Describe repository templates
    - A repository template allows creating a new repository that follows the same directory structure, branches, and files specified in the template
1. Describe the different features to maintaining a repository
    - Branches are used to seperate different states and features
    - Pull requests are used to request branch commits to be pulled into another branch
    - Forks allow users and teams to have their own copy of the repo, helpful when they don't have permission to work directly in the source repo
1. Describe how to clone a repository
    - From command line, `git clone <repository>` is the most simplicistic example
    - From Visual Studio, File->Clone Repository
    - From Visual Studio, Select Repository (lower right)->{meatballs}->Clone Repository
1. Describe how to create a new branch
    - From GitHub.com in repo, select branch dropdown, type new branch name, click Create {new branch} from {reference branch}
    - From command line, `git branch <branch name>`
1. Explain how to add files to a repository
    - From command line, add your files in your repository, `git add .`, `git commit -m <message>`, `git push`
    - From GitHub.com, Add file->Create new file->Add filename and file contents, Commit changes
1. Identify how to view repository insights
    - GitHub.com, go to the main page of the repo, under the repo name select Insights
    - Things like pulse, contributors, traffic, forks etc. can be viewed from the insights tab
1. Explain how to save a repository with stars
    - Go to a repo and click the Star icon which whill save the repo to your stars list
1. Explain feature previews
    - A feature preview is usually a branch that is isolated and contains the commits for a new feature
