# bun-buildpack
This is a heroku buildpack for [bun](https:///bun.sh).

This was mostly made to work with Next.js and similar framework that build the app before "serving" it.

What it does:
* It detects bun on it's `bun.lockb` file.
* install dependencies with `bun install`
* run an build run task with `bun run -b build`
* run a server with `bun run -b start`
