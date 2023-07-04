## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/Kent-PHO/kent-pho.github.io/edit/main/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```r
# Use the mtcars dataset. This is built into R and should always be available
# View() function will create a new tab in Rstudio to browse and filter the 
# dataset. 
View(mtcars)

# The head() function prints the first six rows of every column in the console
# but it is possible to change this default behaviour
head(mtcars)
head(mtcars, n = 10)

# Check what class of object it is
class(mtcars)

# Check the structure
str(mtcars)

# Find out the how many rows and columns it contains using dim() function
dim(mtcars)

# Alternatively use nrow() and ncol()
nrow(mtcars)
ncol(mtcars)

# Create a summary output of each variable (or column)
# Note that summary() does not apply to the row names
summary(mtcars)

# View the distrubution of a numeric variable in a histogram
hist(mtcars$mpg)

# Add more breaks if required
hist(mtcars$mpg, breaks = 20)
```


```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

Download a [simple csv file](https://github.com/Kent-PHO/R-examples/blob/4a4a234578be01a9f88df7aa044502154dc3191a/simple_table.csv?raw=true)

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/Kent-PHO/kent-pho.github.io/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
