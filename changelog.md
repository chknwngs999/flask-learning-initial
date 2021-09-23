# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project WILL ADHERE (as in, in the future) to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

- Like/Comment features

  - Restricted to accounts

  - Corresonding SQL tables (blog id, commenter's user id, comment text, comment timestamp)(queried by blog id, sorted by timestamp?)

  - Liking comments?

- Saving features (low priority)

- Post tags (Like reddit flairs)

- Account Settings

  - Personalized Background/Color Theme

  - Profile pictures/biography

  - Corresponding SQL tables (user id, background image color/link (separate table?), profile image link, biography text)

## 1.0.2 - 2021-09-21

### Changed

- Edited Procfile (for hosting on heroku)

## 1.0.1 - 2021-09-21

### Added

- Added Procfile (for hosting on heroku)

## 1.0.0 - 2021-09-20

### Added

- Initial Commit
  - Created __init__.py, auth.py, blog.py, db.py, and schema.sql

  - Created templates directory, base.html, login and register pages, and index, create, and update pages

  - Created static directory and style.css

  - Created initial unit tests

  - Created gitignore file

  - Created MANIFEST.in, setup.cfg, and setup.py for building dist files

  - Created README.md and changlog.md
