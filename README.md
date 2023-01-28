# Landing Page Project

## Table of Contents

* [description](#description)
* [My Info](#My_Info)
* [Css Edit](#Css_Edit)
* [Edit1](#Edit_#1_After_Submit)
* [Edit2](#Edit_#1_After_Submit)


 ## description 
 ```bash
 a project to make the page with dynamic nav bar and  auto find the item which the user stay in it and highlight it in the nav bar with scroll smooth
 ```

 ## My Info
```bash
my name is yossif ali galal
email:yossifali149@gmail.com
phone:01062697154
```
## Css_Edit
```bash
i change some colores and add padding 
and i add a class called C_A_NAV to make the active nav diffrent from others 
What i do in js :
Select Elements with  id "TopBtn" And Put it into a variable called "mybutton"
Select Elements with  id "navbar__list" And Put it into a variable called "uLists"
Select All "section" And Put it into a variable called "selectAllSections"
create A list element
scroll into view
Go Top Button
calling ButtonAppear function
Change the h1 text
Nav creator
changing text
Making Variable To create "li" element 
Set nav name using Template literals
Append the element
choose Active Nav
Select Elements With "menu__link" Class
set bounding for sections
Using if condition to find the active sectoin
    IF TRUE
                    adding the class "your-active-class" To make it diffrent and active
                    addingthe class "C_A_NAV"  To make it diffrent and active
    IF FALSE 
                    REMOVE THEM

Calling findActive Function 
```

## Edit_#1_After_Submit
```bash
feedback:Your project could not be reviewed. Please resubmit after you address the issue noted below by the reviewer.
Hi,
On mobile and smaller screens the navlinks are going out of the bounds of the navbar. Please fix it.

i fix it by 

#navbar__list li{
    text-align: center; // to align text at center
    width: 20%;       // to give each item a width 20% of total width so it can be responsive
}


#navbar__list{
    display: flex;       // to make it flexbox
    align-items: center;  // to align items at center
    justify-content: space-between;   // to make a space between items
}

and i also give the     height: 60px;
```
## Edit_#2_After_Submit
```bash
Make the scroll smoothly as mentioned in feedback

i changed the nav height
```