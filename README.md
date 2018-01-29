# svg-graph
This svg line chart or graph is easy to use

# User Manual
This is a very simple way to implent svg graph or svg chart.

if you run the demo you will find a edit option where you have to pur a max value and chart values,
also the other attributes you can use or not.

After submitting values and properties you will see a chart.
Now if you click on 'html' switch you will get the code, that's it, only this you need to use in your html.

Download js file from *downloads* folder and call the *min.js* file

# guidence in js 
# 
* on window load or document load call this function 

svgGrpah();

example:: 

    <script type="text/javascript">
       window.onload = svgGrpah;
    </script>

or if you are calling multiple functions in onload

     <script type="text/javascript">
       window.onload = function(){
	 svgGrpah();
      };
    </script>

# Demo link is here

* https://devsubhajit.github.io/svg-chart/index.html

# How to add attributes ( Options )
* First of all, as its now only line graph, we have to set an html attribute as "data-graph='line'"
* Example: data-graph='line' on your element

Others two span are represented as "max value" and "all values", these are the dynamic part only developer will make it.
Like "data-graph='line'", we are going to add other attributes

1. Background Color: data-graphbg='#3630a9'
2. Grid Color: data-grid='#c4c4c4'

Other attributes comes under the attribute of "data-style", these are added with a 'comma (,)' only 
1. Line color: "data-style='color:#4dc137'"
2. Fill mode : "data-style='color:#4dc137,mode:fill'"
3. Gradient: gradient:positive = "data-style='color:#4dc137, mode:fill, gradient:positive, gradient-colors:#74b847-#ad3477'" (from - to)
4. Dots : dots:true, dot-style:#5bbf63, dot-border:#f5dc2c-2 = first attribute is to active dots, second for dots color and third one has two values one is border color and after '-' its border width which is '2'
So adding Dots, the full code looks like = "data-style='color:#4dc137, mode:fill, gradient:positive, gradient-colors:#74b847-#ad3477, dots:true, dot-style:#5bbf63, dot-border:#f5dc2c-2'"
5. Curved Corner: If we want a curved corner, we have these facility too, use this : 'corner:curved' inside "data-style"

# Thanks for using "svggraph"
Hope you will like it