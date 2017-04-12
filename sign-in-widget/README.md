# Code Snippets

## To get files

1. Download [background.jpg](background.jpg) and [iceLogo.png](iceLogo.png) to `C:\inetpub\wwwroot`.
2. Update the sign-in widget code (you can use the code snippets below).

## Code Snippet 1: To add a custom logo

To replace the original `oktaSignIn` var declaration.

```javascript
var oktaSignIn = new OktaSignIn({baseUrl: orgUrl, logo: 'iceLogo.png'});
```

## Code Snippet 2: To add a custom background

To be placed before `</head>`

```html
<style>
  body{
    background-image: url("background.jpg");
    background-repeat: repeat;
  }
</style>
```
