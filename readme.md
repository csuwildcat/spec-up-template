# Spec-up Template Repo

This is a template repo that allows you to quickly begin creating a spec with Spec-Up. Here's what to do:

1. Clone the repo
2. Run `npm install`
3. Run `npm run edit`
4. Begin editing, and the tool will auto-generate your specs

NOTE: you may want to run something like [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code, the [Serve](https://www.npmjs.com/package/serve) Node.js package, or another auto-refreshing local file server to more easily view your rendered specs without having to manually refresh in your browser.

The repo contains two example specs:

1. Single-file spec - All spec text is contained in one markdown file, located in the `single-file-spec` folder.
2. Multi-file spec - Spec text is broken up into separate files for even greater source management control. These markdown files are located in the `multi-file-spec` folder.

You'll probably want to change the names of the folders these spec markdown source documents reside in, to better reflect whatever spec you are writing. If you do, just be sure to change the `spec_directory` field in the root `specs.json` file to ensure the tool knows where to look when generating your spec. You can learn more about the `specs.json` file and its configuration options within this general Spec-Up explainer: [Spec-Up Install and Configuration Explainer](https://github.com/csuwildcat/spec-up/blob/master/readme.md).


