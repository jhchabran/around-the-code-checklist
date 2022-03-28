# around-the-code-checklist

A list of concepts, tools, domains to learn to become a better developer. 

## What is this about? 

When going through software engineering studies, there is a strong focus on learning to code. But coding is more than just writing code, it's about understanding the problems, making guesses about what tool to use, building your own workflow and building experience. A dear family member of mine who is going down the passionating path of software engineering is bombarding me with questions and I'm using this repository to track down various resources that can be useful to him. 

## Goal

The purpose of this list is not to bring an aspiring developer to an acceptable level, but rather to provide an opinionated set of expectations that can be used as a goal post to simply get better faster. Every point comes with a _why do I need to know this?_ paragraph, because understanding the purpose of a given advice is key to keep being motivated. 

## Workflow

### Git 

#### Why?

Using `git` efficiently is the cornerstone of a developer workflow. Friction due to not being comfortable around `git` commands will translate in creating fat commits with a lot of changes, which will then turn into big Pull Requests. Those are hard to review for others and will often take longer to be reviewed. 

Quoting a very experienced friend with 25 years of code under his belt, _If a PR is too large, the reality is that others will click on the review button after skimming through the code, because looking at 4000 lines being changed and being sure you did not miss anything is a myth_. Best case scenario, someone will just ask you to split it. Worst case scenario, it will be accepted without scrutiny. And in between lies the horrible scenario where the pull request will stay open for days and slowly become outdated. 

#### Goal 

The tool used to achieve this is irrelevant. While it's important to always be able to know how to do it with command line `git` commands, using your editor plugin for this, a UI tool or the command line does not matter. 

Every of those points must require nearly zero mental effort:

- [ ] Jumping around branches, fetching remote branches and creating new ones.
- [ ] Stashing your changes, 
- [ ] Resolving conflicts. 
- [ ] Rebasing branches. 
- [ ] Diffing commits across branches. 
