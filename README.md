# Starter-Quarto-Website

### What is this starter website and Quarto?

The point of this website is as a more "feature rich" template.

The main [Quarto website](https://quarto.org/) is also feature rich, and a good source of insipration, but I thought it would be easier to have this website as a starting point, so you can copy this website to your own repo as explained below, as explained below, to get a more feature rich website out of the blocks.

Quarto is the most recent website creation tool, but has risen to become one of the most popular, in large part due to the team making it who are very popular.

It is a website template tool, so you write in markdown (with a YAML header) and then you make Quarto render your markdown files into the website's HTML.

You can publish this website using GitHub pages, or on other platforms, see [here](https://quarto.org/docs/publishing/index.html).

Quarto turns your Markdown files into HTML files, the format of which can be tweaked by the optional associated YAML header, telling Quarto how to decorate the webpages.

The YAML header controls the layout of the page. On each page in the template there will be a </> button. This reveals what the underlying Markdown+YAML source file is pre-Quarto conversion into HTML, to satisfy your curiousity.

### Quick way to get your own website!:

1. Fork this repo (in the top right)

2. Go into the settings of your new website repo, and find the settings for "Pages" (probably on the middle left)

  Under build and deployment, select branch=main and folder=/docs.

  Then your website should go live.

  Your settings page should look like this:

  ![github pages settings](https://user-images.githubusercontent.com/22969230/213680688-a73472b9-612e-4309-9dcf-c565af6afa09.png)

### How to edit:

For all the information on how to get started, go to [Quarto.org](https://quarto.org/).

In short:

1. Download Quarto and then download your github repo containing your website to your local computer.

  Then you can edit the markdown files in a markdown (.md / .qmd) or notebook (.ipynb) editor of your choice.

2. Convert the markdown files into the HTML files, using Quarto. 

  Run "quarto render the_file_path_of_your_website_directory" in a terminal (or use the shortcut in VS Code / Jupyter Notebook if you have the relevant Quarto extension).

  Now your local HTML files are updated, by Quarto, based on your Markdown files.

3. Push this local repository back up to the GitHub repository where your github pages website is stored. 

### Advanced:

You can also add javascript into your Quarto webpage, linked through the YAML header, to customise the webpage further. See [here](https://quarto.org/docs/reference/formats/html.html#includes).

### Useful links

[Setting up Git and GitHub](https://www.codecademy.com/article/f1-u3-git-setup)
[Quarto Guide](https://quarto.org/)

### Your Website Link

GOOD idea to change this link, to have your website URL here for easy access, for others and yourself.

[website URL](website URL)
