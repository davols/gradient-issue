# gradient-issue
Example project of gradient issue

So it seems that it's possible to create drawables that refer to attributes if the drawable is of a shape that's not a gradient. Attributes in drawables have been added either in API 21 or API 23. Here are some screenshots of using gradient drawables together with attributes.

The layout consists of 4 views.
View1: Solid drawable with attrs.
View2: Gradient drawable with reference to attrs
View3: Gradient drawable with reference to attrs
View4: gradient drawable with reference to colors.

The issue is with View2 and View3 with API < 26. 
How it should look: 
![nexus4api27](https://github.com/davols/gradient-issue/blob/master/emulator_nexus4_api27.png?raw=true)

Issues with actual phone (Sony with API24):
![sonyapi24](https://github.com/davols/gradient-issue/blob/master/sony_api24.png?raw=true)

More examples that show the issue:
Emulator api 25
![nexusapi25](https://github.com/davols/gradient-issue/blob/master/emulator_pixel_api25.png?raw=true)
Emulator api 24
![nexusapi24](https://github.com/davols/gradient-issue/blob/master/emulator_nexus5x_api_24.png?raw=true)
Emulator api 23
![nexusapi23](https://github.com/davols/gradient-issue/blob/master/emulator_pixel_api23.png?raw=true)
