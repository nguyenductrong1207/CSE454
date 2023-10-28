## Contributing
Please submit bug reports, suggestions, and pull requests to the [GitHub issue tracker](https://github.com/PHPMailer/PHPMailer/issues).

We're particularly interested in fixing edge cases, expanding test coverage, and updating translations.

If you found a mistake in the docs, or want to add something, go ahead and amend the wiki – anyone can edit it.

If you have git clones from prior to the move to the PHPMailer GitHub organisation, you'll need to update any remote URLs referencing the old GitHub location with a command like this from within your clone:

```sh
git remote set-url upstream https://github.com/PHPMailer/PHPMailer.git
```

Please *don't* use the SourceForge or Google Code projects any more; they are obsolete and no longer maintained.

## Sponsorship
Development time and resources for PHPMailer are provided by [Smartmessages.net](https://info.smartmessages.net/), the world's only privacy-first email marketing system.

<a href="https://info.smartmessages.net/"><img src="https://www.smartmessages.net/img/smartmessages-logo.svg" width="550" alt="Smartmessages.net privacy-first email marketing logo"></a>

Donations are very welcome, whether in beer 🍺, T-shirts 👕, or cold, hard cash 💰. Sponsorship through GitHub is a simple and convenient way to say "thank you" to PHPMailer's maintainers and contributors – just click the "Sponsor" button [on the project page](https://github.com/PHPMailer/PHPMailer). If your company uses PHPMailer, consider taking part in Tidelift's enterprise support programme.

## PHPMailer For Enterprise

Available as part of the Tidelift Subscription.

The maintainers of PHPMailer and thousands of other packages are working with Tidelift to deliver commercial
support and maintenance for the open-source packages you use to build your applications. Save time, reduce risk, and
improve code health, while paying the maintainers of the exact packages you
use. [Learn more.](https://tidelift.com/subscription/pkg/packagist-phpmailer-phpmailer?utm_source=packagist-phpmailer-phpmailer&utm_medium=referral&utm_campaign=enterprise&utm_term=repo)

## Changelog
See [changelog](changelog.md).

## History
- PHPMailer was originally written in 2001 by Brent R. Matzelle as a [SourceForge project](http://sourceforge.net/projects/phpmailer/).
- [Marcus Bointon](https://github.com/Synchro) (`coolbru` on SF) and Andy Prevost (`codeworxtech`) took over the project in 2004.
- Became an Apache incubator project on Google Code in 2010, managed by Jim Jagielski.
- Marcus created [his fork on GitHub](https://github.com/Synchro/PHPMailer) in 2008.
- Jim and Marcus decide to join forces and use GitHub as the canonical and official repo for PHPMailer in 2013.
- PHPMailer moves to [the PHPMailer organisation](https://github.com/PHPMailer) on GitHub in 2013.

### What's changed since moving from SourceForge?
- Official successor to the SourceForge and Google Code projects.
- Test suite.
- Continuous integration with GitHub Actions.
- Composer support.
- Public development.
- Additional languages and language strings.
- CRAM-MD5 authentication support.
- Preserves full repo history of authors, commits, and branches from the original SourceForge project.
