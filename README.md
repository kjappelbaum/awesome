# **Awesome ChemInfo** [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A collection of awesome things for ChemInfo developers

- [Front-end](#front-end)
  - [State management](#state-management)
    - [immer](#immer)
  - [React](#react)
    - [draft-js](#draft-js)
    - [formik](#formik)
    - [nivo](#nivo)
    - [react-dropzone](#react-dropzone)
    - [react-fontawesome](#react-fontawesome)
    - [react-inspector](#react-inspector)
    - [react-mutable-context](#react-mutable-context)
    - [react-select](#react-select)
    - [react-window](#react-window)
    - [the-platform](#the-platform)
    - [use-immer](#use-immer)
- [Back-end](#back-end)
  - [Querying other servers](#querying-other-servers)
    - [got](#got)
  - [Buffer utilities](#buffer-utilities)
    - [crypto-md5](#crypto-md5)
    - [base64-js](#base64-js)
    - [fast-xml-parser](#fast-xml-parser)
    - [jszip]([jszip])
    - [node-gzip](#node-gzip)
    - [pako](#pako)
  - Sending email
    - [nodemailer](nodemailer)

## Front-end

### State management

#### [immer](https://github.com/mweststrate/immer)

Create the next immutable state by mutating the current one.

### React

#### [draft-js](https://github.com/facebook/draft-js)

A React framework for building text editors.

Draft.js is a JavaScript rich text editor framework, built for React and backed by an immutable model.

#### [formik](https://github.com/jaredpalmer/formik)

Build forms in React, without the tears.

#### [nivo](https://github.com/plouc/nivo)

nivo provides supercharged React components to easily build dataviz apps, it's built on top of d3.

#### [react-dropzone](https://github.com/react-dropzone/react-dropzone)

Simple HTML5-compliant drag'n'drop zone for files built with React.js.

#### [react-fontawesome](https://github.com/FortAwesome/react-fontawesome)

Font Awesome 5 React component

#### [react-inspector](https://github.com/storybookjs/react-inspector)

Advanced component allowing not only to inspect objects but also the DOM. Check the [storybook](https://react-inspector.netlify.com/?selectedKind=Numbers&selectedStory=positive&full=0&addons=1&stories=1&panelRight=0).

#### [react-mutable-context](https://github.com/targos/react-mutable-context)

Create a React context that can accessed and mutated with hooks.

#### [react-select](https://github.com/JedWatson/react-select)

The Select control for React.

#### [react-window](https://github.com/bvaughn/react-window)

React components for efficiently rendering large lists and tabular data

#### [the-platform](https://github.com/palmerhq/the-platform)

Web API's turned into React Hooks and Suspense-friendly React components.

#### [use-immer](https://github.com/mweststrate/use-immer)

A hook to use immer as a React hook to manipulate state.

## Back-end

### Sending email

#### [nodemailer](https://github.com/nodemailer/nodemailer)

Send quickly and easily emails from node

### Querying other servers

#### [got](https://github.com/sindresorhus/got)

Got is a human-friendly and powerful HTTP request library.

### Buffer utilities

#### [base64-js](https://github.com/beatgammit/base64-js)

Encode / decode base 64 using bytes array.

#### [crypto-md5](https://github.com/jtblin/crypto-md5)

Generates an md5 hash using node crypto module.
Equivalent to `crypto.createHash('md5').update(data).digest('base64');`.

#### [fast-xml-parser](https://github.com/NaturalIntelligence/fast-xml-parser#readme)

Validate XML, Parse XML to JS/JSON and vice versa, or parse XML to Nimn rapidly without C/C++ based libraries and no callback.

#### [jszip](https://github.com/Stuk/jszip#readme)

Allows to zip and unzip files with promises. Works
in Node.js as well as in the browser.

#### [node-gzip](https://github.com/Rebsos/node-gzip)

Simply gzip and ungzip in Node.js with promises.

#### [pako](https://github.com/nodeca/pako)

High speed zlib port to javascript, works in browser and Node.js.
