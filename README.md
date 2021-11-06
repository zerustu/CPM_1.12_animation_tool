# CPM_1.12_animation_tool
A tool to convert blockbench animation file to expression that can be add use in 1.12 model

this respitory have two files:

-[a PDF](https://github.com/val9k/CPM_1.12_animation_tool/blob/main/how%20to%20use%201.12%20CPM%20interpolation.pdf) to better explane how to use the tool

-[CPM_interpolation.html](https://val9k.github.io/CPM_1.12_animation_tool/CPM_interpolation_1.12.html) : upload your animation file from blockbench on this page and put the output lines in the model.json. more info in the PDF

# Info :
This tool use a fourier aproximation that only work on periodic function : the first keyframe and the last keyframe should have the same value, or else it will not work.

This output is a 1-periodic function that will complete a loop when the timer variable goes from 0 to 1 (or any interger n to n+1)
[in the pdf, the cos and sin value have strange periode, don't worry about it, the screen shot are from an odler version :). ]

# Credit :
This tool was made by my, for any question, you can contact me on discord (▄█▀zerustu▀█▄#0075) or post an issue on this github.

thanks to dearFox for his interpolation tool, this project start from his tool
and tanks to gamepiaynmo for creating CPM.

you can find dearfox's interpolation tool (1.16) [here](https://github.com/DearFox/cpm-tools) and my 1.16 tool [here](https://github.com/val9k/CPM_catmull_rom_interpolation)
