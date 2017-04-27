[![Support](https://www.totaljs.com/img/button-support.png)](https://www.totaljs.com/support/)

- [__Live chat with professional support__](https://messenger.totaljs.com)
- [__HelpDesk with professional support__](https://helpdesk.totaljs.com)

# Total.js: Empty Project

- Install Total.js via NPM `$ npm install total.js`
- Download example
- Run it `$ node debug.js`

# Running this application on Google Cloud Platform

In a project (e.g. long-temple-164810) on Google Cloud Platform (https://console.cloud.google.com) open the online Google Shell (icon looks like [>_] ).

type:

```javascript
CLONETODIR=~/src/long-temple-164810/totaljs-gruniart
```

next type:

```javascript
git clone https:// $CLONETODIR
```

then type:

```javascript
cd $CLONETODIR
```

Optionally type:

```javascript
git pull
```

Following on, type:

```javascript
npm install
```

then type:

```javascript
gcloud app deploy --project long-temple-164810
```

The deployment will start. When prompted, confirm by typing: ```Y``` (followed by ENTER)

After the deployment has succeeded, type: ```gcloud app browse```

Open a browser and browse for the URL provided for the application, e.g.:

```javascript
https://long-temple-164810.appspot.com
```