# Intro to collaborative coding

#### Tip: this is a markdown file. It uses a set of [symbols](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) to allow rapid formatting of the document. You can use a text editor or a specialised markdown editor (such as [Remarkable](https://remarkableapp.github.io/)).

## About

This is not meant to be a guide to programming. It's also not meant to be a definitive guide to *Python*, *testing*, *version control* or any other topic mentioned here.

This is meant to be a collection of *examples* and *links* to hopefully spark off some discussion of important aspects of **collaborative scientific coding** for new students in the [Orengo lab](www.orengogroup.info).

The intention is for students to document their answers in [their own fork](https://help.github.com/articles/fork-a-repo/) of this project.

Notes on the questions below:

 * These questions do not have a single correct answer
 * Hopefully your answers will improve as you get more experience
 * Try and answer in your own words

Feel free to copy and paste quotes from elsewhere (with links to the original source). By the end of your project you will hopefully be able to answer the questions in your own words from a position of experience (which is far more valuable).

## Contents

### 1. How to get help

 1. What does a bad question look like?
    * **Answer:** my _X_ is not working, what do I do?
 1. What does a good question look like?
    * **Answer:** my _X_ does _Y_ instead of _Z_. How do I fix it?
 1. Typical sources of information. 
	*  **Answer:** [Google](https://www.google.co.uk/?gws_rd=ssl), [stack overflow](https://stackoverflow.com/), dedicated subreddit, known experts on the subject
 
### 2. Version control

 1. why is this important?
 	* **Answer:** being able to always have a working/presentable version of a code/thing is crucial. Tracking bugs is easier since you can check when X stopped working.
 1. when should it be used?
 	* **Answer:** if there is a change in the code that affect the result in any noticeable way/if it took you longer than 5 minutes to make the change.
 1. what does a [basic git flow](https://www.atlassian.com/git/tutorials/comparing-workflows) look like? (and [more complex flows](http://nvie.com/posts/a-successful-git-branching-model/))
 	*  A:
 1. what does a "good" commit look like?
 	* [Tips for good commit msgs.](https://robots.thoughtbot.com/5-useful-tips-for-a-better-commit-message) 
 1. have a go (fork this repo, fill in your own answers)
 	* [Tips for forking and branching](http://blog.scottlowe.org/2015/01/27/using-fork-branch-git-workflow/)

### 3. Testing 

 1. why is testing important?
 	* A
 1. specifically to programming in a scientific environment? 
 	* A
 1. how can testing be implemented?
 	* A
 1. when should it happen?
 	* A
 1. what is TDD? (key aspects? why is it useful?)
	* [TDD with Python](https://code.tutsplus.com/tutorials/beginning-test-driven-development-in-python--net-30137) 
	* [Unittest from Python 2 Official](https://docs.python.org/2/library/unittest.html)
 1. what is CI? (key aspects? why is it useful?)
 	* A
 1. what is benchmarking? how is it different to testing?
 	* Benchmark is concerned with performance.
https://gist.github.com/sloria/7001839

https://www.python.org/dev/peps/pep-0008/

https://github.com/seanfisk/python-project-template

### 4. DRY

 1. what does it mean?
 	* "[Don't repeat yourself](https://en.wikipedia.org/wiki/Don%27t_repeat_yourself)"
 1. why is it important?
 	* Code/Data integrity (Refer to data integrity.) That means less reduandency and less prone to random mutations.
 1. how does this idea translate into code?
 	* A
 1. are there any exceptions where you might want to ignore this? (hint: *dependencies*)
	* Overhead of dependency and copyright problem.

### 5. Organisation

 1. where's your data? tests? libraries? scripts?
 	* [Constructing python modules (Official doc)](https://docs.python.org/2/tutorial/modules.html#packages)
 1. documentation
	 * Document at different levels. 
 1. why? where? who is it for? (hint: *you in X months time*)
 	* A
 1. different types of documentation
	* A
 1. considering maintenance
	* 
 1. how to encourage good documentation?
	* A
 1. Deployment:
	https://gist.github.com/sloria/7001839

	https://www.python.org/dev/peps/pep-0008/

	https://github.com/seanfisk/python-project-template

  
### 6. Runtime debugger

