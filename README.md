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
#####upperCase
has uppercase symbols in generated password
```javascript
default: true
options: boolean / true or false
```
#####lowerCase
has lowercase symbols in generated password
```javascript
default: true
options: boolean / true or false
```
#####numbers
has numbers symbols in generated password
```javascript
default: true
options: boolean / true or false
```
#####punctuation
has punctuation symbols in generated password
```javascript
default: true
options: boolean / true or false
```
#####size
password length
```javascript
default: 8
options: integer
```
#####wrapperClass
custom class to select
```javascript
default: "generatorWrapper"
options: string
```
#####button: {
######isVisible
has visible button
```javascript
default: true
options: boolean / true or false
```
######text
button text
```javascript
default: "New Password"
options: string
```
##### }
## Demo
<a href="http://codepen.io/mel/full/kzJho" target="_blank">codepen.io/mel/full/kzJho</a>
## License
March 2014 <br />
passwordGenerator 1.1.0 <br />
@author Mario Vidov <br />
@url <a href="http://vidov.it" target="_blank">www.vidov.it</a> <br />
@twitter  <a href="http://twitter.com/MarioVidov" target="_blank">MarioVidov</a> <br />
MIT license
