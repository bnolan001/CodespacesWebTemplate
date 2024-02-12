# CodespacesWebTemplate

Provides the basic configuration to launch a GitHub Codespace environment ready for HTML, CSS, and JavaScript coding. The project will spin up a Codespace with the following plugins:

- [Prettier](https://github.com/prettier/prettier-vscode)
- [LiveServer](https://github.com/ritwickdey/vscode-live-server)
- [GitDoc](https://github.com/lostintangent/gitdoc)

The **Prettier** plugin helps format your code to a consistent style. The **LiveServer** plugin will launch a local web server to host your web pages. The server will automatically refresh the page when you save your changes.  the **GitDoc** plugin allows you to automatically commit and push your changes to your repository on a periodic basis.  To enable the **GitDoc** plugin you will need to go to update the Settings configuration for it.

## Configuration

### GitDoc
GitDoc is a great extension to automatically commit and push changes into the repository.  For developers who are just getting started with web development, configuring this extension to automatically save their changes can make the introduction into git version control a much less intimidating experience.  Because the extension cannot be configured by default to automatically push the changes up to the repository, users will need to update the settings the first time they launch project in Codespaces.
1. 
