# Hacking Historical Texts Final Project Template

{% include css.html %}

![Title Image]({{ site.baseurl }}/assets/images/intro-image.png)

## Instructor and Author

[David J. Thomas](mailto:dave.a.base@gmail.com), [thePortus.com](http://thePortus.com)<br />
Instructor of Ancient History and Digital Humanities<br />
Department of History<br />
[University of South Florida](https://github.com/usf-portal)

---

{% include nav.html %}

---

## Project Template

This is a starter template for final projects. When you have completed your final project, you should replace this message (README.md) with a short 1-2 paragraph description of your project.

See the [Course Workbook Project Page](https://theportus.github.io/hacking-historical-texts) for more information on the final project.

**REQUIREMENTS BEFORE STARTING**
+ [GitHub account](https://github.com) created
+ [Atom](https://atom.io) editor installed

---

## Files To Edit

```sh

# Intro pages, one for the repo, one for the site. You can make them identical
README.md # This is displayed on the GitHub repository page
index.md # This file, which is the homepage of your site

# Configuration and credit files. Edit with your team's info
_config.yml # Edit with your title/credit info, used when building site
CITATION.cff # A machine-readable citation file, edit with your info

# Where to put your own files
pages/*.md # The folder containing the rest of your pages (except index.md)
assets/images/ # Put your images here
assets/data/ # Put any data you want to include here (no files over 30mb)

```

---

## Launching the Site

To create the website from this repository, follow these steps...

1. Go to your repository homepage
2. Click the 'Settings' tab
3. Scroll down to the 'GitHub Pages' section
4. Under 'Source' click the dropdown menu and choose 'master branch'

**See your site at your-username.github.io/your-repo-name**

*(May take a few minutes)*

---

## Changing the Theme

To change the look of the website, follow these steps...

1. Go to your repository homepage
2. Click the 'Settings' tab
3. Scroll down to the 'GitHub Pages' section
4. Under 'Theme Chooser' click the dropdown menu
5. Follow on-page instructions to preview and select your theme

---

## Images, Files, and Linking

*Putting in an image*

```sh

# Make sure to put your image in the assets/images folder (or subfolder)
![Example Image]({{ site.baseurl }}/assets/images/example-image.png)

```

*Linking to Sample Data*

```sh

# Make sure your data file is in the assets/data folder (or subfolder)
[Display text]({{ site.baseurl }}/assets/data/example-data.csv)

```

*Linking to index.md*

```sh

# Make sure the page you link to is in the pages/ folder
[Display text]({{ site.baseurl }}/index.md)

```

*Linking to another site page that isn't index.md*

```sh

# Make sure the page you link to is in the pages/ folder
[Display text goes here]({{ site.baseurl }}/pages/put-your-page-name-here.md)

```

*Linking to an external page*

```sh

[Display text](https://www.put-your-link-url-here.html)

```

---

## Past Project Examples

* [Confederate Memorials](http://confederate-memorials-project.readthedocs.io/)
* [The Slave Ledges](http://slave-ledger.readthedocs.io/en/latest/)
* [An Teanga Sean: The Celtic Languages](http://an-teanga-sean-the-celtic-languages.readthedocs.io/)

---
