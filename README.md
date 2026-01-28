## Plan
My plan going into this project was very simple. Firstly, I needed break down all the content into various secitions that I could group into parent containers. I applied parent divider classes to each of the following sections; Header, About, Portfolio, and Contact. I wrapped each of these parent containers with a red border so that when changes were made to the page, the effects were immediately clear. Secondly, I broke each section down further into child containers, wrapping these items in a blue border. Doing this allowed me to make small changes one at a time and see the live results of each change using 'Live Server' in Visual Code Studio. Then one section at a time, I made altercations to the parents and child class until they matched the provided template. 

## Header
For the header I created a set of dividers and placed them within a parent divider styled as a flexbox to line the two items horizontally. 

## About & Background
For the about section, I created a parent divider that houses the child items for the picture and for the "Hi, I'm Pete!" section. I created a third child item that contained the Background section, but left it outside of the about parent divider. I applied the flex styling to the parent divider to line the two contained child items horizontall.y

## Portfolio
I created a seperate class for the paragraphs in the portfolio section, I applied text-size: 14px to shrink the size of the text to the required font size. Like the two sections before, I applied a parent dividers that contained three child item; one per artwork. I used the flexbox to line them up horizontally and applied a margin to the children to better line them up and provide more space between the discriptions of the art. 

## Contact
I applied a div to the contact page to center the content with the above sections. 

## Additional notes 
I did not use any AI assistant with the completion of the code.
I did not make any changes to the colors or font choices, as I thought the provided colors worked well. 
I feel that my method to complete the assignment was well thought out and seperated the content into managable sections. My only concern is that the abundance of div elements I added combined with the preexisting article, and section elements may complicate the layout further down the road. 


## Changes 01/28/26
I moved the horiontal break out of the About container and placed it before the Portfolio container. This change better aligned the horizontal break with the provided example. This created more consistent spacing between each section. Additional I moved the picture in the About section to a center alignment using inline styling with the !important notation to overwrite the left alginment. I sumbmitted all changes via Github commit.