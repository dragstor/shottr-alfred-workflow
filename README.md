# Alfred Workflow for Shottr

This is a simple Alfred workflow for the [Shottr](https://shottr.cc) screenshot app for macOS. It allows you to utilize the Shottr URL Schema to take screenshots without using the Shottr app directly.

## Installation

1. Download the latest release from the [releases](https://github.com/dragstor/shottr-alfred-workflow/releases) page
2. Double click the downloaded file to install the workflow in Alfred
3. Open Alfred and type `ss` to see the available commands

## Usage

The available keywords ones are:

| Keyword  | URL Schema                          | Additional parameters                      |
|----------|-------------------------------------|--------------------------------------------|
| sstr     | `shottr://show`                     |                                            |
| ssfs     | `shottr://grab/fullscreen`          |                                            |
| ssa      | `shottr://grab/area`                |                                            |
| ssw      | `shottr://grab/repeat`              |                                            |
| ssrg     | `shottr://grab/window`              |                                            |
| sss      | `shottr://grab/scrolling`           |                                            |
| sssr     | `shottr://grab/scrolling/reverse`   |                                            |
| ssds     | `shottr://grab/delayed`             |  add a number [1..10]  for custom delay, e.g. `ssds 7`    |
| ssap     | `shottr://grab/append`              |                                            |
| sso      | `shottr://ocr`                      |                                            |
| ssc      | `shottr://load/clipboard`           |                                            |
| ssf      | `shottr://load/file`                |                                            |
| ssu      | `shottr://uploads`                  |                                            |

💡 When starting the workflow via `ss`, Alfred sorts the commands by the most used.

💡 You can change this to the default order like this:
1. Open Alfred
2. Click the "Workflows" from the sidebar menu
3. Choose "Shottr.cc" from the list
4. Double-click the "Choose a tool" List Filter
5. Choose the "Keep results in order defined in the table" option from the last dropdown
6. Click the "Save" button

## License

This project is licensed under the GPL3 License - see the [LICENSE](LICENSE) file for details

## Contributing

If you have any ideas or if you find a bug, just open an issue and tell me what you think. 

If you'd like to contribute, please fork the repository and make changes as you'd like. Pull requests are warmly welcome.

## Acknowledgments

- A huge thanks to Max from Shottr for the excellent app, and for sharing the URL Schema and the app icons 🙌🏻

  