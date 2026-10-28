<p align="center">
  <a href="https://cloudmorrow.com"><img src="https://raw.githubusercontent.com/Cloudmorrow/.github/main/profile/assets/morrow.png" width="260" alt="Morrow, the hedgehog, sitting on his own cloud"></a>
</p>

<h1 align="center">Keep your data. Change the software.</h1>

<p align="center">
  <b>Cloudmorrow is a cloud you install on hardware you own.</b><br>
  Your data stays on your machine, encrypted, in standard shapes every app agrees on.<br>
  The apps around it, called Quills, you pick, change and throw away as your needs change.
</p>

<p align="center">
  <a href="https://cloudmorrow.com">Website</a> ·
  <a href="https://cloudmorrow.com/install">Install</a> ·
  <a href="https://cloudmorrow.com/quills">Quill Catalog</a> ·
  <a href="https://cloudmorrow.com/datamodels">Datamodels</a> ·
  <a href="https://cloudmorrow.com/resources/developers">Build a Quill</a> ·
  <a href="https://cloudmorrow.com/donate">Donate</a>
</p>

<p align="center">
  <img src="https://raw.githubusercontent.com/Cloudmorrow/cloudmorrow/main/docs/images/desktop-tasks.webp" width="49%" alt="Tasks in a desktop browser: three lanes beside a sidebar of Quills">
  <img src="https://raw.githubusercontent.com/Cloudmorrow/cloudmorrow/main/docs/images/tui-tasks.webp" width="49%" alt="The same board in the terminal app">
</p>
<p align="center"><sub>One Quill, Tasks, on two of its surfaces. Nobody wrote two screens: the Quill describes one, and the phone, the browser, the terminal, the command line and your assistant all draw it.</sub></p>

## One command

On a Linux machine, a Raspberry Pi, an old laptop or any VPS:

```sh
curl -fsSL https://raw.githubusercontent.com/Cloudmorrow/cloudmorrow/main/deploy/install-server.sh | sudo sh
```

A few questions, and it is running. Open it in a browser, add it to your phone's home screen, and put `cm` on your computers. The whole story is at [cloudmorrow.com/install](https://cloudmorrow.com/install).

## The repositories

| | |
| --- | --- |
| [**cloudmorrow**](https://github.com/Cloudmorrow/cloudmorrow) | The server, the web app, the terminal app and the agent. One Python service. |
| [**quill-catalog**](https://github.com/Cloudmorrow/quill-catalog) | Every published Quill, by shelf. A server reads it; a pull request adds to it. |
| [**datamodels**](https://github.com/Cloudmorrow/datamodels) | The shapes every Quill agrees on: tasks, contacts, calendars, files, messages. |
| [**quill-template**](https://github.com/Cloudmorrow/quill-template) | Start a Quill of your own: a manifest, a datamodel, a CLAUDE.md and a CI check. |

## The Quills

Each one is a repository of its own, free under the AGPL. ★ marks the foundation: offered and ticked on a fresh server.

| Quill | What it does | Shelf |
| --- | --- | --- |
| [CutMorrow](https://github.com/Cloudmorrow/quill-cutmorrow) | A video editor for the videos in your drive: cut, trim and arrange clips on video and audio tracks, blur what should not be seen, crop, and export. | Personal |
| [Files](https://github.com/Cloudmorrow/quill-files) ★ | Your own drive on the server, your fileshares, and what is in them. | Personal |
| [Media](https://github.com/Cloudmorrow/quill-media) | Every photo and video in your drive, as pictures: filter them and give them stars. | Personal |
| [Notes](https://github.com/Cloudmorrow/quill-notes) ★ | Markdown notes in folders, with pictures: plain files in the Notes folder of your drive. | Personal |
| [Calendar](https://github.com/Cloudmorrow/quill-calendar) ★ | Your own calendar, the ones you share, and one for everybody. | Productivity |
| [Cells](https://github.com/Cloudmorrow/quill-cells) | Small spreadsheets: cells, numbers and formulas, worked out the same on the phone, the web, the terminal and the command line. | Productivity |
| [Docs](https://github.com/Cloudmorrow/quill-docs) | Documents, a basic Word with headings, lists, tables and styles, over .docs files and Word's own. | Productivity |
| [Tasks](https://github.com/Cloudmorrow/quill-tasks) ★ | Boards with three lanes: To Do, Doing, Done. | Productivity |
| [Channels](https://github.com/Cloudmorrow/quill-channels) ★ | Channels, threads, mentions and reactions: a team's conversations, on your own server. | Communication |
| [CRM](https://github.com/Cloudmorrow/quill-crm) | Customers for a company: organisations, people, a pipeline of deals, and what to do next. | Business |
| [DevProject](https://github.com/Cloudmorrow/quill-devproject) | Your software projects: the repository, notes, a board, and the .env secrets on every machine. | Developer |
| [Secrets](https://github.com/Cloudmorrow/quill-secrets) ★ | Keys and passwords in vaults and environments, sealed, and never shown until you ask. | Developer |

Want one that does not exist yet? Describe it to an assistant: `cm quill new` and [the developer handbook](https://cloudmorrow.com/resources/developers) are what it needs. A Quill says what data it will touch before it is installed, has no UI code of its own, and takes its screens with it when it goes.

<p align="center"><sub>Free software under the <a href="https://www.gnu.org/licenses/agpl-3.0.html">GNU AGPL v3</a>. Started and looked after by BramLabs in Vordingborg, Denmark, and open to anyone who wants to help.</sub></p>
