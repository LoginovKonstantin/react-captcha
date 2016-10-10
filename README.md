# react-captcha
###**Install**
>$ npm install react-captcha --save

###**Example usage**

```jsx
const Captcha = require('react-captcha');  

<Captcha
	sitekey = 'your_sitekey'
	lang = 'en'
	theme = 'light'
	type = 'image'
	callback = {(value) => console.log(value)}/>

```
HELP:  https://developers.google.com/recaptcha/intro