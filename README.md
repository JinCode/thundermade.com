# Thunder Made LLC Company Website
## Description
This is the company website for Thunder Made LLC. It is a static website built with Hugo and Bootstrap. It is hosted on github pages and uses a custom domain name. The website is served on https://thundermade.com.

## Development
### Prerequisites
- [Hugo](https://gohugo.io/getting-started/installing/)

### Project Structure
- all code is in the themes/thunder-made-theme directory, because we are utilizing the [Hugo Module System](https://gohugo.io/hugo-modules/)
- DO NOT MODIFY the docs directory, it is automatically generated by hugo


### Running the site locally
1. Clone the repository
2. Run `hugo server -D` from the root directory

### Deploying the site
1. Run `hugo` from the root directory
2. Commit and push the changes to the master branch

### To Do
- [ ] add all required images to static/images
- [ ] style the header in partials/header.html
- [ ] style the footer in partials/footer.html
- [ ] style the home page in layouts/_default/home.html
- [ ] style the products page in layouts/products/list.html
- [ ] style the blogs page in layouts/blogs/list.html
- [ ] style the blog page in layouts/blogs/single.html
- [ ] style the contact-us page in layouts/_default/contact-us.html