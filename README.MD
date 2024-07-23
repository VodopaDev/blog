# The Blog
Welcome to the code/config for my personal blog.  

The tech stack is kept as simple as possible by known tech stack such as the [Hugo](https://gohugo.io/) static-website generator with the [hugo-profile](https://github.com/gurusabarish/hugo-profile/tree/master) theme, and a GitHub Actions pipeline to build the static files and deploy  host on GitHub pages (with redirect from my custom domain).  

Some additional changes where applied to the hugo-profile theme to harmonize styling and remove unnecessary elements. Bootstrap and fontawesome SVGs were also trimmed from repo files to rely on CDNs and dynamic resource loading.

# How to build
1. Install [Hugo](https://gohugo.io/installation/)
2. Clone the repo
3. Run `hugo server -D`
4. Open `http://localhost:1313`
