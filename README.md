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
  ],
  tel: [
    { rule: /^1[34578]\d{9}$/, message: '手机格式不正确' }
  ]
}
console.log(FormValidate.checkForm(this.user, this.rules))

```
