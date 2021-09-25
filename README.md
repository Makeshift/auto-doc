[![CI](https://github.com/tj-actions/auto-doc/workflows/CI/badge.svg)](https://github.com/tj-actions/auto-doc/actions?query=workflow%3ACI)
[![Update release version.](https://github.com/tj-actions/auto-doc/workflows/Update%20release%20version./badge.svg)](https://github.com/tj-actions/auto-doc/actions?query=workflow%3A%22Update+release+version.%22)
[![Public workflows that use this action.](https://img.shields.io/endpoint?url=https%3A%2F%2Fapi-tj-actions1.vercel.app%2Fapi%2Fgithub-actions%2Fused-by%3Faction%3Dtj-actions%2Fauto-doc%26badge%3Dtrue)](https://github.com/search?o=desc\&q=tj-actions+auto-doc+language%3AYAML\&s=\&type=Code)


auto-doc
--------
Auto generate documentation from actions.yml.


## Usage


```yaml
...
    steps:
      - uses: actions/checkout@v2
      - name: Run auto-doc
        uses: tj-actions/auto-doc@v1
```


## Inputs


## Outputa


* Free software: [Apache License 2.0](LICENSE)

If you feel generous and want to show some extra appreciation:

[![Buy me a coffee][buymeacoffee-shield]][buymeacoffee]

[buymeacoffee]: https://www.buymeacoffee.com/jackton1
[buymeacoffee-shield]: https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png


Credits
-------

This package was created with [Cookiecutter](https://github.com/cookiecutter/cookiecutter) using [cookiecutter-action](https://github.com/tj-actions/cookiecutter-action)

Report Bugs
-----------

Report bugs at https://github.com/tj-actions/auto-doc/issues.

If you are reporting a bug, please include:

* Your operating system name and version.
* Any details about your workflow that might be helpful in troubleshooting.
* Detailed steps to reproduce the bug.