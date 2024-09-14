# <small>(variables?: Object) => string</small> $template(<small>input: string</small>)

Returns a function that allows you to substitute variables into `input` alongside `if` and `unless` expressions.
## Substitution

?> Note that you need to pass the variables you want to use in substitution into `variables`.

### Variable Interpolation
You can use `{{ variableName }}` in `input`, and it will be replaced by the value of `variables.variableName`
### If statements
You can use `{{#if (condition)}} ... {{/if}}` in `input`, and the content inside will only appear if the condition returns a truthy value.
### Unless statements
You can use `{{#unless (condition)}} ... {{/unless}}` in `input`, and the content inside will only appear if the condition returns a falsy value.
## Example
```javascript
$template("Hello {{foo}}")({foo: "World"}) // returns "Hello World"

$template("The number is {{#if num > .5}}greater than 0.5{{/if}}{{#unless num > .5}}less than 0.5{{/unless}}")({num: 0.65}) // returns "The number is greater than 0.5"
```