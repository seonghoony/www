# About this repository

This is a public repository, forked from [sfreytag/friday-theme](https://github.com/sfreytag/friday-theme). The website is hosed on my homelab. Please refer to [https://www.shjeong.net/](https://www.shjeong.net/).

# Installation

```bash
# install ruby, jekyll

sudo apt-get install ruby-full build-essential zlib1g-dev -y
echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc

# download this repository
git clone https://github.com/seonghoony/www
cd www
gem install jekyll bundler

# run this repository
bundle exec jekyll serve --host 0.0.0.0
```