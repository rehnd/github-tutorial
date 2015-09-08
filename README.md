# Github Tutorial

This tutorial is intended to help people get started with git and also
to give an idea for how development can be done in github.

The best resource for learning git is probably [https://git-scm.com/]

A side note is that a good overview of markdown syntax is here:
[https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet]

#### 1 Editing git settings 
The first thing to do is change your ```~/.gitconfig``` file. This can
be done by direct editing of the file or can be done by entering the
following in the command line:

```
$ git config --global user.name "Your Name"
$ git config --global user.email "your.email@server.com"
$ git config --global core.editor emacs
$ git config --global color.ui true
```

This will generate a file (```~/.gitconfig```) that looks like the following

```
[user]
	name = Your Name
	email = your.email@server.com
[core]
	editor = emacs
[color]
	ui = true
```

For more customization options, see
[https://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration](git-scm
customizations).

#### 2 Development on Github 
The file "github-tutorial.pdf" gives an overview of git features,
github features, and an example of a way to develop code in a decent
way.
