# Human-Centred Visual Learning Group Website

This is the website of our academic research group at the University of Birmingham.

A simple, clean, and responsive [Jekyll](https://jekyllrb.com/) theme for academics.
If you like the theme, give it a star!
## Getting started

For more about how to use Jekyll, check out [this tutorial](https://www.taniarascia.com/make-a-static-website-with-jekyll/).

### Step 1. Open with GitHub Desktop
If you want to change the content, please following:
1. Fork our github Repo.
2. Open code with GitHub Desktop. Please use the master branch.
3. Make any changes to your webpage, commit, and push.
4. Wait for a few minutes and let the action complete. You can see the progress in the Actions tab. If completed successfully, in addition to the `master` branch, your repository should also autonomously deploy the `gh-pages` branch.
5. Finally, make a pull requests. The webpage will become available at https://cvlab-uob.github.io/.

### Step 2. Local setup
If you want to pre-view the website when you edit it on your local computer, please following:

#### 1. Install Jekyll
Assuming you have [Ruby](https://www.ruby-lang.org/en/downloads/) and [Bundler](https://bundler.io/) installed on your system (*hint: for ease of managing ruby gems, consider using [rbenv](https://github.com/rbenv/rbenv)*). For Ubuntu/MacOS,

```bash
$ sudo apt install ruby-full ruby-bundler
$ sudo gem install bundler jekyll
$ jekyll -v
```
#### 2. View your website on your local computer

```bash
$ cd <your-repo-name>
$ bundle install
$ bundle exec jekyll serve
# => Now browse to http://localhost:4000
```
Now, feel free to edit the content.
After you are done, **commit** your final changes.
