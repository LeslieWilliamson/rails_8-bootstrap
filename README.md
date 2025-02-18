# README

I was able to successfully integrate bootstrap into a new Rails 8 project using the instructions found in this [document](
https://dev.to/jessalejo/create-a-new-rails-72-project-with-bootstrap-theme-on-a-newly-set-up-wsl-in-minutes-4p6#:~:text=Create%20a%20New%20Rails%20Project%201%20Application%20Structure%3A,esbuild%20%28-j%3Desbuild%29%3A%20Configures%20esbuild%20as%20the%20JavaScript%20bundler. )

Some additional steps to cleanup my ***WSL*** environment
* uninstall npm 
* uninstall node
* uninstall yarn

```
sudo apt-get remove yarn && sudo apt-get purge yarn
sudo apt-get remove nodejs
sudo apt-get remove npm
sudo apt autoremove
```

## Things I Learned

* [Node version manager - nvm](https://github.com/nvm-sh/nvm)
* [Node package manager - npm](https://nodejs.org/en/learn/getting-started/an-introduction-to-the-npm-package-manager)
* [Node.js ](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs)
* [Javascript package manager - yarn](https://classic.yarnpkg.com/lang/en/docs/)
* [Ruby version manager - rvm](https://rvm.io/)
* [Ruby package manage - RubyGems](https://rubygems.org/)
* [Ruby 3.3 official documentation](https://docs.ruby-lang.org/en/3.3/)
* [Ruby release 3.3.7](https://www.ruby-lang.org/en/news/2025/01/15/ruby-3-3-7-released/)
* [Ruby Bunlder](https://bundler.io/)
* [Rails 8.0.1](https://guides.rubyonrails.org/)
* [Working with Javascript in Rails](https://guides.rubyonrails.org/v7.0.7/working_with_javascript_in_rails.html)
* [Javascript bundling](https://dev.to/sayanide/the-what-why-and-how-of-javascript-bundlers-4po9)
* [CSS Bundling for Rails](https://github.com/rails/cssbundling-rails)
* [Difference between apt-get and apt](https://www.howtogeek.com/791055/apt-vs-apt-get-whats-the-difference-on-linux/)
* [Github writting and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Understanding bin/dev and Procfile.dev](https://railsnotes.xyz/blog/procfile-bin-dev-rails7)
* [Automate security updates for Ubuntu](https://linuxize.com/post/how-to-set-up-automatic-updates-on-ubuntu-18-04/)


## CSS Frameworks

CSS frameworks are collections of pre-written CSS files and sometimes JavaScript components that offer reusable code for common design elements. They provide a set of predefined classes and rules, streamlining the development process by offering a foundation of reusable CSS styles for common elements such as buttons, grids, forms, and navigation menus.

- [List of Awesome CSS Frameworks](https://github.com/troxler/awesome-css-frameworks)
- [Best CSS Frameworks](https://prismic.io/blog/best-css-frameworks)
- [Syntactically Awesome Style Sheets - SASS](https://sass-lang.com/)
