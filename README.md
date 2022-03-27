# web3-amazon-clone  🔥

# Welcome to straight-code

[🐦 Twitter](https://twitter.com/straight_code28)

[ℹ️ Website](https://straight-code.github.io)



This repo provides a nice and simple web3 amazon clone. There are two ways of using this repo, you can go the simple route or the more complex one.

The simple route is so simple, all you need to do is download the build folder on the release page and change the configuration to fit your needs. (Follow the video for a walk through).

The more complex route allows you to add additional functionality if you are comfortable with coding in react.js. (Follow the below instructions for a walk through).

## Installation 🛠️

If you are cloning the project then run this first, otherwise you can download the source code on the release page and skip this step.

```sh
git clone https://github.com/straight-code/web3-amazon-clone.git
```

Make sure you have node.js installed so you can use npm, then run:

```sh
yarn install
```

## Usage ℹ️

In order to make use of this dapp, all you need to do is change the configurations to point to your smart contract as well as update the images and theme file.

For the most part all the changes will be in the `src` folder.

To edit further, go to the `src/components/` file and update the following fields to fit your smart contract, network and marketplace details. The cost field should be in wei.

Note: you can change that in the App.js file if you need to use a smart contract 
After all the changes you can run.

```sh
yarn run start
```

Or create the build if you are ready to deploy.

```sh
yarn run build
```

Now you can host the contents of the build folder on a server.

That's it! you're done.

