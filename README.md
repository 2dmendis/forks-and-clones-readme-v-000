# Forks and Clones

## Objectives

1. Fork a repo
2. Clone a repo
3. Push to different remote repos


##Forking a Github Repository
Forking a Github repository is just a way to create your own copy of any other Github repo. We do this all the time while using Learn, so you can use your copy as a sandbox to play around while maintaining a canonical repo where the original lab remains intact. In other words, it creates another remote that allows you to work in your own world without having to mess with our learn-co-student stuff.

You can fork any repo by clicking the "Fork" button at the top right of any Github repository. Learn also makes it very easy by allowing you to click "Fork This Lab" directly from Learn. It's also worthwhile to note that you can go to your fork by switching the learn URL with your Github username. For example:

```
https://github.com/learn-co-students/first-lab-001-prework-web
```
Change "learn-co-students" to your username:
```
https://github.com/your-username-here/first-lab-001-prework-web
```

![Fork Button](http://readme-pics.s3.amazonaws.com/fork_button.jpg)

[More on forking at the Github docs.](https://help.github.com/enterprise/2.2/user/articles/fork-a-repo/)

##Cloning
Now we want to get our forked copy of the repository on our local machine. This is where cloning is useful. To do this:

1. Find your forked repo on your Github profile
2. Make sure you select `SSH` as your URL type

  ![SSH URl](https://s3.amazonaws.com/learn-verified/ssh)
  
3. Click the "Copy to clipboard" button like the one below. This will copy the URL for us to use when we clone.

	![Clone Repo Button](http://readme-pics.s3.amazonaws.com/clone-repo-clone-url-button.png)

4. In the terminal, let's run our clone command. It takes the URL we just copied as an argument:

	```bash
	git clone your-github-url
	```
	This will create a local copy of the repository that corresponds to the URL.

<p data-visibility='hidden'>View <a href='https://learn.co/lessons/forks-and-clones-readme' title='Forks and Clones'>Forks and Clones</a> on Learn.co and start learning to code for free.</p>
