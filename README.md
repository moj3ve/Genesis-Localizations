## Genesis Localizations

To submit a new translation for Genesis, fork or clone this repository. Create a new folder called language.lproj, where "language" is the identifier for your language. For a full list of language identifiers refer to [this.](https://www.ibabbleon.com/iOS-Language-Codes-ISO-639.html) Copy each ".strings" file from defaults.lproj to your new .lproj folder. Following the example below, change the text inside each ```<string></string>``` accoring to the correct translation. Finally, make a pull request with the changes, and I will merge them here.

### Currently supported languages

* English

## Localizing Text

```objective-c

<plist version="1.0">
	<dict>
		<key>GLOBAL_ENABLED</key> // Do not change this line
		<string>Enabled</string> // This is what you would translate and change
	</dict>
</plist>
```
