# Craft CMS 3.x Starter Project

A [Craft CMS](https://craftcms.com/) starter project by [Andrea DeMers](http://andreademers.com).

## Content Management System (CMS)
- [Craft CMS](https://craftcms.com/)
- [Craft CMS 3.x documentation](https://docs.craftcms.com/v3/)

## Craft CMS Plugins
- [Contact Form](https://plugins.craftcms.com/contact-form)
- [Mailgun](https://plugins.craftcms.com/mailgun)
- [Minify](https://plugins.craftcms.com/minify)
- [Redactor](https://plugins.craftcms.com/redactor)
- [Retcon](https://plugins.craftcms.com/retcon)
- [SEOmatic](https://plugins.craftcms.com/seomatic)
- [Twigpack](https://plugins.craftcms.com/twigpack)

## PHP Packages
- [Craft Scripts](https://packagist.org/packages/nystudio107/craft-scripts)

## Front-end
### Build Tools
- [Laravel Mix](https://github.com/JeffreyWay/laravel-mix)

### CSS
- [Tailwind CSS](https://tailwindcss.com/)

### JavaScript
- [lazySizes](https://afarkas.github.io/lazysizes/index.html)
- [Vue.js](https://vuejs.org/)

## Requirements
- Craft [server requirements](https://docs.craftcms.com/v3/requirements.html)
- Craft [control panel browser requirements](https://docs.craftcms.com/v3/requirements.html#control-panel-browser-requirements)
- [Composer](https://getcomposer.org/) PHP dependency manager 1.3.0 or later

## Installation
1. To create a new project, run `composer create-project ademers/craft-starter <Path>`, substituting `<Path>` with the path where Composer should create the project.
2. Create a database as per the instructions in the [Craft documentation](https://docs.craftcms.com/v3/installation.html#step-4-create-a-database).
3. Set up your web server as per the instructions in the [Craft documentation](https://docs.craftcms.com/v3/installation.html#step-5-set-up-the-web-server).
4. Duplicate the `.env.example` file in the project root and rename it to `.env`.
5. Run the Craft setup wizard `./craft setup` and answer the questions when prompted.
6. Access your new Craft website from your web browser.
7. Do a little dance.

## Todo
- [x] Replace Vue.js with Alpine.js as default JavaScript framework
- [x] Configure PurgeCSS
- [x] Add installation instructions

## License
The MIT License (MIT). Please see [License file](https://github.com/ademers/craft-starter/blob/develop/LICENSE.md) for more information.
