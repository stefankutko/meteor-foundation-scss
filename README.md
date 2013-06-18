Zurb Foundation Framework for Meteor
======================

This is a simply a wrapper for the Foundation framework git repo. The goal is to
provide the base SCSS files and JS files so the user can manually include them
into their project. This allows choice as to which parts you wish to use and
provides the mixins and variables for use in your own SCSS files.

**Please note that this packages does not actually include the JS or css
itself!** You must include the scss files from the packages directory. For
example, if your SCSS file lives in the root of your meteor app you should use
this to include all of Foundation SCSS.

```scss
@import 'packages/foundation-scss/foundation/scss/foundation';
```

The same goes for the base jQuery plugins. This allows for the use of your own
version of jQuery or Zepto seperate from what is included by default with
Foundation.
