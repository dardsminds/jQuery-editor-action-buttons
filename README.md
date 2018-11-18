# jQuery-editor-action-buttons
Small jQuery plugin that put edit, save and cancel button on the editor area

![screen capture](https://github.com/dardsmind/jQuery-editor-action-buttons/blob/master/screen.png)

# How to use
HTML: place your div any part of your page, preferrably on upper right corner of the editing area

```html
<div class="editorButtons"></div>
```
JS: initialize the place holder with the buttons and assign actions to each buttons

	$(".editorButtons").editorActionButtons({
		onSave: function(){
			// your save function here
		},
		onEdit: function(){
			// your edit initialization code here
		},
		onCancel: function(){
			// restore code here
		}
	});
  
  # Note
  The button uses bootstrap class and font icon class, you need to include these files on your page as well.
  

