# Gravity Forms Phone Extension
Contributors: joehana, quentinhayot  
Donate link: http://paypal.me/anex  
Tags: forms, phone, input  
Requires at least: 4.5.0  
Tested up to: 4.9  
Stable tag: 1.2.0  
License: GPLv2 or later  
License URI: http://www.gnu.org/licenses/gpl-2.0.html  

Extends the Phone Field with a Country Code Selectbox

## Description

Extension for GravityForms (WordPress) which applies the International Phone Input (http://intl-tel-input.com) to all Phone Fields.

## Installation

1. Upload `gravityforms-phone-extension` to the `/wp-content/plugins/` directory or upload the .zip through the 'Plugins' menu in WordPress
2. Activate the plugin through the 'Plugins' menu in WordPress
3. All Gravity Forms "Phone" fields are now using the International Phone Input

## Options

You can customize the behavior of your fields by initialising the library with optional parameters. (Available options: https://github.com/jackocnr/intl-tel-input#options)  

To do so, edit `assets/js/init.js` as follow:
```javascript
$field.intlTelInput({
		// Put your options here
	});
```


## Changelog

### 1.2.1
* Fix minor issues

### 1.2.0
* Improve Script and Style Loading

### 1.1.0
* Improve Plugin Structure
* Update intlTelInput to 11.0.11

### 1.0.1
* FIX: Remove 'http:' from $.get function in init.js to prevent issues on SSL Sites

### 1.0.0
* Initial Release
