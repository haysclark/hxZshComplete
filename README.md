hxZshComplete
=============

zsh completion for haxe and it's tools

How to install
--------------

### Plain zsh

* Clone the repository:

```bash
$ git clone git://github.com/hxKraut/hxZshComplete.git ~/.hxZshComplete
```

* Run `make` and `make install`:

```bash
$ make
$ sudo make install
```

* Source the script from your `~/.zshrc`:

```bash
source ~/.hxZshComplete/haxe.zsh
export FPATH=($FPATH ~/.hxZshComplete
```

* Re-Source your `~/.zshrc` in every open terminal (or just restart them):

```bash
$ source ~/.zshrc
```

### With oh-my-zsh

(What is oh-my-zsh and where to get it?)

* Clone the repository into your omz-plugins-directory:

```bash
$ cd ZSH_CUSTOM/plugins
$ git clone git://github.com/hxKraut/hxZshComplete.git haxe
```

* Run `make` and `make install`:

```bash
$ make
$ sudo make install
```

* Activate the plugin in `~/.zshrc`:

```bash
plugins=(haxe [your other plugins without square brackets])
```

* Re-Source your `~/.zshrc` in every open terminal (or just restart them):

```bash
$ source ~/.zshrc
```

How to update
-------------

### Plain zsh

* Switch into the installation directory:

```bash
$ cd ~/.hxZshComplete
```

* Pull from master branch of the repo:

```bash
$ git pull origin master
```

* Run `make` and `make install`:

```bash
$ make
$ sudo make install
```

* Re-Source your `~/.zshrc` in every open terminal (or just restart them):

```bash
$ source ~/.zshrc
```

### With oh-my-zsh

* Switch into the installation directory:

```bash
$ cd ZSH_CUSTOM/plugins/haxe
```

* Pull from master branch of the repo:

```bash
$ git pull origin master
```

* Run `make` and `make install`:

```bash
$ make
$ sudo make install
```

* Re-Source your `~/.zshrc` in every open terminal (or just restart them):

```bash
$ source ~/.zshrc
```

How to contribute?
------------------

(TBD…)

# kitchen-zsh-plugin

`kitchen-zsh-plugin` is a zsh plugin for
[Test Kitchen](http://kitchen.ci/). This plugin can be installed into oh-my-zsh [custom plugin](https://github.com/robbyrussell/oh-my-zsh#customization) folder.

I did this plugin for fun, before I found the zsh-users version. I recommend you use that one instead of mine : https://github.com/zsh-users/zsh-completions/blob/master/src/_kitchen

## Installation for oh-my-zsh

1. In the command line, change to `oh-my-zsh` plugins directory:

    ```console
    $ take ~/.oh-my-zsh/custom/plugins
    ```

2. Clone the repository into a new directory called `kitchen`:

    ```console
    git clone https://github.com/pelletiermaxime/test-kitchen-zsh-plugin.git kitchen
    ```

3. Include `kitchen` plugin to your .zshrc file along with other plugins

4. Restart your terminal application.

## TODO

* Add driver subcommands.

## Additional information

* This is heavily based on the [vagrant zsh plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/vagrant/_vagrant)
* Caching code inspired by the [supervisor zsh plugin](https://github.com/robbyrussell/oh-my-zsh/blob/master/plugins/supervisor/_supervisorctl)
* This readme is based on the [berkshelf-zsh readme](https://github.com/berkshelf/berkshelf-zsh-plugin/blob/master/README.md)
