# bookmarking is awesome but chrome's bookmark is fucked !
We have developed linktory extension because we think chrome's bookmark feature is not enoght.


The motivation behind creating linktory was:
1. to add more description than just a url when we are bookmarking a website.

2. being able to search among our bookmarks.

3. to create some lists of awesome links and share them among our friends and Colleagues.


## Features
- use [React Chrome Extension](https://github.com/satendra02/react-chrome-extension) boilerplate
- Used ReactJs to write chrome extension
- Injecting extension to host page as content script
- Utilized the Chrome messaging API
- Isolated extension CSS using Iframe

## Installation
>Make sure you have latest **NodeJs** version installed

Clone repo

```
git clone https://github.com/linktory/linktoryExtension.git
```
Go to `linktoryExtension` directory run

```
yarn install
```
Now build the extension using
```
yarn build
```
You will see a `build` folder generated inside `[PROJECT_HOME]`

To avoid running `yarn build` after updating any file, you can run

```
yarn watch
```

which listens to any local file changes, and rebuilds automatically.

## Adding React app extension to Chrome

In Chrome browser, go to chrome://extensions page and switch on developer mode. This enables the ability to locally install a Chrome extension.

<img src="https://cdn-images-1.medium.com/max/1600/1*OaygCwLSwLakyTqCADbmDw.png" />

Now click on the `LOAD UNPACKED` and browse to `[PROJECT_HOME]\build` ,This will install the React app as a Chrome extension.

When you go to any website and click on extension icon, injected page will toggle.

<img src="https://cdn-images-1.medium.com/max/1600/1*bXJYfvrcHDWKwUZCrPI-8w.png" />

## Contributing

Bug reports and pull requests are welcome on GitHub at https://github.com/linktory/linktoryExtension.git. This project is intended to be a safe, welcoming space for collaboration, and contributors are expected to adhere to the [Contributor Covenant](http://contributor-covenant.org) code of conduct.


## License

The repo is available as open source under the terms of the [GPL-3.0 License](https://opensource.org/licenses/GPL-3.0).
