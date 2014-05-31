ngBootbox
=========

AngularJS wrapper for Bootbox.js. Bootbox.js allowes you to easily make use of Twitter Bootstrap modals for javascript alerts, confirms and prompts. ngBootbox includes three directives, one for each of alert, confirm and prompt.

Usage
=========

ng-bootbox-alert

```html
<pre>
<button class="btn btn-default" ng-bootbox-alert="Alert message!">
    Alert
</button>
</pre>
```

ng-bootbox-confirm

```html
<pre>
<button class="btn btn-lg btn-primary" ng-bootbox-confirm="Are you sure you want to confirm this?"
        ng-bootbox-confirm-action="confirmCallbackMethod(attr1, attr2)" ng-bootbox-confirm-action-cancel="confirmCallbackCancel(attr1, attr2)">
    Confirm
</button>
</pre>
```

ng-bootbox-prompt

```html
<pre>
<button class="btn btn-lg btn-primary" ng-bootbox-prompt="Please type in your name"
        ng-bootbox-prompt-action="promptCallback(result)" ng-bootbox-prompt-action-cancel="promptCallbackCancelled(result)">
    Prompt
</button>
</pre>
```