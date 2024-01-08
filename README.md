For the time being, due to this being for personal use, this README will serve as a log of my work on this project.



1/4/2024:
    14:30 - 15:50
        setting up code suite for postscript
        setting up OpenSCAD
        Light research on Vera Molnar
        Looking at project topics on syllabus
        Looking at Bridges Archive
        Parquet Deformations look SUPER interesting tbh
        
1/5/2024:
    9:13
        setup copilot, added to the repository's codespace
    13:15 - 18:40:
        taking notes on postscript
        remaking examples
        imported examples
        re-did ps/esp viewing to allow ipad to do it
        made keybind so "ctrl+alt+p" while in postscript file (.ps or .eps) will automatically create a pdf of the code
        a whole lot of configuring devContainer.json
        
1/6/2024:
    15:00 - 18:00:
        making dragon curve in postscript
        learning l-systems
            omg this might be what I focus on
        imported l-system examples to study
        kinda made a fern in wind?
        to do: read this paper on l-systems in    
          postscript; "https://www.cstug.cz/bulletin/pdf/2012-1.pdf" (english starts p11)
          
1/7/2024:
	13:20 - 14:30:
		figuring out how exactly the formulas for l-systems work via dragon curve
		planned l-system for hilbert curve (havent tested yet)
    18:00 - 21:20:
        making the hilbert curve
            had issues with some Fs not drawing, turns out I needed to always draw F rather than checking N was 0, which worked for dragon curve bc it *replaces* previous lines with corners, rather than just adding corners
            I can just define F to draw (i can even skip pop if i only dup N |X|+|Y| times in X and Y, but I want to pop to keep consistent when I only work with F)
            also I need to remember to keep the sum of rotations = 0 mod 360
        made it, scaled it, centered it. (note that only a .eps can restrict output with bounding box)
	22:10:
		i think ill use ¿? instead of BE for l-systems' [] (option+shift+? or RightAlt+? to get ¿)
  
1/8/2024:
	14:50:
		i think ive decided on my focus; mathematically defined organic/natural shapes and structures, especially using l-systems and the golden ratio
