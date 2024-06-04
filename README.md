# Code-Conventions

## Rules of Commit-ment

### Branches
 - **The branch names must begin with the jira issue code
    - **Don't:**
       - ❌ Title: Cleaning Code
    - **Do:**
       - ✅ Title: HS-1234 Cleaning Code
### Pull Requests
 - **Pull requests name must begin with the jira issue code
    - **Don't:**
       - ❌ Title: Cleaning Code
    - **Do:**
       - ✅ Title: HS-1234 Cleaning Code
 - **Maximum time alloted for verifying a PR is 5 minutes. If it goes beyond that, it will be rejected.**
 - **The PR itself must contain all the necessary information/direct links to said information to gage**
    - What is being adressed ( before ).
    - What are the desired end results ( after ).
 - **The scope of the PR must be clear and concise.**
    - **Don't:**
       - ❌ Title: Cleaning Code
       - ❌ Title: Design Improvements
       - ❌ Title: Tos privacy change
    - **Do:**
       - ✅ Title: Removing commented code from the User Dashboard
       - ✅ Title: Fix for bug #...
       - ✅ Title: Implement feature X.
          - Description: Feature: [url]
 - **Use proper english because pull request titles will show in release notes. And release notes will
   be sent to clients.**
    - ❌ Title: ads Subscription Title as standalone component
    - ✅ Title: **Added** subscription title as standalone component
  
 - **Use sentence capitalization case.**
    - ❌ Title: ~~d~~esign changes to the API user page
    - ❌ Title: ~~f~~aq changed according to new design
    - ✅ Title: **S**how affiliate manager email to resellers
 - **Write the title and description from your own perspective, do not humanize the PRs.**
    - ❌ Title: ~~ads~~ subscription title as standalone component
    - ✅ Title: **Added**```(Short for I have added)``` subscription title as standalone component
    - 

## Laravel 
### Must use npm plugins
 - https://tailwindcss.com/blog/automatic-class-sorting-with-prettier

### Must use settings
 - 4 spaces for indenting
 - to be decided formatter
