# rt-mbp14inch-making-it-work
Document getting my work aka MZLA mbp14inch A2779 working for me :-) #ymmv
## 2023-09-08
* 1\. unboxing - it turns on when you open the lid?!?
* 2\. `brew install frum`
* 3\. `brew install libyaml`
* 4\. `brew install libtool`
* 5\. `sudogem uninstall psych`
* 6\. ruby 3.2.2 shenanigans
```bash
sudo gem install psych -- --with-libyaml-dir=$(brew --prefix libyaml)
export RUBY_CONFIGURE_OPTS=--with-libyaml-dir=$(brew --prefix libyaml)
```
