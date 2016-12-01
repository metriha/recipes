<p align="center">
  <img src="bin/cake.png" alt="Recipes for UNI logo"/>
</p>

<h1 align="center">Recipes for UNI :cake:</h1>

<p align="center">
  <a href="https://github.com/uni-linux/uni"><img src="https://img.shields.io/badge/get-uni-green.svg" alt="get uni"/></a>
  <a href="https://github.com/uni-linux/recipes/blob/master/LICENSE"><img src="https://img.shields.io/github/license/mashape/apistatus.svg" alt="License - MIT"/></a>
</p>

> This is the main recipes repository for [UNI](https://github.com/uni-linux/uni).<br/>
> You can create your own or use one of the available recipes in here.

> Recipes are bash scripts to do anything. Be it to install programs and resolve dependencies or fix system problems. Anything you want and can do with bash scripts.

# Available Recipes
- [atom-install](https://github.com/uni-linux/recipes/tree/master/src/daltonmenezes/atom-install)<br/>
  Installs the latest version of Atom Editor from their official website and resolve dependency issues.

# Contributing

As I said, recipes are bash script files. You can do anything you want.

So, if you want create your own recipes and publish it here you must:
- Fork this repository!
- Create your feature branch: git checkout -b my-new-recipe
- Take [this template](https://github.com/uni-linux/recipes/tree/master/src/uni/template) as a base and keep a title, description and usage in your README.md file. The `uni bake` command will search in: `your-user-folder-name/your-recipe-folder-name`
- Create a folder in `/src/` named with your github user name and create a separated folder inside it for each recipe created by you
- Commit your changes: git commit -m 'Add user-name/recipe-name recipe'
- Push to the branch: git push origin my-new-recipe
- Send your pull request.

After your pull request is merged, you can safely delete your branch.

If you have doubt yet about how to create recipes, just take a look [in here](https://github.com/uni-linux/recipes/tree/master/src) and check how the things works.
