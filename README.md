# CLI for live-streaming your local dev environment

Scrimba is a next-generation screen sharing for developers. Download our npm pagkage and you'll be able to:
* **Live stream** your local dev environment to a URL
* **Collaborate** in real-time while discussion via voice chat
* **Keep a recording** of the session so that you can re-watch it whenever you want

![](https://i.imgur.com/hDwDZ4l.png)

## Quick-start
```
# install the CLI
$ npm -g install scrimba
# navigate to your project
$ cd my-awesome-project
# start a live stream
$ scrimba start
```

This opens your project as a _scrim_ in your browser. In this _scrim_, you'll have access to your files, your terminal and a small browser window (which can point to e.g. localhost or external websites).
You can then share the URL with anyone, so that they can join in on your session. They'll be able to both interact with your code, and to talk with you via audio chat.

Note: you'll have to be logged into Scrimba in order to start a live-streaming session.

## Features

* Codebase, terminal and browser sharing
* Real-time collaboration
* Multiple mouse pointers
* Voice chat
* Up to 4 participants
* Record sessions

## Feedback

This is an experimental feature, and you're likely to encounter bugs. Please report any bugs, quirks, or invconveniences to us via our [Slack group](https://scrimba.slack.com/), as it'll help us improve the experience. We'd also love to hear any suggestions you might have.

## Limitations
* Currently only works with Google Chrome

## Troubleshooting

If you have trouble installing scrimba without sudo, read up on [fixing-npm-permissions](https://docs.npmjs.com/getting-started/fixing-npm-permissions)

```
prebuild-install WARN install EACCES: permission denied, mkdir '/path/to/node_modules/node-pty-prebuilt/build'

# If you really need to install with sudo, and get the error above, install using --unsafe-perm:
sudo npm install -g scrimba --unsafe-perm


```

[Scrimba](https://scrimba.com:9000/@welcome) let's you live-stream your local dev environment to a URL. Share the link it with a colleague and you'll be able to collaborate in real-time while discussing via voice chat. You can also record the session and re-watch it whenever you want.
