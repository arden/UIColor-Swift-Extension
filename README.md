# UIColor-Swift-Extension
A UIColor Extension written in Swift for convenience purposes. <br>
![ScreenShot](/screenshots/apple_swift.png)


This extension: <br>
1. Saves your time from converting Hex codes to RGB colors manually <br>
2. Gives you access to more standard or sophisticated colors with much convenience
<br>
<h2>How to use:</h2> 
1. Drop this extension file into your Swift project
2. Instantiate UIColor
3. Implement the delightful methods!

**Example1** <br>
let superAwesomeColor = UIColor() <br>
self.view.backgroundColor = superAwesomeColor.convertHexStringToColor(**"Insert the hex color code string here"**) <br>
**Example2** <br>
let amazingColor = UIColor() <br>
self.view.backgroundColor = amazingColor.convertHexToRGB(**Insert your UInt32 Color Hex Code here**)
<br>
**Example3** <br>
let delightfulColor = UIColor() <br>
self.view.backgroundColor = delightfulColor.**Insert the delightful color methods provided to you**()

