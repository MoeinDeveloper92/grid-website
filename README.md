box-sizing=> this feature allows developer to add padding and border withought adding it to the width
of the box. it is recmmendded to add it to the unicersal property above the stylesheet,

line-height=> we make use of lineheight to spread thing ot a little bit.

In CSS we should try to learn make our CSS code modular, which means we need to mkae the code reusable.
for instance have a class for flex/ have class for grid/ for frid with different collumns/ if we want to make a preant element flex / we just need to define flex and call flex class and thas it. there is no need to define this propertis and features on every single element.

\*\* keep in mind that, Justify content in flex and grid always pertain to the main-axis, while align items always pertain to cross axis.

\*\* if you have variables which has repeated over and over it is better to put it inside te variable
:root{
--bg-primary:#123123
}

///////////////

hwo to add slant in the css/ like a tint
by before and after element we can achive this

what is REM unit in CSS=>Basically it is ia multiplier of a parent element.
for isntance by default the parent elemnt is 16 px, and if we define a parent element size 2rem we will have 32 px of size.
////////
