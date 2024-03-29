<p align="center">
  <img alt="Phunt" src="assets/header.png"/>
  <a href="https://www.producthunt.com/posts/phunt?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-phunt" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=47632&theme=dark" alt="Phunt - Product Hunt command line interface | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a><br>
  <a href="https://github.com/vorpaljs/awesome-vorpal" target="_blank">
    <img src="https://awesome.re/mentioned-badge.svg">
  </a>
</p>

# PHUNT

[![asciicast](https://asciinema.org/a/33953.png)](https://asciinema.org/a/33953)

## Installation

```cli
npm i -g phunt
```


## Usage

```cli
$ phunt
@username => help
```

For the first time, you are required to enter your **Developer Token** (**NOT API key/secret**) (see [FAQ](#faq)).

## Commands

- [x] `me` (Get current user)
- [x] `me posts` (See all posts created by current user)
- [x] `me products` (See all posts made by by current user)
- [x] `posts` (Get the tech posts of today)
- [x] `posts {category}` Get the posts of today (for given category)
- [x] `posts new` (Get all the newest posts)


## FAQ

**Access Token**

1. Create new account on [ProductHunt](https://www.producthunt.com).
2. [Add an application](https://www.producthunt.com/v1/oauth/applications).
3. Generate static Developer Token.
4. Your token can be found at the bottom of page.
