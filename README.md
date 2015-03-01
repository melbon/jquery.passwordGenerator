# jquery.passwordGenerator
With this plugin you can easily generate different password with very high level of security.
## Install
```javascript
<script src="jquery.min.js"></script>
<script src="../jquery.passwordGenerator.min.js"></script>
```
or 
```javascript
bower install passwordgenerator
```
## Usage
```javascript
$(selector).passwordGenerator();
```
## Configuration
```javascript
{
    upperCase: , // default: true;
    lowerCase: , // default: true;
    numbers: , // default: true;
    punctuation: , // default: true;
    size: , // default: 8
    wrapperClass: "", // default: "generatorWrapper";
    button: {
        isVisible: , // default: true;
        text: "" // default: "New Password";
    }
}
```
## Demo
<a href="http://codepen.io/mel/pen/kzJho" target="_blank">codepen.io/mel/pen/kzJho</a>
## License
March 2014 <br />
passwordGenerator 1.1.0 <br />
@author Mario Vidov <br />
@url <a href="http://vidov.it" target="_blank">www.vidov.it</a> <br />
@twitter  <a href="http://twitter.com/MarioVidov" target="_blank">MarioVidov</a> <br />
MIT license
