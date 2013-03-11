# forms

  create forms dynamically by providing a JSON schema

## Installation

    $ component install nickjackson/forms

## Spec
[wiki/Spec](https://github.com/nickjackson/forms/wiki/Spec)


## Todo
* Add component/Model support?
* Add Date/Calendar functionality
* Add Tests
* Validation

## API

### var form = new Form(schema);
Creates new Form object based on schema object
 
### form.render()
Renders form

### form.setValue({})
Fills in rendered form with data given

### form.getValue()
Returns object of current values
 
### form.view
Rendered DOM

## License

  MIT
