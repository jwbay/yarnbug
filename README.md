`> yarn licenses ls --production | grep flow@`  
`> yarn licenses ls --production | grep jest@`  
Expected: nothing  
Actual: nothing

`> yarn licenses ls --production | grep jest-` (jest's dependencies)  
Expected: nothing  
Actual:  
```
├─ babel-plugin-jest-hoist@18.0.0
├─ jest-changed-files@17.0.2
├─ jest-cli@18.1.0
├─ jest-config@18.1.0
├─ jest-diff@18.1.0
├─ jest-environment-jsdom@18.1.0
├─ jest-environment-node@18.1.0
├─ jest-file-exists@17.0.0
├─ jest-haste-map@18.1.0
├─ jest-jasmine2@18.1.0
├─ jest-matcher-utils@18.1.0
├─ jest-matchers@18.1.0
├─ jest-mock@18.0.0
├─ jest-resolve-dependencies@18.1.0
├─ jest-resolve@18.1.0
├─ jest-runtime@18.1.0
├─ jest-snapshot@18.1.0
├─ jest-util@18.1.0
```
