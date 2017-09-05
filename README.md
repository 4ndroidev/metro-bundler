# rocket-bundler

[![npm version](https://badge.fury.io/js/rocket-bundler.svg)](http://badge.fury.io/js/rocket-bundler)

🚀 The JavaScript bundler for React Native.

- **🚅 Fast**: We aim for sub-second reload cycles, fast startup and quick bundling speeds.
- **⚖️ Scalable**: Works with thousands of modules in a single application.
- **⚛️ Integrated**: Supports every React Native project out of the box.

This project was previously part of the [react-native](https://github.com/facebook/react-native) repository. In this smaller repository it is easier for the team working on Rocket Bundler to respond to both issues and pull requests. See [react-native#13976](https://github.com/facebook/react-native/issues/13976) for the initial announcement.

usage: 

node node_modules/rocket-bundler/src/cli.js bundle \
	--dev false \
	--platform android \
	--entry-file index.android.js \
	--bundle-output output/index.android.bundle \
	--base-file base.js \
	--base-output output/base.bundle \
	--assets-dest output/ \
	--sourcemap-output output/sourcemap.txt
