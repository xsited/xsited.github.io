# About the website

#### This site is based on "Clean Blog" by Start Bootstrap - Jekyll Version

The official Jekyll version of the Clean Blog theme by [Start Bootstrap](http://startbootstrap.com/).

#### [View Live Demo &rarr;](http://blackrockdigital.github.io/startbootstrap-clean-blog-jekyll/)

# About posts

The `_posts` folder is where your blog posts will live. These files are generally Markdown or HTML format.



### How to add a post

To create a new post, all you need to do is create a file in the `_posts` directory. How you name files in this folder is important. Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. For example, the following are examples of valid post filenames:

`2011-12-31-my-new-post.md` <br />
`2012-09-12-dont-use-spaces-between-words.md`

# Update sections

### Customization

If you want to edit certain sections like header, footer, google-analytics you can change the code in these files
- `_includes/header.html`
- `_includes/nav.html`
- `_includes/ga.html`

Update the fields in `_config.yml ` such as email according to your liking.

Use `<amp-img>` tag instead of `<img>` tag(see the post for example) and specify attributes alt,width and height

WARNING: Do not add any javascript file or code, it will make the page AMP incompatible.

### site generation

`_site` dir is generated when you run jekyll, it converts all the liquid-tags, frontmatter, markdown, scss of files into simple html, css which is recognized by the web browsers and puts them in the `_site` dir. As you can see there is a index.md in the root folder which contains three dashes at the top and bottom the content inside it is called frontmatter and inside it we have specified certain info about that page refer these pages to get familiar.

### github pages and Jekyll


To create a github-pages repo use the instructions given in this doc https://pages.github.com/ and for more information on jekyll refer this jekyll docs https://jekyllrb.com/docs/home/ .


### preview a branch
If you want to download the branch run these commands (for linux terminal) <br />
git clone https://github.com/username/reponame.git <br />
cd reponame <br />
git checkout master  `(for changing branch)`<br />
jekyll serve `(for Running jekyll)`<br />
now open browser and go to 127.0.0.1:4000 to see the website. <br />

To push the changes:-<br />
git add --all<br />
git commit -m "commit message"<br />
git push origin master
