# Things that i've lerant during revision of prerequisites

* Emmit Shortcuts For Fast Phase Coding 
  
1] to merge unrelated history from remote repo to local repo
*command: git pull origin main --allow-unrelated-histories*

2] for fast phase coding: *command + ctr + down arrow*
 
3] _Shortcut : comment, fast phase coding, Ect.

- table>tr>th*(number of how many you want)
- In form elemet the name attribute is mainly used to reference element in javascript as we write all logics in javascript file

4] Classes and ID's in HTML 
- where the classes and ID's in html is used to select the element.. to *target* to *select* the element in html we used the classes and Id's
- use cases will be different of classes and id's as per styling
- where the CLASSES denoted using "." and  the ID denoted using "#"
- there can be multipel classes but the by convention ID will be only one (*Good practice uk*)
- to target unique element we have ID

  5] HTML <span> Element :
  - It is generic insline container for phrasing the content
  - Used to group the element for syling perpose
  - is very much like a <div> element, but <div> is a block-level element whereas a <span> is an inline-level element


# Dom Manipulation
Updating and Altering Documens by inspecting the web page
- Using JSX(JavaScript eXtended) directly manipulate the web page from chrome console(web Browser)
- Manipulation done using various methods Such as
- [getElementById, GetAttributes, SetAttributes etc..]
- Main part of this pricess to add or update contect using DOM.
- using [.textContent, innerHTML, innerText etc....]
  
  1) InnerText : for just showing the priview which is visible.
  2) InnterContent : all contect including hide contect.
  3) innerHTML : contect with the elements of html.
 
# DOM Query Selector[Used in real word]
- using query sqlector we can directly get the element and manipulate it 
- where it will returen the element you wanted
- THE BEST WAY TO MANIPULATE(UPDATATION, DELETATION ETC) THE DOCUMENT OBJECT MODEL
- E.G
document.querySelector('<element>')

*Here how it works* :
- 1
![DOM_Quert_sel](https://github.com/cnnarayanchavan/Grind-1313/assets/113028954/bcb03f67-0193-4ec0-9761-7a929b8d3b2e)

- 2
![DOM_Quert_Selector](https://github.com/cnnarayanchavan/Grind-1313/assets/113028954/de765653-c79e-4917-91d1-be32c6aad659)




[Here the querySelectorALL is return the *NODELISTS* of elements you wnat]

- where *NODELISTS*  which appear like array but are not the pure arrays
- also has the array menthods in define in prototype such as foeEach ect..

*HERE IN querySelectorAll WE HAVE TO DEFINE THAT WHICH ELEMENT WE WANT TO MANIPULATE OR UPDATE AS IT RETURN THE NodeList  THAT'S THE MAJOR DIFFERENCE BETWEEN querySelector AND querySelectorAll*
- as it returns the nodelist we can use the forEach() method for faster manipulation
- but if we want to use the map or other methods we have first convert the NodeList into the Array then we can use other array methods.
- e.g
-  ![Query Selector ALL](https://github.com/cnnarayanchavan/Grind-1313/assets/113028954/fdefd25f-428f-4761-9025-1fd9144420c0)

# The nect method getElementbyClass.
- here the method getElementbyClass return the Html collection which is not (again) array.
- so to apply the array methods we have to first conb=vert it into the array by using
- Method = *Array.from(<Name>)*
  





