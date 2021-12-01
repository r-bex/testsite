## What is this

I am learning how to make a basic static blog site with Eleventy.

## Dev

Working this out still but I think...

1. have nodeJS and npm installed
2. clone this repo and cd into it
3. run `npm install --only=dev` to install dev dependencies
4. run `npx @11ty/eleventy --serve` to serve the site at localhost:8080
5. make changes and run `rm -r _site && npx @11ty/eleventy --serve` to clear the site HTML and rebuild
