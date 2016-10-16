Tox Mirror
=============

Mirror of Tox package for pre-commit.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prospector: see http://tox.readthedocs.io/en/latest/


### Using prospector with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/AngryDevelopersLLC/tox-mirror
        sha: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: tox
