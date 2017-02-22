### Setup

1. Install [Node.js](https://learn.bevry.me/node/install)

1. Fork the project and clone your fork - [guide](https://help.github.com/articles/fork-a-repo/)

1. Install local dependencies

  ``` bash
  npm install
  ```


### Developing

1. Make your changes to the project

1. Run tests

	``` bash
	npm test
	```


### Publishing

Follow these steps in order to implement your changes/improvements into your desired project:


#### Preparation

1. Make sure your changes are on their own branch that is branched off from master.
  1. You can do this by: `git checkout master; git checkout -b your-new-branch`
  1. And push the changes up by: `git push origin your-new-branch`

1. Ensure all tests pass:

  ``` bash
  npm test
  ```

  > If possible, add tests for your change, if you don't know how, mention this in your pull request


#### Pull Request

To send your changes for the project owner to merge in:

1. Submit your pull request
  1. When submitting, if the original project has a `dev` or `integrate` branch, use that as the target branch for your pull request instead of the default `master`
  1. By submitting a pull request you agree for your changes to have the same license as the original plugin
