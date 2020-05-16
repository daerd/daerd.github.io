# daerd.github.io

[The code of my user page](https://github.com/daerd/daer) in Github Pages was meant to be here, but Github only allows project pages to be loaded from branches different than master, and I don't think using another one to work with the development code is a good idea. For that reason I decided to host my code in another repo and load it as a project page, and redirect to it from here.

> [https://help.github.com/en/github/working-with-github-pages/about-github-pages](https://help.github.com/en/github/working-with-github-pages/about-github-pages)

> The default publishing source for user and organization sites is the master branch. If the repository for your user or organization site has a master branch, your site will publish automatically from that branch. You cannot choose a different publishing source for user or organization sites.

Having this repo pointing to the other one is really useful to be able to load [daerd.github.io](https://daerd.github.io) from [my custom domain](https://www.daer.dev) via DNS CNAME record. Its bigger contra is showing the name of the other repo in the URL, but that can be solved using [window.history.pushState](window.history.pushState) in it.
