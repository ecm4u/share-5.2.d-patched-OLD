Share 5.2.d-patched
===================

This is a patched version of Alfresco Share 5.2.d, based on [the subversion tag](https://svn.alfresco.com/repos/alfresco-open-mirror/web-apps/Share/tags/5.2.d/). The following changes have been made.

* Don't build the modules `cmm-qa`, `web-editor`, `web-editor-plugin`, `web-editor-samples/customer-site`, `wcmquickstart-module`.
* Show all nodes in the 'My Documents' dashlet, not only documents. Especially favorite folders can be displayed in the dashlet.
* Allow transient fields (fields not corresponding to a node property)  to be displayed inside a set.
* Applied the patch from ACE-4154 to allow download of custom type Datalists.

You can create a diff to the tag `5.1.g` by executing

    $ ./diff-to-tag.sh

This will create a file `../share-5.1.g.diff`.
