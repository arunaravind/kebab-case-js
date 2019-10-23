# kebab-case-js
Regex to convert any string - covered almost all symbols - to kebab case

```
const yourString = "Frankly, my dear, I don't give a damn"
const toKebabCase = yourString.replace(/([a-z])([A-Z])/g, '$1-$2').replace(/([-!$%^&*()_+|~=`{}\[\]:";'<>?,.\/])/g, '-').toLowerCase().replace(/\s+/g, '-').toLowerCase()
```
