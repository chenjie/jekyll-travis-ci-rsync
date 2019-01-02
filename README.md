# jekyll-travis-ci-rsync
Deploy Jekyll website to both GitHub Page (gh-pages branch) and self-hosting Virtual Private Server using Travis CI and rsync command. 

## Quick Notes
The purpose of this repo is to give you an example of integrating Jekyll, GitHub and TravisCI. The example scripts and config files are based on a fantastic theme called minimal-mistakes, which can be found [here](https://github.com/mmistakes/minimal-mistakes). Notice that the theme itself also uses TravisCI to automate testing procedure, which is awesome. 

## Demo Site
[JellyBlog](https://nichenjie.com/) which is also open-sourced on GitHub.

## Main Refs
* A detailed [tutorial](https://www.rusiczki.net/2018/01/25/use-travis-to-build-and-deploy-your-jekyll-site-through-ssh/) written by János Rusiczki.
* Continuous integration config [procedure](https://jekyllrb.com/docs/continuous-integration/travis-ci/) documented by Jekyll team. `Very well-written and helpful!`
* Official docs from docs.travis-ci.com:
  - https://docs.travis-ci.com/user/deployment/pages/
  - https://docs.travis-ci.com/user/languages/ruby/
  - https://docs.travis-ci.com/user/encrypting-files/

## Other Refs
* If you want to use Git instead of rsync, please checkout [travis-jekyll-git](https://github.com/felixrieseberg/travis-jekyll-git).
* Or if you want to use FTP instead, please checkout [Ajay Karwal's blog post](https://ajaykarwal.com/deploying-jekyll-using-travis-ci/).

## License
[MIT](LICENSE)
