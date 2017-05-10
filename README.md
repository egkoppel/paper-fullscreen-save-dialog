# paper-fullscreen-save-dialog
<!---
```
<custom-element-demo>
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="paper-fullscreen-save-dialog.html">
    <link rel="import" href="../paper-button/paper-button.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<paper-button onClick="document.getElememtById('dialog').open()">Hi</paper-button>
<paper-fullscreen-save-dialog id="dialog">
          <paper-fullscreen-save-dialog id="dialog" confirm-button="Done">
            <span class="title">Hello world</span>
            <p>Hello world</p>
        </paper-fullscreen-save-dialog>
</paper-fullscreen-save-dialog>
```
A polymer fullscreen paper dialog, with both save and cancel buttons
