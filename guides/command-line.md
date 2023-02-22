### Setting up your macOS command line

#### Homebrew

The first thing I like to do is to install [Homebrew](https://brew.sh/), an open-source package manager for Macs. I install almost everything through Homebrew—utilities, dev tools, applications, etc., as we'll see in a bit.

1. Launch Terminal (don't worry, we'll install the much better [iTerm2](#iterm2) later).
2. Install Homebrew with curl.

   ```shell
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

3. Make sure everything is up to date.

   ```shell
   brew update
   ```

#### iTerm2

Next, let's set up [iTerm2](https://iterm2.com/), a replacement for the pre-installed Terminal. This is, of course, optional, but iTerm2 comes packed with [so many more features](https://apple.stackexchange.com/questions/25143/what-is-the-difference-between-iterm2-and-terminal) that most people prefer it over Terminal.

1. Install iTerm2 with brew.

   ```shell
   brew install --cask iterm2
   ```

2. Go to `iTerm 2` in the menu bar and select `Make iTerm2 Default Term`.
3. Go to `iTerm2 > Preferences` in the menu bar.
   - Under `General > Window`, disable Adjust window when changing font size.
   - Under `Appearance > General`, set Theme to Minimal.
   - Under `Profiles > Default > Text > Font`, set the font size to 15.
   - Under `Profiles > Default > Keys > Key Mappings`, select the Natural Text Editing preset.
4. Go to `iTerm 2` in the menu bar and select Install Shell Integration.

#### Git

#### Prezto

#### Vim

#### exa

#### tere

#### tldr
