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

Things worth knowing:

* [Difference between apt-get and apt](https://www.howtogeek.com/791055/apt-vs-apt-get-whats-the-difference-on-linux/)
* [Github writting and formatting syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [Understanding bin/dev and Procfile.dev](https://railsnotes.xyz/blog/procfile-bin-dev-rails7)
* [Automate security updates for Ubuntu]((https://linuxize.com/post/how-to-set-up-automatic-updates-on-ubuntu-18-04/))
