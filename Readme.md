# Rainbow Creator UIColor Extension

The Rainbow Creator UIColor extension provides developers with easier methods to create custom colours.  Apple provides a limited number of pre-defined colours such as UIColor.blackColor() and UIColor.greenColor().  The Rainbow UIColor library adds over 1500 more colours but not even that may have the exact colour that you require.  


## Usage

To use the library download the file and import it into your project.  

Then you can change your code from

	let backgroundColour = UIColor ( red: 94.0/255.0, green: 7.0/255.0, blue: 95.0/255.0, alpha: 1.0 )

to the following

	let backgroundColour = UIColor  ( redValue: 94, greenValue: 7, blueValue: 95, alphaValue: 1.0 )

Note that because the alpha value in this case was 1.0 it could have been left off because the function has it set to that value by default.

There are also functions that allow you to create UIColor objects using a hexidecimal integer or string.

	let backgroundColour = UIColor ( hex: 0x42ac58, alpha: 0.75 )
	let foregroundColour = UIColor ( hexString: "#0f23ec" )
	
The setting of the alpha is available in both but if you leave it out then it defaults to 1.0.  (Please note that I have no idea what those will produce.  I just made them up as an example.)

## Future

Currently the extension works in Swift as that is what I primarily develop with.  If I get requests to port the extension over to Objective-C I will take the time to do so.  


## Contact

If there is some extra functionality that you would like see added please feel free to get in touch.  I'd be happy to look into it.  Or even say hi you can reach me on [@NrthrnRealities](https://twitter.com/NrthrnRealities) on Twitter.

## A Note About Spelling

I am terribly sorry about mixing up the spellings of colour and color.  I'm from Canada and we spell it with the 'u' and I can't get out of the habit.  However when it comes to function names, parameters, and other cases when it really counts I've strived to go against my instincts and spelt it without the extra letter as per the Apple standard.  In other cases I've allowed myself to spell it the proper way. :)  Please forgive me my little indulgence.