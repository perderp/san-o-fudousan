# san-o-fudousan



Sanno Real Estate to support those who are looking for commercial land and commercial land in Shiga Prefecture and those who want to make effective use of unused land


##### Table of Contents

- [Prerequisites](#Prerequisites)
- [Installing san-o-fudousan](#Installing)
- [Usage of san-o-fudousan](#Usage)
- [Contributing to san-o-fudousan](#Contributing)
- [Additional Info](#Additional)
  - [Breakpoints](#Breakpoints)
  - [Errors](#Erros)
- [Acknowledgements and References](#Acknowledgements)
- [Credits](#Credits)
- [Contribute](#Contribute)

## <a name='Prerequisites'></a> :pushpin: Prerequisites

Before you begin, ensure you have met the following requirements:

- You have a `Windows 10` machine.

| Tool | Version | Description                                                                                  |
| ---- | ------- | -------------------------------------------------------------------------------------------- |
| Node | > 14.9.0  | Install node version via [NVM](https://github.com/coreybutler/nvm-windows/releases/tag/1.1.7) |

## <a name='Installing'></a> :rocket: Installing san-o-fudousan

To install san-o-fudousan in your local machine, run this following script in your terminal:

**Windows**:

```sh
git clone -b [your_branch] https://github.com/perderp/san-o-fudousan
```

## <a name='Usage'></a>:computer: Usage of san-o-fudousan

To begin the development, follow this steps listed below:

1. go to **`src/`** folder
2. run **`npm install`**
3. after the dependencies installed, run **`gulp build && gulp sync`**

##### Code Block:

```sh
cd src
npm install
gulp build
gulp sync
```

:warning: Note: Make changes only in **`src/`** folder.

## <a name='Contributing'></a> :memo:Contributing to san-o-fudousan

Before cloning, create a [new branch](https://github.com/perderp/san-o-fudousan) for your local development.

To contribute to san-o-fudousan, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## <a name='Additional'></a> :paperclip: Additional Info

Additional information about san-o-fudousan.

- ### <a name='Breakpoints'></a>Breakpoints

  san-o-fudousan has a specified breakpoints on respective platforms:

  | Platform | Breakpoints   |
  | -------- | ------------- |
  | PC       | 769px up      |
  | tablet   | 481px - 768px |
  | Mobile   | 480px below   |

- ### <a name='Errors'></a>Errors

  If you encounter this problem `bash gulp command not found` consider this running this script in cmd

  ```sh
  npm install --global gulp-cli
  ```

  Installing the gulp in global scope.

## <a name='Acknowledgements'></a>:two_hearts: Acknowledgements and References

- This project uses [Slick](https://kenwheeler.github.io/slick/) for the carousel/slider

## <a name='Credits'></a> :mailbox: Credits

| Member                                        | Role     |
| --------------------------------------------- | -------- |
| [Jaspher ](https://github.com/perderp)        | Core Dev |


## <a name='Contribute'></a> :handshake:Contribute

Contributions, issues and feature requests are welcome!

- Issue Tracker: https://github.com/perderp/san-o-fudousan/issues
- Source Code: https://github.com/perderp/san-o-fudousan

---

Copyright © 2020 [HiPE Inc. ltd.](https://bpoc.co.jp/) All rights reserved
