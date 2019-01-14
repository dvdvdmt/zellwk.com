# Introduction

This is a repo for zellwk.com. I open-sourced this repo because I wanted to share my code. **Please note:** I may write [dirty code](https://zellwk.com/blog/write-dirty-code) in this repo. Do not copy everything blindly!

## Installation

1. Clone this repo
2. Run `npm install`

## Using this repo

For development work, you need to run two commands at the same time:

1. `npm run server`: Runs Node server
2. `npm run dev`: Compiles and serves statically generated site

## Development

1. All source files can be found in `src` directory.
2. This repo uses [Eleventy](https://github.com/11ty/eleventy) to generate the static site

## Deployment

1. This project uses [Circleci](https://circleci.com) for continuous deployment. Look at [.circleci/config.yml](.circleci/config.yml) for the configuration.
2. For manual deploy, run `npm run deploy`.

## Contributing

Feel free to file a PR if you want to help improve this project :)
