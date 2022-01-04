# Building Monorepos on GitHub
This is the repository for the LinkedIn Learning course Building Monorepos on GitHub. The full course is available from [LinkedIn Learning][lil-course-url].

![Building Monorepos on GitHub][lil-thumbnail-url] 

If you’re a developer or system administrator, you’re always looking for easier and more collaborative ways to manage a large codebase for your organization. That’s where monorepos come in. They allow you to manage code for many projects on a single repository. In this course, instructor Carlos Solís teaches you how to build and host monorepos on GitHub, streamlining your entire workflow and boosting collaboration across your team.

Discover how monorepos can help you reduce complexity, avoid code dependencies, and improve cross-functional collaboration. Learn more about this powerful tool for managing multiple projects from one centralized point. Find out how to build, manage, and deploy monorepos on GitHub, exploring best practices, tools, and techniques to scale your enterprise with this exciting piece of architecture.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"


### Instructor

Carlos Solís 
                            


                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/carlos-solis).

[lil-course-url]: https://www.linkedin.com/learning/building-monorepos-on-github
[lil-thumbnail-url]: https://cdn.lynda.com/course/3000667/3000667-1640196242098-16x9.jpg
