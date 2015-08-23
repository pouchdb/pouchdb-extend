pouchdb-extend
===============

Deprecation notice
---

As of PouchDB commit [f17d58](https://github.com/pouchdb/pouchdb/commit/f17d58a95941e7f2bb8d2505800decbe0435cf0f), this project is deprecated. PouchDB now has a custom `extend()` function that is inside of PouchDB itself.

You can still use this repo and that's fine, but it's not a requirement for using PouchDB or writing PouchDB plugins. Feel free to use whatever `extend()` you like!

Original docs follow.

Original docs
-----

extend() method taken from JQuery 1.9.0 for use in PouchDB

We use this because other extend libraries have been shown 
to not play nicely with Ember.js and IndexedDB
(see [pouchdb/pouchdb#2158](https://github.com/pouchdb/pouchdb/issues/2158)).
