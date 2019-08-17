## GSoC 2019: Debun tool
![Hex](https://img.shields.io/badge/gsoc-syslog--ng-blue.svg)

### General Info
- Name: Mehul Prajapati
- Github: [mehul-m-prajapati](https://github.com/mehul-m-prajapati)
- Email: mehul.encs@gmail.com
- Organization: [syslog-ng](https://github.com/balabit/syslog-ng)
- Mentor: [Kókai Péter](https://github.com/Kokan)
- Draft Proposal: [Improve-Debun-tool-collected-information](https://github.com/balabit/syslog-ng/wiki/GSoC-2019-Proposal%3A-Improve-Debun-tool-collected-information-%28Mehul-Prajapati%29)


### Project overview
Syslog-ng is a highly scalable logging application, which is used collect logs fromvarious sources (such as applications, files) on a centralized log server and allows to process them with parsers, filters, and specialized modules before saving/sending them. The syslog-ng-debun tool is distributed with the syslog-ng OSE application.


### Project Abstract
The syslog-ng-debun tool collects and saves information about your syslog-ng OSE installation, making troubleshooting easier, especially if anyone is concerned about syslog-ng OSE related issues. The goal of this project is to improve the current debun tool by adding new features and developing tests.


### Tasks
|No.|Description|PR|
|:---|:---|:---|
|1| Save the active config | [PR #2752](https://github.com/balabit/syslog-ng/pull/2752)|
|2| find properties files listed in syslog-ng config | [PR #2782](https://github.com/balabit/syslog-ng/pull/2782)|
|3| Create a new type for file path into grammar search | [PR #2797](https://github.com/balabit/syslog-ng/pull/2797)|
|4| Collect internal logs with possibly higher log level | [PR #2840](https://github.com/balabit/syslog-ng/pull/2840)|
|5| syslog-ng-ctl: new command list-files to fetch files from configuration | [PR #2797](https://github.com/balabit/syslog-ng/pull/2797)|
|6| Debun: Collect all files in config which have absolute path | WIP |
