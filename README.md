# Pierre Orhan
**Pierre Orhan is a Phd in Neuroscience and artificial intelligence. He specializes in modeling the emergence of cognitive algorithms.**

[//]: # ()
[//]: # (![Academic Pages template example]&#40;images/homepage.png "Academic Pages template example"&#41;)

[//]: # ()
[//]: # (# Getting Started)

[//]: # ()
[//]: # (1. Register a GitHub account if you don't have one and confirm your e-mail &#40;required!&#41;)

[//]: # (1. Click the "Use this template" button in the top right.)

[//]: # (1. On the "New repository" page, enter your repository name as "[your GitHub username].github.io", which will also be your website's URL.)

[//]: # (1. Set site-wide configuration and add your content.)

[//]: # (1. Upload any files &#40;like PDFs, .zip files, etc.&#41; to the `files/` directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.)

[//]: # (1. Check status by going to the repository settings, in the "GitHub pages" section)

[//]: # (1. &#40;Optional&#41; Use the Jupyter notebooks or python scripts in the `markdown_generator` folder to generate markdown files for publications and talks from a TSV file.)

[//]: # ()
[//]: # (See more info at https://academicpages.github.io/)

[//]: # ()
[//]: # (## Running locally)

[//]: # ()
[//]: # (When you are initially working your website, it is very useful to be able to preview the changes locally before pushing them to GitHub. To work locally you will need to:)

[//]: # ()
[//]: # (1. Clone the repository and made updates as detailed above.)

[//]: # (1. Make sure you have ruby-dev, bundler, and nodejs installed)

[//]: # (    )
[//]: # (    On most Linux distribution and [Windows Subsystem Linux]&#40;https://learn.microsoft.com/en-us/windows/wsl/about&#41; the command is:)

[//]: # (    ```bash)

[//]: # (    sudo apt install ruby-dev ruby-bundler nodejs)

[//]: # (    ```)

[//]: # (    If you see error `Unable to locate package ruby-bundler`, `Unable to locate package nodejs `, run the following:)

[//]: # (    ```bash)

[//]: # (    sudo apt update && sudo apt upgrade -y)

[//]: # (    ```)

[//]: # (    then try run `sudo apt install ruby-dev ruby-bundler nodejs` again.)

[//]: # ()
[//]: # (    On MacOS the commands are:)

[//]: # (    ```bash)

[//]: # (    brew install ruby)

[//]: # (    brew install node)

[//]: # (    gem install bundler)

[//]: # (    ```)

[//]: # (1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.)

[//]: # ()
[//]: # (    If you see file permission error like `Fetching bundler-2.6.3.gem ERROR:  While executing gem &#40;Gem::FilePermissionError&#41; You don't have write permissions for the /var/lib/gems/3.2.0 directory.` or `Bundler::PermissionError: There was an error while trying to write to /usr/local/bin.`)

[//]: # (    Install Gems Locally &#40;Recommended&#41;:)

[//]: # (    ```bash)

[//]: # (    bundle config set --local path 'vendor/bundle')

[//]: # (    ```)

[//]: # (    then try run `bundle install` again. If succeeded, you should see a folder called `vendor` and open `.gitignore` then add `vendor` inside it.)

[//]: # ()
[//]: # (1. Run `jekyll serve -l -H localhost` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.)

[//]: # (    You may also try `bundle exec jekyll serve -l -H localhost` to ensure jekyll to use specific dependencies on your own local machine.)

[//]: # ()
[//]: # (If you are running on Linux it may be necessary to install some additional dependencies prior to being able to run locally: `sudo apt install build-essential gcc make`)

[//]: # ()
[//]: # (## Using Docker)

[//]: # ()
[//]: # (Working from a different OS, or just want to avoid installing dependencies? You can use the provided `Dockerfile` to build a container that will run the site for you if you have [Docker]&#40;https://www.docker.com/&#41; installed.)

[//]: # ()
[//]: # (You can build and execute the container by running the following command in the repository:)

[//]: # ()
[//]: # (```bash)

[//]: # (docker compose up)

[//]: # (```)

[//]: # ()
[//]: # (You should now be able to access the website from `localhost:4000`.)

[//]: # ()
[//]: # (# Maintenance)

[//]: # ()
[//]: # (Bug reports and feature requests to the template should be [submitted via GitHub]&#40;https://github.com/academicpages/academicpages.github.io/issues/new/choose&#41;. For questions concerning how to style the template, please feel free to start a [new discussion on GitHub]&#40;https://github.com/academicpages/academicpages.github.io/discussions&#41;.)

[//]: # ()
[//]: # (This repository was forked &#40;then detached&#41; by [Stuart Geiger]&#40;https://github.com/staeiou&#41; from the [Minimal Mistakes Jekyll Theme]&#40;https://mmistakes.github.io/minimal-mistakes/&#41;, which is © 2016 Michael Rose and released under the MIT License &#40;see LICENSE.md&#41;. It is currently being maintained by [Robert Zupko]&#40;https://github.com/rjzupkoii&#41; and additional maintainers would be welcomed.)

[//]: # ()
[//]: # (## Bugfixes and enhancements)

[//]: # ()
[//]: # (If you have bugfixes and enhancements that you would like to submit as a pull request, you will need to [fork]&#40;https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo&#41; this repository as opposed to using it as a template. This will also allow you to [synchronize your copy]&#40;https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork&#41; of template to your fork as well.)

[//]: # ()
[//]: # (Unfortunately, one logistical issue with a template theme like Academic Pages that makes it a little tricky to get bug fixes and updates to the core theme. If you use this template and customize it, you will probably get merge conflicts if you attempt to synchronize. If you want to save your various .yml configuration files and markdown files, you can delete the repository and fork it again. Or you can manually patch.)

[//]: # ()
[//]: # (---)

[//]: # (<div align="center">)

[//]: # (    )
[//]: # (![pages-build-deployment]&#40;https://github.com/academicpages/academicpages.github.io/actions/workflows/pages/pages-build-deployment/badge.svg&#41;)

[//]: # ([![GitHub contributors]&#40;https://img.shields.io/github/contributors/academicpages/academicpages.github.io.svg&#41;]&#40;https://github.com/academicpages/academicpages.github.io/graphs/contributors&#41;)

[//]: # ([![GitHub release]&#40;https://img.shields.io/github/v/release/academicpages/academicpages.github.io&#41;]&#40;https://github.com/academicpages/academicpages.github.io/releases/latest&#41;)

[//]: # ([![GitHub license]&#40;https://img.shields.io/github/license/academicpages/academicpages.github.io?color=blue&#41;]&#40;https://github.com/academicpages/academicpages.github.io/blob/master/LICENSE&#41;)

[//]: # ()
[//]: # ([![GitHub stars]&#40;https://img.shields.io/github/stars/academicpages/academicpages.github.io&#41;]&#40;https://github.com/academicpages/academicpages.github.io&#41;)

[//]: # ([![GitHub forks]&#40;https://img.shields.io/github/forks/academicpages/academicpages.github.io&#41;]&#40;https://github.com/academicpages/academicpages.github.io/fork&#41;)

[//]: # (</div>)
