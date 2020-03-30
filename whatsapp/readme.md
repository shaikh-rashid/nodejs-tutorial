# WhatsApp Clone

Install files and deps

```bash
meteor create whatsapp

cd whatsapp

meteor add-platform android

rm -rf server client

# step 1
meteor remove blaze-html-templates
meteor add angular-templates

meteor add dab0mb:ionic-assets
meteor npm install angular@^1.5.8 --save
meteor npm install angular-animate@^1.5.8 --save
meteor npm install angular-sanitize@^1.5.8 --save
meteor npm install angular-ui-router@^0.3.1 --save
meteor npm install ionic-scripts --save
meteor npm install babel-runtime --save

# step 2
meteor npm install angular-meteor --save
meteor npm install angular-ecmascript --save

# step 3
meteor npm install moment --save
meteor add fourseven:scss

# step 4
meteor npm install angular-moment --save
meteor add check

# step 5
meteor npm install --save bcrypt
meteor add mys:accounts-phone
meteor npm install angular-meteor-auth --save

# step 6
meteor reset
meteor remove insecure

# step 7
meteor remove autopublish
meteor add reywood:publish-composite

# step 8
meteor add okland:camera-ui
```
