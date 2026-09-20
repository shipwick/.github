# .github

Defaults for every repository of the Shipwick organization that does not have
its own: the [security policy](SECURITY.md) and the
[code of conduct](CODE_OF_CONDUCT.md). `profile/README.md` is what
[github.com/shipwick](https://github.com/shipwick) shows.

## rulesets/

The branch and tag rules of the repositories, to import under
*Settings → Rules → Rulesets → New ruleset → Import a ruleset*:

- `main.json` — every repository: the default branch cannot be deleted or
  force-pushed. History that was public stays what it was.
- `release-tags.json` — shipwick/shipwick: only repository administrators can
  create, move or delete `v*` tags. A tag is a release: the installer and the
  Homebrew formula install what it points to.
