# TaCos 2022 Website 
This is the website template for the 2022 `Tagung der Computerlinguistik Studierenden` in Düsseldorf. The template is a [Jekyll](https://jekyllrb.com/) event theme cloned from https://github.com/melvinchng/event-jekyll-theme. 

Checkout out LinkTree if you want to know more about us or the conference: https://linktr.ee/tacos2023.

## Website Documentation
Our documentation can be found in the Wiki of this repository.  
https://github.com/tacosConference/tacosConference.github.io/wiki/Basic-Website-Documentation 

## How to clone the website
**1. Check whether you have installed [Git](https://git-scm.com/).**

In the command line, type:
```sh
git --version
``` 
You know you have git installed when you see something like `git version 2.25.1`. If you don't, follow steps 1 and 2 in [this tutorial](https://docs.slam.phil.hhu.de/#/github_tut). For windows users, substitute the step that uses `sudo apt install git` with a download from [here](https://git-scm.com/download/win).

**2. Install the prerequisites for the website**
Follow the tutorial for your operating system [here](https://jekyllrb.com/docs/installation/#requirements) and check if you have NodeJS installed:
```sh
node --version
```
If not, install it with the corresponding installer for your operating system from [here](https://nodejs.org/en/download/). 

Finally, download Jekyll sitemap and Jekyll SEO gems.
```sh
gem install jekyll-sitemap
gem install jekyll-seo-tag
```
Should you encounter the error below when trying to install `jekyll-sitemap` you have to install ruby dev with `sudo apt install ruby-dev` for Linux/ Ubuntu (or look that up for Windows and Mac). 

```sh
gem install jekyll-sitemap
this error may appear

ERROR:  Error installing jekyll-sitemap:
        ERROR: Failed to build gem native extension.

    current directory: /var/lib/gems/3.0.0/gems/ffi-1.15.5/ext/ffi_c
/usr/bin/ruby3.0 -I /usr/lib/ruby/vendor_ruby -r ./siteconf20221123-802-zy3iwm.rb extconf.rb
mkmf.rb can't find header files for ruby at /usr/lib/ruby/include/ruby.h
```

**3. Clone the website**
In the command line, clone the website with the command below. It will be as new folder in the same folder that you run the command in. 
```sh
git clone git@github.com:tacosConference/tacosConference.github.io.git
```

You are done! :tada:
