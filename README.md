# Accelerator - GOV UK Design / Decision History

This is now one of the our Accelerators and comes under the category of tools.

This repository is a template to set up a [Design / Decision History](https://x-govuk.github.io/govuk-design-history/introduction/#:~:text=A%20design%20history%20can%20help,the%20team%20and%20others%20leave.https:/) fast!
It is based on the practise of compiling a complex set of pages into a simple static page that techincal and non technical users can use alike. This solution is not suitable for Design / Decision historys that need to remain private. Github pages are public by nature.

This repository is based on the work of:-

* [Pages CMS for GitHub pages](https://github.com/pages-cms/pages-cms)
* [Jekyll blog](https://jekyllrb.com/)
* [Johnpearts GovLike Jekyll theme](https://github.com/johnpeart/GovLikehttps:/)

## How to setup this repo

This repository is designed to allow non technical users the ability to contribute to a GitHub site. However, there is a bit of a technical set up that must be undertaken first.

1. Create a new repository.
2. Copy this repository to your new repo and push to main.
3. On GitHub
   1. Head to the "Settings" tab
   2. Select "Pages" from the left side menu
   3. Set the Build and deployment section to GitHub Action, by default ti should detect a Jekyll project to build
   4. Commit a change to the repo to build the pages instant (Recomended Actions...)
      1. Have a look at the _config.yml and update all references that should relate to your repo
      2. Make sure base url is set to /{your repo name}
   5. Once the build action is complete, the pages should be assessable at https://{org}.github.io/{repo name}


## How to use the CMS

The following steps need to be taken to use the CMS

1. Make sure the user who needs to maintain or update the pages content has a GitHub account.
2. Make sure the user has edit permissions on the repo where the pages site is.
3. Direct the user to https://pagescms.org/ and ask them to log in with GitHub
4. Select the repository, this should be the same as the end of the GitHub repo url.
5. Happy blogging, the user should now have access to add and edit blog posts.
6. Any saved changes will take a couple of minutes to reflect via the GitHub site url.
