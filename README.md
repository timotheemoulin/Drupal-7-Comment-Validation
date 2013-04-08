Drupal Comment Validation
=========================

Drupal core : 7.x,
Version : 7.x-1.0,
Package : Timothée Moulin

Provides a username validation on anonymous comments

Steps to install

1. Upload the folder in /sites/*/modules
2. Install the module as usually
3. Go to the configuration page and fill out the unauthorized terms field

It will automatically check the username on anonymous comments and refused the comment if it contains a term from the list.
Usernames of registrated users are automatically checked by Drupal.
