Andivionian Project Status Classification [![Status Aquana][status-aquana]][andivionian-status-classifier]
=========================================
This is a classification of the software projects that allows to determine the project applicability, according to the classification-defined criteria. It is considered that the software authors themselves may assign an andivionian status to their project, and it will help the users to figure out at what development stage the project currently is.

The classification is forked from the work status classification used by the [Andivionian Scientific Alliance][alliance] earlier (see the **History** section below for details).

**To see the current status set, browse to the [version 1][v1] page.**

History
-------
This set of statuses was "forked" from the [set of work statuses][alliance.old-statuses] used by the [Andivionian Scientific Alliance][alliance] back in 2015, with certain adaptations to use it for the software projects. For example, we use the usability and feature completeness criteria instead of the anomaly engineering ones.

Later in 2016, the Alliance has [reworked the status system][alliance.new-statuses], and these terms are no longer used for the work statuses. They are currently applied to [the world classification][alliance.world-classes]. We still believe in their applicability for the software projects in their original meaning, so there are no current plans to adapt any changes from the Alliance.

Versioning Notes
----------------
This is a section on versioning the classification itself. The current latest major version is [v1][].

If anything changes in the definition of the statuses, then the version is increased according to [Semantic Versioning 2.0.0][semver]. We consider the status definitions to be the public API of the project, so the minor version will increase in case of backwards-compatible changes, and the major version will update in case of backwards-incompatible changes.

If a new major version is released, it will be made available on a separate URL (`/v2/` instead of `/v1`), alongside the old version.

### Hyperlink Stability
We are trying to keep the hyperlinks anywhere inside https://andivionian.fornever.me/ to be stable when possible, including the link anchors. But this is not subject to the versioning policy. If any of the links change, this won't automatically cause a major version increment.

License
-------
The materials from this project may be redistributed under the terms of [Creative Commons Attribution-ShareAlike 3.0 License][cc-by-license], the same as the original materials from the [Andivionian Scientific Alliance][alliance].

[![cc-by][]][cc-by-license]

Documentation
-------------
- [Changelog][docs.changelog]

[alliance.new-statuses]: http://scientific-alliance.wikidot.com/item-classes
[alliance.old-statuses]: https://web.archive.org/web/20150728015250/http://scientific-alliance.wikidot.com/item-classes
[alliance.world-classes]: http://scientific-alliance.wikidot.com/world-classes
[alliance]: http://scientific-alliance.wikidot.com/
[andivionian-status-classifier]: https://andivionian.fornever.me/v1/#status-aquana-
[cc-by-license]: http://creativecommons.org/licenses/by-sa/3.0/
[cc-by]: http://mirrors.creativecommons.org/presskit/buttons/80x15/svg/by-sa.svg
[docs.changelog]: CHANGELOG.md
[semver]: https://semver.org/
[status-aquana]: https://img.shields.io/badge/status-aquana-yellowgreen.svg
[v1]: https://andivionian.fornever.me/v1/
