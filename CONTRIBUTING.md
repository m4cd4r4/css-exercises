# The Odin Project Contributing Guide

Thank you for expressing interest in contributing to The Odin Project (TOP)! Whether you are a first time contributor or you have made several contributions to our repos, please be sure to read this guide thoroughly before contributing as it will lessen the chances of any issues arising during the process.

**Please do not open an issue or pull request (PR) with your solutions to any exercise repo**. Your PR will be immediately closed without being merged. The exercise repos are for you to do and keep any work on your own local machine or your personal GitHub.

## Table of Contents
* [Curriculum Structure](#curriculum-structure)
* [Label Meanings](#label-meanings)
* [How to Contribute](#how-to-contribute)
   * [Repo Specific Instructions](#repo-specific-instructions)
   * [Check Before Doing Anything](#check-before-doing-anything)
   * [Being Assigned an Issue](#being-assigned-an-issue)
   * [Creating an Issue](#creating-an-issue)
   * [Setting Up Your Local Clone](#setting-up-your-local-clone)
   * [Working on an Issue](#working-on-an-issue)
   * [Opening a Pull Request](#opening-a-pull-request)
* [Further Help](#further-help)

## Curriculum Structure

Between our website, repos, and Discord server, you're bound to see certain terms being used in regards to the curriculum structure. It can be important to keep these terms in mind when referring or contributing to certain parts of our curriculum, both for consistency and to make sure everyone understands what you mean.

* **Path**: The broadest level of the curriculum structure. When you first start TOP, you will be on the Foundations path. Upon completion of Foundations, you choose one of two different Full Stack paths to continue down.
* **Course**: A path is made up of different courses. A course splits a path into more distinct topics, and each course has its own completion percentage. When asked what course you're on, you might say "I'm on the Getting Hired course!"
* **Section**: A course is made up of different sections. A section splits a course into even more distinct topics. When asked what section you're on, you might say "I just started the Basic Ruby section!"
* **Lesson**: Finally, a section is made up of different lessons. This is the most specific level of the curriculum structure. This is the exact thing you're currently on. When asked what lesson you're on, you might say "I'm reading through the Webpack lesson!"

## Label Meanings

The labels that get applied to issues and PRs in our repos have specific meanings and are broken into two categories: status and type. An issue/PR should only ever have one status label, but can have multiple type labels. The following isn't a complete list, but rather a list of the labels that are more universal across all of our repos.

### Status Labels
* **Abandoned**: This issue/PR has been abandoned and will not be implemented
* **Accepted**: This PR has been accepted and is able to be merged
* **Awaiting Changes**: Waiting for requested changes to be made by the contributor
* **Awaiting Response**: Waiting for a response from the contributor
* **Discussion**: This issue/PR has an ongoing discussion
* **Do Not Merge**: This PR should not be merged until further notice
* **Do Not Review**: This issue/PR should not be reviewed until further notice
* **Help Wanted**: This issue can be assigned to other contributors
* **In Progress**: This issue/PR has ongoing work being done
* **Invalid**: This issue/PR is invalid or is not relevant
* **Investigating**: Something in this issue/PR is being investigated
* **Needs Review**: This issue/PR needs an initial or additional review
* **On Hold**: There is a temporary hold on any continued work or review
* **Stale**: This issue/PR has been inactive for over 30 days and may be closed if inactivity continues
* **Under Review**: This issue/PR is being reviewed by at least one maintainer

### Type Labels
* **Accessibility**: Involves an accessibility feature or requires accessibility review
* **Bug**: Something isn't working as intended
* **Chore**: Involves changes to the build process or internal tooling
* **Documentation**: Involves an update to the documentation
* **Duplicate**: This issue/PR already exists
* **Easy Fix**: Involves a minor fix such as grammar, syntax, etc.
* **Enhancement**: Involves a new feature or enhancement request
* **Epic**: This issue is a larger, unnamed project with several moving parts
* **Good First Issue**: Good for beginner contributors
* **Hacktoberfest**: This issue is a good Hacktoberfest participation
* **Maintainer Only**: This issue is available only to maintainers
* **Priority**: This issue/PR should be resolved ASAP

## How to Contribute

The complexity of a change can determine how exactly you should go about contributing. Generally, simpler changes can just have an issue made or a PR created rather than needing to bring it up on our Discord server. Simple changes that you should feel free to just create an issue or PR for can include:

* Typo or grammar fixes - "I noticed that this sentence in this lesson is using incorrect grammar."
* Simple syntax errors - "This line of code is missing a closing element tag."
* Clarifying questions - "This lesson says to use this syntax, but in a previous lesson we were told to use a different syntax. Which is correct?"
* Other small-scale changes - "I think including an instruction about X could help minimize confusion at this step."

If you have a more complex suggestion or notice a more urgent issue, going to our [contribution-suggestions-bugs-discussions Discord channel](https://discordapp.com/channels/505093832157691914/540903304046182425) can be a great way to start a discussion or receive feedback. This channel can also be used to share a link to an issue or PR you have created if you haven't seen any activity on the actual issue/PR for a while, or to have a more real-time discussion. Just keep in mind that maintainers have busy lives - many with day jobs - and may not get to items on our repos immediately.

While you can also just create an issue on a repo for more complex or urgent changes rather than bring it up on our Discord, generally you should avoid doing work and opening a PR for such changes. Depending what the PR entails, it may not be something we're looking to implement at this time or is not how we wish to go about things, and we don't want all of that time and work going to waste. Changes that may be more complex or urgent can include:

* A complete rewrite of a lesson
* Adding a completely new lesson
* HTML in lessons is not displaying properly
* A new feature for the website

Regardless of the complexity of a change, when you wish to make a contribution on one of TOP's repos you must follow any further instructions in this guide.

### Repo Specific Instructions

#### [TOP Curriculum Repo](https://github.com/TheOdinProject/curriculum)

  If you're new to contributing to open-source, or if you just want to make a really quick PR, you can click the "Improve this lesson on GitHub" link found at the end of each lesson instead of going through the steps to fork + clone one of our repos.

  While working on an existing or a new lesson, you must follow our [Layout Style Guide](https://github.com/TheOdinProject/curriculum/blob/main/LAYOUT_STYLE_GUIDE.md) to ensure the layout and formatting is consistent across our curriculum.

  Before submitting a PR for an existing or a new lesson, you must use our [Lesson Preview Tool](https://www.theodinproject.com/lessons/preview) to ensure the lesson Markdown is correctly formatted and rendering properly.
  
<hr>

#### [TOP Website Repo](https://github.com/TheOdinProject/theodinproject)

Before starting any work on our main website repo, you must read and follow the instructions found on [The Odin Project Wiki](https://github.com/TheOdinProject/theodinproject/wiki). These instructions will help you get the TOP app running locally, and help you with adding new paths, courses, sections, and lessons.

### Check Before Doing Anything

It's important that you look through any open issues or PRs in a repo before attempting to submit a new issue or work on a change, regardless of the complexity. This will help avoid any duplicates from being made, as well as prevent more than one person working on the same thing at the same time.

If your proposal already exists in an open issue or PR, but you feel therer are details missing, comment on the issue/PR to let those involved know of those missing details.

### Being Assigned an Issue

If you would like to work on an existing issue in a repo:

1) Find an issue that is not currently assigned to anyone.
    * A couple of good places to start are issues with the `Status: Help Wanted` or `Type: Good First Issue` labels. You can filter the issues list to only show ones with these (or any) specific labels to make them easier to find.
    * You can also filter out any issues with the `Status: In Progress` label, so that you only see issues that haven't been assigned to anyone.

2) Ask to be assigned the issue by a maintainer.
    * **If you are not a maintainer, do not give others permission to work on an issue**

3) **Wait to be assigned the issue before starting any work**.

4) After being assigned, address each item listed in the acceptance criteria, if any exist.
   * If an issue doesn't have any acceptance criteria, feel free to go about resolving the issue however you wish. You can also ask the maintainer that assigned you the issue if there are any specific acceptance criteria.

### Creating an Issue

1. If you would like to make a simple change that is not part of an existing issue, you are welcome to skip the next step and just submit a PR with your proposed change(s).

2. Create a new issue and **read the issue template in its entirety and fill out all applicable sections**. If you aren't sure how to create an issue, you can read the GitHub documentation on [creating an issue from a repository](https://docs.github.com/en/issues/tracking-your-work-with-issues/creating-an-issue#creating-an-issue-from-a-repository).
   * The title of the issue should follow a format similar to `file, exercise/lesson, or folder: brief description of issue`. This makes it easier for anyone to quickly see what an issue is for, reducing the possibility of a duplicate issue from being made.
   * If you would like to be assigned the issue you are creating, complete the applicable checkbox in the issue template. Note that this does not guarantee that you will be assigned the issue, but rather it lets maintainers know that you are interested.

### Setting Up Your Local Clone

Before you begin working on anything, make sure you follow these steps in order to set up a clone on your local machine:

1. Fork this repo to your own GitHub account. If you don't know how to do so, follow the GitHub documentation on how to [fork a repo](https://docs.github.com/en/get-started/quickstart/fork-a-repo).

2. Clone this repo to your local machine with one of the commands below. Be sure the `<your username>` text is replaced with your actual GitHub username, and the `<repo name>` with the actual repo name. You can also read the GitHub documentaiton on [cloning a repository](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository).

    ```bash
    # If you have SSH set up with Git:
    git clone git@github.com:<your username>/<repo name>.git
    # Otherwise for HTTPS:
    git clone https://github.com/<your username>/<repo name>.git
    
    # An example:
    git clone git@github.com:Odinson/css-exercises.git
    ```

3. `cd` into the directory of your local clone, then set the upstream remote so you can keep your local clone synced with TOP's original repo. The `<repo name>` below should be the same as the one you used when creating your local clone in the previous step.

    ```bash
    # If you have SSH set up with Git:
    git remote add upstream git@github.com:TheOdinProject/<repo name>.git
    # Otherwise for HTTPS:
    git remote add upstream https://github.com/TheOdinProject/<repo name>.git
    
    # An example:
    git remote add upstream https://github.com/TheOdinProject/css-exercises.git
    ```

### Working on an Issue

Once you have the repo forked and cloned, and the upstream remote has been set, you can begin working on your issue:

1. Create a new branch, replacing the `<your branch name>` with an actual branch name:

    ```bash
    git checkout -b <your branch name>
    
    # An example:
    git checkout -b flex_exercises
    ```

2. Add commits as you work on your issue, replacing the `<your commit message>` text with your actual commit message:

   ```bash
   git commit -m "<your commit message>"
   
   # An example:
   git commit -m "Update solution files"
   ```

3. Sync your work with the upstream remote every so often. Follow the [ongoing workflow](https://www.theodinproject.com/paths/full-stack-ruby-on-rails/courses/ruby-programming/lessons/using-git-in-the-real-world#ongoing-workflow) instructions in our Using Git in the Real World lesson.

4. Push your branch to your forked repo, replacing the `<your branch name>` with the branch you've been working on locally:

    ```bash
    git push origin <your branch name>
    
    # An example:
    git push origin flex_exercises
    ```

5. Preview your proposed changes by locally opening any applicable HTML files (or using VS Code's Live Server extension). If the preview matches the existing "Desired Outcome" image(s) for the exercise, continue to open a pull request. Otherwise, update any images in your local clone and commit + push those changes before opening a pull request.

### Opening a Pull Request

1. After pushing your changes, go to your forked repo on GitHub and click the "Compare & pull request" button. If you have multiples of this button, be sure you click the one for the correct branch.
   * If you don't see this button, you can click the branch dropdown menu and then select the branch you just pushed from your local clone:
   
      ![GitHub branch dropdown menu](https://user-images.githubusercontent.com/70952936/150646139-bc080c64-db57-4776-8db1-6525b7b47be2.jpg)
   
   * Once you have switched to the correct branch on GitHub, click the "Contribute" dropdown and then click the "Open pull request" button.

2. **Read the PR template in its entirety before filling it out and submitting a PR**. Not filling out the template correctly will delay a PR getting merged.
   * If a checkbox is not required and is not applicable to your PR, do not complete it. If your PR isn't related to an open issue, for example, you shouldn't complete the checkbox for linking an issue.
   * The title of the PR should follow the format described in the PR template, which is usually some variation of `file, exercise/lesson, or folder: brief description of changes`. This makes it easier for anyone to quickly see what a PR is for, reducing the possibility of a duplicate PR from being made.
   * Be sure you describe the change(s) you are proposing in more detail in Step 1 of the PR template. If the PR is not related to an open issue, you should also include why your proposed changes are beneficial or what problem(s) it solves. This gives maintainers the information to consider when deciding whether a PR should be merged.
   * If the PR is related to an open issue, be sure to link that issue in Step 2 of the PR template. This can be done either by replacing the `XXXXX` with the issue number, e.g. `Closes #2013`, or if the issue is in another TOP repo replacing the `#XXXXX` with the URL of the issue, e.g. `Closes https://github.com/TheOdinProject/curriculum/issues/XXXXX`. This streamlines the issue closing process, as an issue that is linked to a PR will be closed when that PR gets merged.

3. At this point a maintainer will either leave general comments, request changes, or approve and merge your PR.
   * It is important to respond to any comments or requested changes in a timely manner, otherwise your PR may be closed without being merged due to inactivity.
   * After pushing any requested changes to the branch you opened the PR with, be sure to re-request a review from the maintainer that requested those changes at the top of the right sidebar:

      ![Reviewers section of GitHub's sidebar](https://user-images.githubusercontent.com/70952936/150647064-4fdd59d1-82a4-4f18-894d-0e43a5ee0ffb.jpg)


## Further Help
Please let us know if you require any further help with any of the steps in this guide in our [contribution-suggestions-bugs-discussions Discord channel](https://discordapp.com/channels/505093832157691914/540903304046182425).
