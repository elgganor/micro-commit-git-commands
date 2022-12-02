# Micro-commits Git Commands

## Getting Started

### Prerequisites

To use these scripts, you need to have git installed on your machine and install the following packages:

#### diff-so-fancy
```sh
brew install diff-so-fancy
```

#### fzf
```shell
brew install fzf
```

### Installation

1. Clone this repository & cd into it
2. Copy the command files into your folder /usr/local/bin
```shell
cp ./commands/git-* /usr/local/bin
```
3. Make sure your folder /usr/local/bin is in your PATH environment variable

### Usage

1. Set the goal
```shell
git goal "commit message"
```
2. Save your progress when you validate your work (tests passed)
```shell
git save
```
3. Revert to a last known good state if you don't validate your work (tests don't pass)
```shell
git back
```
4. Squash your intermediate commits into your goal commit and push your code
```shell
git done
```

## Resources

If you want to learn more about micro-commits, you can read the articles:

https://world.hey.com/niko.heikkila/a-practical-guide-to-micro-commits-a37151eb

https://www.industriallogic.com/blog/whats-this-about-micro-commits/
