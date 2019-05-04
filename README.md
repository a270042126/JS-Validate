# JS-Validate
Vue JS Validate

### use
```
const user = {
  name: '',
  tel: '',
  id: ''
}
const rules= {
  name: [
    { require:true, message: '必填' }，
    { min: 3, max: 5, message: '在长度在3—5之间' }
  ]
}
console.log(FormValidate.checkForm(this.user, this.rules))

```
