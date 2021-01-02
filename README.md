# Persona 5 & Royal Negotiation Guide

A tool to help with negotiations in Persona 5 and Persona 5 Royal. 

Direct link to a user-friendly version: http://joyce-chen.github.io/persona5-negotiation/

If you want to contribute any changes or confirm some results, please use the [open issue for P5 Royal](https://github.com/joyce-chen/persona5-negotiation/issues/16), the [open issue for P5](https://github.com/joyce-chen/persona5-negotiation/issues/17), or [the form](https://forms.gle/JtH9YUekRKVEkYgc6). Thank you!

Submitted questions are up-to-date as of **November 24th**. (No consistent update schedule.)


---

August 10th: 
- Added a dark mode.
- Added icon labels to the text/icon toggle for both question pages.
- Used local storage to keep toggle state.
- Made tables responsive for small screens.


TODOS:
- Organize the filters to show all the questions for pools of Shadows.
- Show corresponding personality only when filtering by Persona.
- Organize Shadows by level instead.
- Make and merge PRs from other users that forked this repo.


---

Thank you to all the people who contributed by making PRs!

Thank you to GooberSD/Chompobar for all the additional questions and answers they were able to collect in their playthrough and giving me permission to use that data to update this guide. [GooberSD/Chompobar's Google Docs Guide](https://docs.google.com/document/d/1Fq00lkODNAam7RZoczHU2kFyU3CZvyW59F0PwLnJoz8/)

## Building and Running Locally

This site is built with Jekyll and deployed with Github Pages. Dependencies are managed via Bundler.

To run the site locally:

> ⚠️ [Ruby](https://www.ruby-lang.org/en/documentation/installation/) must be installed in your local development environment.

### 1. Install Jekyll
See the [Jekyll install docs](https://jekyllrb.com/docs/installation/) for detailed instructions.

### 2. Install bundler
See the [Bundler install docs](https://bundler.io/#getting-started) for detailed instructions.

### 3. Clone the repository
In your terminal:

```
$ git clone https://github.com/joyce-chen/persona5-negotiation.git
```

### 4. Install dependencies
In your terminal:

```
$ cd persona5-negotiation # if you haven't already
$ bundle install # Installs dependencies listed in Gemfile
```

### 5. Run the app
In your terminal:

```
# The --livereload flag will cause the site to reload automatically when you
# change any of the source files.
$ bundle exec jekyll serve --livereload
```