This is a repo for a computer peripheral that can help blind people feel a computer screen.

Right now there are just some fabrication files, but I'll add some math documents and a few example functions in python or something.

I haven't finished the project so I dont have much software yet.


I want this information to be free to anyone who wants it. I'm putting an MIT license on it.

# Summary of Project:
- Represent pixels with pins
  - Instead of adjusting brightness for a pixel, the display adjusts height of a pin.
  - Text may be unreadable, but regions of text and general shapes should be visible.
  - The display is a relatively small 2D grid of pins with 10x10 resolution and 10mm/pin densiy.
- Motion
  - The display tracks position and rotation.
  - To feel different parts of the display, simply move the display like a mouse. (But it also tracks rotation)
  - Zoom in or out to feel the forest or the trees.
- Why
  - 3D design
    - There exists very little that I can find to help blind people design things in 3d.
    - Fusion 360 would be nearly impossible to use without at least getting a general idea of what the LED display is trying to communicate
    - The Tactile display should at least give the user enough information to work with.
  - Strictly Graphical Programs
    - Some programs like LabVIEW are basically imposible to use without eyesight. A tactile display would be a great tool for using LabVIEW without eyesight.
- Limitations
  - Text
    - The tactile display can't really be used to read text. It would be orders of magnitude faster and easier to use braille to read ordered text.
  - Depth Perception
    - The display can't determine the difference between a pixel representing a close object from a far object if the pixels are the same color.



You can contact me at andrew.mcclary@haikuergo.com

