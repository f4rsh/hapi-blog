# Changelog
All notable changes to this project will be documented in this file.

## Unreleased
- Added article short URL support

## 0.0.1 - 2017-12-01
- Created a `base.handler` for generic CRUD handler
- Added basic CRUD for entities `article`, `author`, `tag`
- Added basic token based authorization for `POST`, `PUT/PATCH`, `DELETE` endpoints
- Added articles filter for published/non published articles based on authorization token
- Added `key` parameter for fetch an article by his key
- `PUT/PATCH` endpoints for articles store it respective tags (from body payload)