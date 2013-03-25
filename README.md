APIs for the text field selections
==================================

```javascript
//Selects everything in the text field.
element.select()

//Returns the offset to the start of the selection.
//Can be set, to change the start of the selection.
element.selectionStart [ = value ]

//Returns the offset to the end of the selection.
//Can be set, to change the end of the selection.
element.selectionEnd [ = value ]

//Changes the selection to cover the given substring.
element.setSelectionRange(start, end)
```

Connect at the page as shown in the example below:

```HTML
<!--[if lte IE 8]><script type="text/javascript" src="selection.htc"></script><![endif]-->
```