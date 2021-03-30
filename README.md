## Usage

First clone this repository to your laptop. You must have Node (> v4) and [yarn](https://yarnpkg.com/lang/en/docs/install) installed.

```sh
cd ~/code/<your_github_nickname>
git clone git@github.com:lewagon/webpack-boilerplate.git ajax101
cd ajax101
rm -rf .git
yarn install
stt # open this folder in Sublime Text
# or
code . # open this folder in VSCode
```

Make sure you have `./node_modules/.bin` in your `$PATH` (check your `~/.zshrc`!). This way you can run a local server with:

```sh
webpack-dev-server
```

and check your code style with:

```sh
eslint src
```
