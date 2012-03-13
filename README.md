# rbenv-init-project

Scratch all the itches. rbenv init-project is a silly plugin to setup rbenv
scaffolding for local development projects. I got tired of typing `echo blah > .rbenv-gemsets` as
well as `echo <rubby-version> > .rbenv-version`. This will setup a gemset
named for the cwd using the "global" version of ruby as defined by rbenv.

I have plans to make it more flexible, but it works for now.

## Work flow

  * create project
  * cd to project directory
  * rbenv init-project
  * do work, son

## Installation

    $ mkdir -p ~/.rbenv/plugins
    $ cd ~/.rbenv/plugins
    $ git clone git@github.com:benjaminws/rbenv-init-project.git
