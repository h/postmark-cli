<h1 align="center">
  <img src="./media/header@2x.png" width="100%" style="max-width:1230px;" alt="Postmark CLI">
</h1>
<p align="center">A CLI tool for managing templates, sending emails, and fetching servers on <a href="https://postmarkapp.com">Postmark</a>. <br/>Nifty for integrating with a CI/CD pipeline.</p>

<p align="center">
  <a href="https://travis-ci.org/wildbit/postmark-cli"><img src="https://travis-ci.org/wildbit/postmark-cli.svg?branch=master" alt="TravisCI"></a>
  <a href="https://badge.fury.io/js/postmark-cli"><img src="https://badge.fury.io/js/postmark-cli.svg" alt="npm version"></a>
</p>

## Usage

Please see the [wiki](https://github.com/wildbit/postmark-cli/wiki) for detailed instructions about how to use the library. 
For quick start after installing the library, you can type `postmark` in your command line, which should show you the CLI tool available options.

Check out wiki for instructions how to [send email](https://github.com/wildbit/postmark-cli/wiki/email-command), 
[manage templates](https://github.com/wildbit/postmark-cli/wiki/templates-command) or [list servers](https://github.com/wildbit/postmark-cli/wiki/servers-command).

```bash
$ postmark

  Commands:
    postmark email <command> [options]      Send an email
    postmark servers <command> [options]    Manage your servers
    postmark templates <command> [options]  Pull and push your templates

  Options:
    --version  Show version number
    --help     Show help
```

## Installation

- Install [Node.js](https://nodejs.org/en/)
- `$ npm i postmark-cli -g`
- `$ postmark` 🌈

## Issues & Comments

Feel free to contact us if you encounter any issues with the library. 
Please leave all comments, bugs, requests and issues on the Issues page.

## License

Postmark CLI library is licensed under the **MIT** license. Please refer to the [LICENSE](https://github.com/wildbit/postmark-cli/blob/master/LICENSE.md) for more information.
