# Strapi plugin

This is a fork of the official strapi-plugin-users-permissions that adds a few things to the user authentication process that are missing from the default.

So far, I've added:
- support for handle property during sign up with regular expression validation
- minimum password length
- workaround to fix error message for duplicate key (when working at least with SQLite)
