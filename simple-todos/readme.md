# Simple-todos

- create porject

```bash
meteor create simple-todos

cd simple-todos

# step 1
meteor npm install --save react react-dom

# step 2
meteor npm install --save react-addons-pure-render-mixin
meteor add react-meteor-data

# step 3
meteor Mongo
db.tasks.insert({ text: "Hello world!", createdAt: new Date() });

# step 4
meteor install-sdk android
meteor add-platform android
meteor run android

# step 5
meteor add accounts-ui accounts-password
meteor npm install --save bcrypt

# step 6
meteor remove insecure

# step 7
meteor remove autopublish
meteor npm install --save classnames

# step 8
meteor add practicalmeteor:mocha
meteor test --driver-package practicalmeteor:mocha
```
