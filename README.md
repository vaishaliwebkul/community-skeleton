<p align="center"><a href="https://www.uvdesk.com/en/" target="_blank">
    <img src="https://s3-ap-southeast-1.amazonaws.com/cdn.uvdesk.com/uvdesk/bundles/webkuldefault/images/uvdesk-wide.svg">
</a></p>

<p align="center">
<a href="https://packagist.org/packages/uvdesk/community-skeleton"><img src="https://poser.pugx.org/uvdesk/community-skeleton/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/uvdesk/community-skeleton"><img src="https://poser.pugx.org/uvdesk/community-skeleton/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/uvdesk/community-skeleton"><img src="https://poser.pugx.org/uvdesk/community-skeleton/license.svg" alt="License"></a>
<a href="#backers"><img src="https://opencollective.com/uvdesk/backers/badge.svg" alt="Backers on Open Collective"></a>
<a href="#sponsors"><img src="https://opencollective.com/uvdesk/sponsors/badge.svg" alt="Sponsors on Open Collective"></a>
<a href="https://gitter.im/uvdesk/community"><img src="https://badges.gitter.im/uvdesk/community-skeleton.svg" alt="connect on gitter"></a>
</p>


## Topics
1. [Introduction](#introduction)
2. [Documentation](#documentation)
3. [Requirements](#requirements)
4. [Installation & Configuration](#installation-and-configuration)
5. [License](#license)
6. [Security Vulnerabilities](#security-vulnerabilities)
7. [Miscellaneous](#miscellaneous)

### Introduction

A fully-functional [UVDesk Community Edition][1] project skeleton packaged along with the bare essential utilities that you can use to develop your own custom helpdesk solutions.

It designed on some of the hottest opensource technologies
such as [Symfony](https://symfony.com/) a [PHP](https://secure.php.net/) framework, [Backbone.js](https://backbonejs.org/)
a progressive Javascript framework.

### What's Included?

The standard distribution comes pre-configured with the following bundles:

  * [**UVDeskCoreBundle**][3] - The core framework bundle for bulding helpdesk solutions

  * [**UVDeskAutomationBundle**][4] - Adds support for workflows and prepared responses to automate any specific operations within your helpdesk system

  * [**UVDeskSupportCenterBundle**][5] - Integrates the easily customizable support center portal to enable users to easily interact with the support staff through your helpdesk system
  
  * [**UVDeskMailBoxBundle**][11] - Convert and get all your emails to support tickets on UVDesk and manage customer query easily.

### Documentation

Learn more about UVDesk from [UVDesk Developer Guide][14].

### Demo 

Visit [UVDesk Live Demo][15].

### Forum

We are also having a forum for any type of your concern, feature request discussions. Please visit: [UVDesk Community Forum][16].


### Requirements

* **OS**: Ubuntu 16.04 LTS or higher / Windows 7 or Higher (WAMP / XAMPP).
* **SERVER**: Apache 2 or NGINX.
* **RAM**: 3 GB or higher.
* **PHP**: 7.2 or higher.
* **Processor**: Clock Cycle 1 Ghz or higher.
* **For MySQL users**: 5.7.23 or higher.
* **Composer**: 1.6.5 or higher.
* **IMAP**: [PHP IMAP][6]
* **MailParse**: [PHP Mailparse][7]

### Installation and Configuration

To create your project, run the following command:

```bash
$ composer create-project uvdesk/community-skeleton helpdesk-project
```

After creating your project, you can setup the project in the following ways:

**Via Terminal**

```bash
$ php bin/console uvdesk:configure-helpdesk
```

**Via Web Installer**

After opening your project in the web browser, where you will be greeted by the web installer to guide you in setting up your project.

### About Us

The development of the UVDesk Community Edition is supported by [Webkul][9], led by the [UVDesk Team][10].

Visit our official [website][1] to learn more about the UVDesk Helpdesk System.

### License

All libraries and bundles included in the UVDesk Community Edition are released under the [MIT][12] license.

### Security Vulnerabilities

Please don't disclose security vulnerabilities publicly. If you find any security vulnerability in UVDesk opensource then please write us mail: mailto:support@uvdesk.com.

### Miscellaneous

#### Contributors

This project is on [Open Collective][13] and it exists thanks to this people who contribute.

<a href="https://github.com/uvdesk/community-skeleton/graphs/contributors"><img src="https://opencollective.com/uvdesk/contributors.svg?width=890&button=false"/></a>

#### Backers

Thank you to all our backers! 🙏

<a href="https://opencollective.com/uvdesk#contributors" target="_blank"><img src="https://opencollective.com/uvdesk/backers.svg?width=890"></a>

#### Sponsors

Support this project by becoming a sponsor. Your logo will show up here with a link to your website.

<a href="https://opencollective.com/uvdesk/contribute/sponsor-7372/checkout" target="_blank"><img src="https://images.opencollective.com/static/images/become_sponsor.svg"></a>

[1]: https://www.uvdesk.com/
[3]: https://github.com/uvdesk/core-framework
[4]: https://github.com/uvdesk/automation-bundle
[5]: https://github.com/uvdesk/support-center-bundle
[6]: http://php.net/manual/en/book.imap.php
[7]: http://php.net/manual/en/book.mailparse.php
[8]: https://getcomposer.org/
[9]: https://webkul.com/
[10]: https://www.uvdesk.com/en/team/
[11]: https://github.com/uvdesk/mailbox-component
[12]: https://github.com/uvdesk/community-skeleton/blob/master/LICENSE
[13]: https://opencollective.com/uvdesk
[14]: https://docs.uvdesk.com/
[15]: https://demo.uvdesk.com/
[16]: https://forums.uvdesk.com/
