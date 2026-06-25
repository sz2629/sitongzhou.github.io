mac install ruby and package install  jekyll

[Set up Ruby, Bundler and a project-level Jekyll on macOS Catalina and up](https://gist.github.com/MichaelCurrin/61053a564bdb3098bae11f949bab3578)
[Homebrew](https://brew.sh/)
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

 echo >> /Users/sitongzhou/.bash_profile
    echo 'eval "$(/opt/homebrew/bin/brew shellenv bash)"' >> /Users/sitongzhou/.bash_profile
    eval "$(/opt/homebrew/bin/brew shellenv bash)"
brew install ruby@3.3

[Creating a GitHub Pages site](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)
https://github.com/sz2629/sitongzhou.github.io/settings/pages
 /opt/homebrew/lib/ruby/gems/3.3.0/bin
(base) MacBook-Pro-653:~ sitongzhou$ which ruby
/opt/homebrew/bin/ruby

gem install jekyll
gem install bundler
