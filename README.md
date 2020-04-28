[![Netlify Status](https://api.netlify.com/api/v1/badges/5f205b3a-73c2-472c-b052-82b95bdf36b7/deploy-status)](https://app.netlify.com/sites/sleepy-bhabha-00eedf/deploys)

# Naiblog

![ Template Cover Image](https://i.imgur.com/uBwoT1T.png)

See the [demo here](http://naiblog.xyz/).

## What is it?

A template for Jekyll inspired by Netflix panel for who loves movies and series and would like to have a blog with the same  appearance.

![Jekflix Screenshot Image](https://i.imgur.com/qlTtP6m.png)

## Features

- Live Search
- Estimated Reading Time
- Reading Progress Bar
- "New Post" tag
- Load images on demand
- Push Menu
- SVG icons
- Shell script to create posts
- Tags page
- About page
- Contact page
- 404 error page
- Feed RSS
- Disqus
- Featured post
- Home page pagination 
- Posts sidebar
- Paginated posts
- "Before you go" modal
- Post recommendation
- Netlify CMS ready

## SEO

- Google Analytics
- Meta tags
- JSON-LD
- Sitemap.xml
- Social Media ready

## Setup

#### Environment

Before starting, make sure you have Ruby and NodeJS installed.

Then install Jekyll:

      $ gem install jekyll

And install Gulp client:

     $ npm install gulp-cli -g

#### Installing template

1. Fork the naiblog repo

2. Clone the repo you just forked:

        $ git clone https://github.com/<your-github-username>/naiblog.git

3. Access the local project:

        $ cd path/to/naiblog

4. Install npm packages:

         $ npm install

5. Install Ruby dependencies:

         $ bundle install

6. Build Jekyll:

         $ bundle exec jekyll build

7. Then run Gulp:

         $ gulp

#### Running local

After the steps above, to run Jekyll locally, you'll just need to run Gulp:

         $ gulp

#### Customization

Naiblog Template allows you to personalize your site with several settings. See the docs for more details.

For advanced theme customization, check the directory `_sass` for style files.


![](https://i.imgur.com/wIN8Nbf.png)

Special thanks to [Thiago Rossener](https://github.com/thiagorossener) for the site generator template

