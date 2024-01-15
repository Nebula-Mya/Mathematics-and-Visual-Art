# For the time being, due to this being for personal use, this README will serve as a log of my work on this project.



## 1/4/2024  
14:30 - 15:50  
> setting up codespace for postscript
> 
> setting up OpenSCAD
> 
> Light research on Vera Molnar
> 
> Looking at project topics on syllabus
> 
> Looking at Bridges Archive
>  
> Parquet Deformations look SUPER interesting tbh  
        
## 1/5/2024  
9:13  
> setup copilot, added to the repository's codespace

13:15 - 18:40  
> taking notes on postscript
> 
> remaking examples
> 
> imported examples
> 
> re-did ps/esp viewing to allow ipad to do it
> 
> made keybind so "ctrl+alt+p" while in postscript file (.ps or .eps) will automatically create a pdf of the code
> 
> a whole lot of configuring devContainer.json
        
## 1/6/2024  
15:00 - 18:00  
> making dragon curve in postscript
>  
> learning l-systems
> 
>> omg this might be what I focus on
>>
> imported l-system examples to study
>
> kinda made a fern in wind?
>
> to do: read [this paper](https://www.cstug.cz/bulletin/pdf/2012-1.pdf) on l-systems in postscript (english starts p11)
          
## 1/7/2024  
13:20 - 14:30  
> figuring out how exactly the formulas for l-systems work via dragon curve
> 
> planned l-system for hilbert curve (havent tested yet)

18:00 - 21:20  
> making the hilbert curve
> 
>> had issues with some Fs not drawing, turns out I needed to always draw F rather than checking N was 0, which worked for dragon curve bc it *replaces* previous lines with corners, rather than just adding corners
>> 
>> I can just define F to draw (i can even skip pop if i only dup N |X|+|Y| times in X and Y, but I want to pop to keep consistent when I only work with F)
>> 
>> also I need to remember to keep the sum of rotations = 0 mod 360
>> 
> made it, scaled it, centered it. (note that only a .eps can restrict output with bounding box)

22:10  
> i think ill use ¿? instead of BE for l-systems' [] (option+shift+? or Alt 0191 to get ¿)
  
## 1/8/2024  
14:50  
> i think ive decided on my focus; mathematically defined organic/natural shapes and structures, especially using l-systems and the golden ratio

16:00 - 18:50
> making koch snowflake for practice
>
>> trying to figure out why its not working
>>
>> it wasn't working because I forgot to decrement depth counter and dup for F's in the initial state
>>
> making simple tree fractal for practice with branching
>
> <details><summary>planning on making a sierpinski via a tree as shown by this gif:</summary>
>
> ![sierpinski triangle is just a wide 3-branch tree w/o a trunk](https://upload.wikimedia.org/wikipedia/commons/a/a9/Fractal_tree.gif)</details>

20:10 - 22:10
> cleaned up simple tree fractal to optimise it
> 
> added shortcut to type ¿ with "shift+alt+/", same as on the ipad
>
> made a sierpinski triangle tree
>
>> learned that, because scaling is saved (and restored by branching), basic scaling with depth doesn't need to use the current depth, ie halving each time is just 0.5 dup scale in F

22:40
> idea for using l-systems for art pieces!!
>
>> do photography focusing on plants and tress and then replicate it with mathematics, with the final piece being some kind of combination of both parts
>> 
>> my first thought was overlaying them, but that might be hard to make look good, though tastefully putting the parts next to eachother might work

## 1/9/2024
9:00 - 9:20
> looked through pictures i have (from me or pa) to use for practice, as its raining too much today to take any new ones and i want a proof of concept for class tomorrow

12:40 - 14:45
> imported practice photos taken by me, pa, and ma
>
> made a l-system for a shrub in ma's solstice canyon pic

17:30 - 18:50
> updated shrub to match photo more closely
>
> experimented with replacing orig. shrub with generated

20:00 - 21:30
> finished a proof of concept with the solstice canyon greenery shrub

## 1/10/2024
14:30 - 16:00
> added random angles to simple tree
>
> omg i should introduce randomness to the equations!
>
> i want to try generating knots (fractal?) using l-systems (use a lambda element to close openings for overlaps)
>
>> started working on this

17:20 - 19:00
> worked on fractal trefoil

20:00 - 22:22
> worked on fractal trefoil

## 1/11/2024
12:25 - 1:08
> worked on a stochastic (probability to equations) l-system plant

## 1/15/2024
> edited and uploaded the best pic ive gotten so far for this project, the weather has been very limiting
