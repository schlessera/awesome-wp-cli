<!--lint disable awesome-git-repo-age-->
# Awesome WP-CLI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of packages and resources for WP-CLI, the command-line interface for WordPress.


## Contents

- [Official Links](#official-links)
- [Third-party Packages](#third-party-packages)
	- [Package Discovery](#package-discovery)
- [Tutorials & Guides](#tutorials--guides)


## Official Links

Everything relevant that is directly part of the official WP-CLI team.

### Infrastructure

The main entry points to the WP-CLI ecosystem.

- [wp-cli.org](https://wp-cli.org/) - Homepage of the WP-CLI project.
- [WP-CLI handbook](https://make.wordpress.org/cli/handbook/) - Guides on how to use or extend WP-CLI.
- [WP-CLI command reference](https://developer.wordpress.org/cli/commands/) - Reference documentation for all the official WP-CLI commands.
- [Make WordPress.org - CLI](https://make.wordpress.org/cli/) - Main entry point for contributing to WP-CLI.
  - [Contributing guide](https://make.wordpress.org/cli/handbook/contributing/) - Everything you need to know to contribute to the tool or its infrastructure.
  - [Official MakeWP Slack](https://make.wordpress.org/chat/) - Official Slack team where all international contributions to WordPress and its teams are discussed.
    - [#cli channel](http://wordpress.slack.com/messages/cli/) - The official support channel for WP-CLI and the WordPress CLI team.
  - [Good first issues](https://make.wordpress.org/cli/good-first-issues/) - List of issues on that are limited in scope and complexity.
- [WP-CLI GitHub organization](https://github.com/wp-cli) - Canonical home of the WP-CLI source code.
  - [WP-CLI framework repository](https://github.com/wp-cli/wp-cli) - The source code for the WP-CLI framework that powers all of the commands.
  - [WP-CLI bundle repository](https://github.com/wp-cli/wp-cli-bundle) - The source for the WP-CLI "binary" and how it is assembled.
  - [WP-CLI tests repository](https://github.com/wp-cli/wp-cli-tests) - The testing framework used throughout all WP-CLI repositories.

### Bundled commands

The commands that are bundled together with the official WP-CLI "binary" (a Phar archive file).

- [wp-cli/cache-command](https://github.com/wp-cli/cache-command) - Manages object and transient caches.
- [wp-cli/checksum-command](https://github.com/wp-cli/checksum-command) - Verifies file integrity by comparing to published checksums.
- [wp-cli/config-command](https://github.com/wp-cli/config-command) - Generates and reads the wp-config.php file.
- [wp-cli/core-command](https://github.com/wp-cli/core-command) - Downloads, installs, updates, and manages a WordPress installation.
- [wp-cli/cron-command](https://github.com/wp-cli/cron-command) - Tests, runs, and deletes WP-Cron events; manages WP-Cron schedules.
- [wp-cli/db-command](https://github.com/wp-cli/db-command) - Performs basic database operations using credentials stored in wp-config.php.
- [wp-cli/embed-command](https://github.com/wp-cli/embed-command) - Inspects oEmbed providers, clears embed cache, and more.
- [wp-cli/entity-command](https://github.com/wp-cli/entity-command) - Manage WordPress comments, menus, options, posts, sites, terms, and users.
- [wp-cli/eval-command](https://github.com/wp-cli/eval-command) - Executes arbitrary PHP code or files.
- [wp-cli/export-command](https://github.com/wp-cli/export-command) - Exports WordPress content to a WXR file.
- [wp-cli/extension-command](https://github.com/wp-cli/extension-command) - Manages plugins and themes, including installs, activations, and updates.
- [wp-cli/i18n-command](https://github.com/wp-cli/i18n-command) - Provides internationalization tools for WordPress projects.
- [wp-cli/import-command](https://github.com/wp-cli/import-command) - Imports content from a given WXR file.
- [wp-cli/language-command](https://github.com/wp-cli/language-command) - Installs, activates, and manages language packs.
- [wp-cli/maintenance-mode-command](https://github.com/wp-cli/maintenance-mode-command) - Activates, deactivates or checks the status of the maintenance mode of a site.
- [wp-cli/media-command](https://github.com/wp-cli/media-command) - Imports files as attachments, regenerates thumbnails, or lists registered image sizes.
- [wp-cli/package-command](https://github.com/wp-cli/package-command) - Lists, installs, and removes WP-CLI packages.
- [wp-cli/rewrite-command](https://github.com/wp-cli/rewrite-command) - Lists or flushes the site's rewrite rules, updates the permalink structure.
- [wp-cli/role-command](https://github.com/wp-cli/role-command) - Adds, removes, lists, and resets roles and capabilities.
- [wp-cli/scaffold-command](https://github.com/wp-cli/scaffold-command) - Generates code for post types, taxonomies, blocks, plugins, child themes, etc.
- [wp-cli/search-replace-command](https://github.com/wp-cli/search-replace-command) - Searches/replaces strings in the database.
- [wp-cli/server-command](https://github.com/wp-cli/server-command) - Launches PHP's built-in web server for a specific WordPress installation.
- [wp-cli/shell-command](https://github.com/wp-cli/shell-command) - Opens an interactive PHP console for running and testing PHP code.
- [wp-cli/super-admin-command](https://github.com/wp-cli/super-admin-command) - Lists, adds, or removes super admin users on a multisite installation.
- [wp-cli/widget-command](https://github.com/wp-cli/widget-command) - Adds, moves, and removes widgets; lists sidebars.

### Optional commands

The commands that are part of the official WP-CLI organization but are not bundled by default.

- [wp-cli/admin-command](https://github.com/wp-cli/admin-command) - Open /wp-admin/ in a browser.
- [wp-cli/dist-archive-command](https://github.com/wp-cli/dist-archive-command) - Create a distribution .zip or .tar.gz based on a plugin or theme's .distignore file.
- [wp-cli/doctor-command](https://github.com/wp-cli/doctor-command) - Diagnose problems within WordPress by running a series of checks for symptoms.
- [wp-cli/find-command](https://github.com/wp-cli/find-command) - Find WordPress installations on the filesystem.
- [wp-cli/google-sitemap-generator-cli](https://github.com/wp-cli/google-sitemap-generator-cli) - A CLI interface for the Google Sitemap Generator plugin.
- [wp-cli/profile-command](https://github.com/wp-cli/profile-command) - Quickly identify what's slow with WordPress.
- [wp-cli/scaffold-package-command](https://github.com/wp-cli/scaffold-package-command) - Scaffolds WP-CLI commands with functional tests, full README.md, and more.
- [wp-cli/wp-super-cache-cli](https://github.com/wp-cli/wp-super-cache-cli) - A CLI interface for the WP Super Cache plugin.

## Third-party Packages

Unofficial third-party packages.

### Package Discovery

Ways of searching for third-party packages you can use.

- [Packagist.org search by WP-CLI package type](https://packagist.org/?type=wp-cli-package) - Composer packages filtered by type `wp-cli-package`.

### Notable Packages

Third-party packages that are commonly useful.

- [Yoast/wp-cli-faker](https://github.com/Yoast/wp-cli-faker) - Generate fake WordPress and WooCommerce content for testing purposes.
- [aaemnnosttv/wp-cli-login-command](https://github.com/aaemnnosttv/wp-cli-login-command) - Login to WordPress with secure passwordless magic links.
- [schlessera/wp-cli-psysh](https://github.com/schlessera/wp-cli-psysh) - Replace WP-CLI shell standard REPL with [PsySH](http://psysh.org/).


## Tutorials & Guides

Websites, ebooks, PDFs, talks and slide shows about how to make the most out of WP-CLI.

- [An Introduction to WP-CLI](https://pascalbirchler.com/an-introduction-to-wp-cli/) - Introductory article that introduces the main concepts and some popular use cases of WP-CLI.
- [Controlling WordPress through the Command Line](https://wordpress.tv/2017/05/22/alain-schlesser-controlling-wordpress-through-the-command-line-introduction-to-wp-cli/) - Introductory talk that covers the very basics of the command line for people who never used the console before.
- [WP Bullet WP-CLI Guides](https://guides.wp-bullet.com/category/wp-cli/) - Snippet-based guides that solve specific use cases.
- [Siteground Webinar: Learn How WP-CLI Can Make Your Life Easier](https://www.youtube.com/watch?v=DlxbRYpZdQg) - Practical examples on how you can improve your workflows with WP-CLI.


## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.


## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Alain Schlesser has waived all copyright and
related or neighboring rights to this work.
