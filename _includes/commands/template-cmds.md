
| Command           | Description                                                                     |
| ----------------- | ------------------------------------------------------------------------------- |
| mceInsertTemplate | Inserts a template the value should be the template HTML to process and insert. |

**Example**

```js
tinymce.activeEditor.execCommand('mceInsertTemplate', false, '<p>This is my template text.</p>');
```
