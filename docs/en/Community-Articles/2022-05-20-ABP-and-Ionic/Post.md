# Creating Mobile Apps using Ionic Framework and ABP Framework

## Introduction

In this article, we will create an example application which will use the [ABP Framework](https://www.abp.io) as backend for a mobile application which can run on an iOS or Andriod mobile device using [Ionic Framework](https://ionicframework.com).

Source Code of the completed application is avalibale on Github.

## Sreenshots

Here, is a preview of the Ionic App

## Requirements

If you haven't used ABP or Ionic Framework before you need to install and setup a few things. So lets get strated.

### Node.js

In order to install and run both ABP and Ionic Framework you first need to install the Node environment. You can either [download and install it from here](https://nodejs.org/en/) or if you are on Mac [use Homebrew to install it like described here ](https://blog.teamtreehouse.com/install-node-js-npm-mac).

To test your setup, you can run the following two commands on the your CL:

```bash
node -v

npm -v
```

Make sure you can open your command line and get a result for both of the commands. Your versions might be different at the time of installing it but that should be ok if you are up to date!

![Node Versions](../images/screen-shot-node-versions.png)

## Yarn

You will also need Yarn insalled for ABP Framework, you can install Yarn through the npm package manager which comes bundled with Node.js when you install it on your system. Ensure that it is Yarn v1.20+ not v2. ABP Framework doesn't support Yean v2

```bash
npm install -g yarn
```

Run the folowing command to check the version of Yarn.

![Yarn Version](../images/screen-shot-yarn-version.png)

### ABP CLI

you will also need to have the ABP CLI installed to create the startup template. ABP CLI is a command line insterface that is used to automate some common tasks for the ABP framework based solution.

In order to install the ABP CLI you will need an IDE such as [Visual Studio](https://visualstudio.microsoft.com/vs/) that uspports [.Net 6.0+](https://dotnet.microsoft.com/download/dotnet) installed

You can install it by running the following command on your CL:

```bash
dotnet tool install -g Volo.Abp.CLI
```

Once the ABP CLI is installed you can run the following command, at the time of writing this article, ABP Framework is at 5.2.2!



![ABP Version](..\images\screen-shot-abp-version.png)
