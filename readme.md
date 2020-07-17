# Awesome WP-CLI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![awesome-lint](https://github.com/schlessera/awesome-wp-cli/workflows/awesome-lint/badge.svg)](https://github.com/schlessera/awesome-wp-cli/actions?query=workflow%3Aawesome-lint) [<img src="assets/wp-cli-bw-trans-filled-tight@311x160.png" alt="WP-CLI Logo" align="right" height="80">](https://wp-cli.org)

[WP-CLI](https://wp-cli.org/) is the command-line interface for WordPress. It offers a complete alternative to the WordPress admin dashboard, often even surpassing its functionality or enabling new use cases. It also comes with a rich ecosystem of third-party commands that are bundled in Composer packages or directly integrated into WordPresss plugins or themes.

## Contents

- [Official links](#official-links)
- [Third-party packages](#third-party-packages)
	- [Package discovery](#package-discovery)
	- [Notable packages](#notable-packages)
- [Tutorials & guides](#tutorials--guides)

## Official links

Everything relevant that is directly part of the official WP-CLI team.

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

## Third-party packages

Unofficial third-party packages.

### Package discovery

Ways of searching for third-party packages you can use.

- [Packagist.org search by WP-CLI package type](https://packagist.org/?type=wp-cli-package) - Composer packages filtered by type `wp-cli-package`.
- [GitHub.com search for WP-CLI integrations](https://github.com/search?q=WP_CLI%3A%3Aadd_command%28+NOT+Akismet_CLI+NOT+elementor+NOT+WordCamp_CLI_Miscellaneous+NOT+W3TotalCache_Command+extension%3Aphp+language%3APHP+-org%3Awp-cli+-path%3Avendor+-path%3Awp-content+-path%3Apublic+-path%3Adeployer+-path%3Aweb+-path%3Asrc%2Fvendor+-path%3Aapp+-path%3Awordpress+-filename%3Aentity-command.php+-filename%3Aclass-wc-cli.php+-filename%3Awp-cli-bp.php+fork%3Afalse+-filename%3Aextension-command.php+-filename%3Acron-command.php+-filename%3Awp-seo-main.php+-path%3Aplugins+-path%3Adata+-path%3Abackup+-path%3Ademo+-path%3Awordcamp.org+-path%3Awordpress.org+-filename%3Alanguage-command.php+-filename%3Aredirection-cli.php+-path%3Athemes+-path%3Alibrary+-filename%3Aeval-command+-filename%3Arole-command+-filename%3Awidget-command+-filename%3Acache-command.php+-path%3Awp-app+-path%3Apublic_html+-filename%3Aqueue.php+-path%3AmyWeb+-path%3Adocroot+-path%3Awebsite&type=Code) - Heavily pre-filtered search for repositories that use `WP_CLI::add_command()`.

### Notable packages

Third-party packages that are commonly useful.

- [Yoast/wp-cli-faker](https://github.com/Yoast/wp-cli-faker) - Generate fake WordPress and WooCommerce content for testing purposes.
- [aaemnnosttv/wp-cli-login-command](https://github.com/aaemnnosttv/wp-cli-login-command) - Login to WordPress with secure passwordless magic links.
- [schlessera/wp-cli-psysh](https://github.com/schlessera/wp-cli-psysh) - Replace WP-CLI shell standard REPL with [PsySH](http://psysh.org/).
- [codeatcode/wp-cli-getbyurl](https://github.com/CodeAtCode/wp-cli-getbyurl) - Get post id and post type/taxonomy from post url.

## Tutorials & guides

Websites, ebooks, PDFs, talks and slide shows about how to make the most out of WP-CLI.

- [An Introduction to WP-CLI](https://pascalbirchler.com/an-introduction-to-wp-cli/) - Introductory article that introduces the main concepts and some popular use cases of WP-CLI.
- [Controlling WordPress through the Command Line](https://wordpress.tv/2017/05/22/alain-schlesser-controlling-wordpress-through-the-command-line-introduction-to-wp-cli/) - Introductory talk that covers the very basics of the command line for people who never used the console before.
- [WP Bullet WP-CLI Guides](https://guides.wp-bullet.com/category/wp-cli/) - Snippet-based guides that solve specific use cases.
- [Siteground Webinar: Learn How WP-CLI Can Make Your Life Easier](https://www.youtube.com/watch?v=DlxbRYpZdQg) - Practical examples on how you can improve your workflows with WP-CLI.
- [What you can do with WP-CLI](http://mte90.tech/Talk-WPCLI/#/) - Examples, script and many user cases from real experience with WP-CLI.
- [Codeatcode/WP-CLI scripts](https://github.com/CodeAtCode/WPCli-scripts) - Set of scripts based on wp cli.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.
