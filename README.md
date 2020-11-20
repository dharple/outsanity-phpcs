# Outsanity PHPCS rules

This is based on PSR-12 and my personal preferences.  It's also based on
[AlexHowansky]'s work on [ork-phpcs] and other phpcs repos.

---

# Conventions

## Code

Source lives in `src`.

Namespace prefix is `\Outsanity\ProjectOrLibrary\`, so projects or librarys can
be used side-by-side if the need arises.

## Tests

Unit tests live in `tests\Unit\`.

Test namespace prefix is `\Outsanity\Tests\Unit\`, with the understanding that
they will not be imported between projects.

---

[AlexHowansky]: https://github.com/AlexHowansky
[ork-phpcs]: https://github.com/AlexHowansky/ork-phpcs
