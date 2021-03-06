CKEditorFootnotes
==================

Footnotes plugin for CKEditor.

Demo: http://demo.gridlight-design.co.uk/ckeditor-footnotes.html

CKEditor Addon: http://ckeditor.com/addon/footnotes

Configuring Multiple Instances
-------------

As of 1.0.5 the plugin accepts a configuration option to allow you to prefix all your footnotes when the editor is instantiated.

E.g.

~~~~~~
CKEDITOR.replace( 'editor1', {
    footnotesPrefix: 'a'
} );
~~~~~~

This could be set dynamically to allow you to ensure that all chunks of text can contain unique ID's, allowing you to include multiple chunks of text on any given page with ID clashes.

For example, it should be possible to use a server-side script to set this variable to the id of a database row.
