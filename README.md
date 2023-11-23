# holy_grail
Hello everyone. I have made a small but effective project which will challenge our simple CSS knowledge. The project is Holy_Grail Website. It is just a model of most if the websites. I have taken total of 5 parts. Check the readme file. 



Header Section: 
=================
The first one is Header part which will have 
* max-height: 60px;


Footer Section: 
===============
The last and below part is footer part which will have 
*max-height: 100px;

It contains copywright details and we can also give social media links.


Middle Section:
=================

Above two sections are quite easy to code in minutes and simple. But here comes the tricky one. 

The middle section consists of 3 parts which are:
i) Navigation Bar
ii) Content Bar
iii) Advertisement Bar

I used flex to flex all three and flexed them in the row direction. 

----------------------
i) Navigation Bar: 
-----------------------
In the navigation bar, I given:

*max-width: 100px;

I have made a navigatory menu on the bar.
For them also I have used flex to allot them column direction. 

Note: Justify-content will not work effectively if we put default height to auto or some less size. So, I have givem 100vh.
      *Also, I given flex-shrink to 0, because the flex grow in content bar taking all the remaining empty space from navigation bar. To 
       avoid this and to prevent losing the default width of 100px I put flex-shrink to 0.


ii) Content Bar
----------------

In the content bar, I have given:
*flex-grow: 1; (To take all the remaining space from other two bars i.e navigation bar and advertisement bar.)

--Images:--

For image text-align not working to make it place at centre. So, I tried to use Flex. Flex is not worked for it single image. So, I made new div with id images and flexed it to justify-content: centre to place the image at centre.

*The text content is text-align: start only.

iii) Advertisement Bar:
-------------------------

In the advertisement bar also,
*width: 100px;

To avoid content box occupying it's allotted space the flex-shrink:0;

Inside this I have placed ads with images max-width, max-height of 80px.


***Thankyou***
