## Overview

In the code, we have 3 arrays of bitmaps. A bitmap is what your screen is drawing — it tells each of the 128x128 pixels what color it should be. Each array maps to either the left, right, or center button. To make a new animation, you will have to:

1. Add your own bitmaps
2. Put each bitmap into a different array, depending on whether you want it displayed through the left, right, or center button
3. Update the size variables to tell the code how many frames you want to cycle through for each button

### How do you even make a bitmap?

You can upload your own PNG to an [image2cpp site like this](https://javl.github.io/image2cpp/). You'll want to make sure your image is no bigger than 128x128 pixels (you can scale it on the site). I would recommend making a bitmap of this size exactly, or else you'll have to add a few additional display commands to change the background (feel free to do that if you have experience working with the Adafruit display library!).

If you generate your own bitmaps, you'll probably want to **scale to fit keeping proportions**, and **center horizontally**.

Once that is done, you can generate code and copy that over to your Arduino file!

### How do you edit the code?

In the code, you'll see areas marked as `OPTIONAL TODOs`. You can follow the instructions there. Once you define your bitmaps, we also recommend collapsing the sidebar so you won't have to scroll through long bitmaps every time.

That's it! Reflash the code and you should be good to go.
