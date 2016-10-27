# PHUNT

Product Hunt Command Line Client

[![asciicast](https://asciinema.org/a/33953.png)](https://asciinema.org/a/33953)

## Requirements

- Node.js

## Installation

```cli
npm i -g phunt
```


## Usage

1. Create new account in [ProductHunt](https://www.producthunt.com/) (if you dont have it).
2. Generate applications API in [here](https://www.producthunt.com/v1/oauth/applications).
Application name and redirect_url value doesn't matter.
3. Generate static Developer Token, the link can be found in bottom of page.
4. Start application. When starting for the first time, enter your Developer Token NOT API key/secret.

```cli
$ phunt
@username => help
```


## Commands

- [x] `me` (Get current user)
- [x] `me posts` (See all posts created by current user)
- [ ] `me products` (See all posts made by by current user)
- [x] `posts` (Get the tech posts of today)
- [x] `posts {category}` Get the posts of today (for given category)
- [ ] `posts new` (Get all the newest posts)
  -
