## Description

The dragon form validator module is the best way to validate your form elements and is suitable for every web app framework like a flask, Django, and other uses. It will check the form values, whether it's fit your form or not.


## How to Install ?

` pip install dragon-form-validator `


## Highlights about Dragon Form Validator:

 - gives you excellent validation results without fail
 - game changer for your forms
 - computer understand format in boolean - 0 or 1
 
 
## How to Use ?

```
import dragon_form_validator

dragon_form_validator.checks('mail','sdfasf@gm@ail.com')

 => # you can use this in IF condition | if it's valids dragon_form_validator.checks(args,args) returns True ,other it's False
```


## Dragon Form Validators :

| Dragon Form Validators | what they do                                                 |
|------------------------------|----------------------------------------------------------------|
| dragon_form_validator.checks('mail',yourvalue) | check your mail will be valid or not         |
| dragon_form_validator.checks('f_name',yourvalue) | check your first name will be valid or not |
| dragon_form_validator.checks('l_name',yourvalue) | check your last name will be valid or not  |
| dragon_form_validator.checks('address',yourvalue) | check your address will be valid or not   |



## copyright & License

dragon form validator | Copyright @ Suresh P | MIT
