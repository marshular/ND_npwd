# ND_npwd
### server.cfg
```set npwd:framework standalone```

### config.json
```json
{
  "PhoneAsItem": {
    "enabled": false,
    "exportResource": "my-core-resource",
    "exportFunction": "myCheckerFunction"
  },
  "general": {
    "useResourceIntegration": true,
    "toggleKey": "f1",
    "toggleCommand": "phone",
    "defaultLanguage": "en"
  },
  "contacts": {
    "frameworkPay": true,
    "payResource": "ND_npwd",
    "payFunction": "pay"
  },
  "profanityFilter": {
    "enabled": false,
    "badWords": ["esx"]
  },
  "database": {
    "useIdentifierPrefix": false,
    "playerTable": "nd_characters",
    "identifierColumn": "identifier",
    "identifierType": "license",
    "profileQueries": true,
    "phoneNumberColumn": "phonenumber"
  },
  "debug": {
    "level": "silly",
    "enabled": true,
    "sentryEnabled": true
  },
  "browser": {
    "homepageUrl": "https://docs.fivemanage.com"
  },
  "defaultContacts": [],
  "disabledApps": [],
  "apps": [],
  "voiceMessage": {
    "enabled": false,
    "authorizationHeader": "PE-Secret",
    "url": "",
    "returnedDataIndexes": ["url"]
  }
}
```
