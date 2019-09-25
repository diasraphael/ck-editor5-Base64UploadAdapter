CKEditor 5 classic editor build with base64upload Adapter
=========================================================

## Demo
https://codesandbox.io/s/github/diasraphael/ckeditor-sample

![screenshot](https://user-images.githubusercontent.com/6531851/65573621-98d37380-df6b-11e9-9583-df322fd6514e.png)

## Quick start

First, install the build from npm:

```bash
npm install --save @diasraphael/ck-editor5-base64uploadadapter
```
 In your website:

```
<div id="editor">
    <p>This is the editor content.</p>
</div>
<script src="./node_modules/@diasraphael/ck-editor5-base64uploadadapter/build/ckeditor.js"></script>
<script>
    ClassicEditor
        .create( document.querySelector( '#editor' ) )
        .then( editor => {
            window.editor = editor;
        } )
        .catch( err => {
            console.error( err.stack );
        } );
</script> 
```

 In your JavaScript application:

```js
import ClassicEditor from '@diasraphael/ck-editor5-base64uploadadapter';

// Or using the CommonJS version:
// const ClassicEditor = require( '@diasraphael/ck-editor5-base64uploadadapter' );

ClassicEditor
	.create( document.querySelector( '#editor' ) )
	.then( editor => {
		window.editor = editor;
	} )
	.catch( err => {
		console.error( err.stack );
	} );
```


## License

Licensed under the terms of [GNU General Public License Version 2 or later](http://www.gnu.org/licenses/gpl.html). For full details about the license, please check the `LICENSE.md` file or [https://ckeditor.com/legal/ckeditor-oss-license](https://ckeditor.com/legal/ckeditor-oss-license).
