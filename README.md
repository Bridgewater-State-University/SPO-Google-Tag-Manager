# Google Tag Manager

## Introduction

This web part has been deployed online to BridgeNet and it is used to add Google Tag Manager to our SharePoint tenant. With Google Tag Manager, we have introduced Google Analytics to BridgeNet. GTM has also been used to inject a Siteimprove analytics script.

## Building the code

```bash
git clone the repo
npm i
npm i -g gulp
gulp
```

This package produces the following:

* lib/* - intermediate-stage commonjs build artifacts
* dist/* - the bundled script, along with other resources
* deploy/* - all resources which should be uploaded to a CDN.

## Build options

* gulp clean - TODO
* gulp test - TODO
* gulp serve - TODO
* gulp bundle - TODO
* gulp package-solution - TODO

## Change Log

Deployed to BridgeNet on January 14, 2021.
