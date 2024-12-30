# In this seection we will learn 
## Selectors 

* Element selector
* Class selector
* Id selector 
* Attribute selector
* Universal selector

## How does it look like?
### general selector
Selector{<br/> 
    property:vaule;<br/> 
   
}<br/> 

#### Element selector
The element selector reference all of the HTML elements that call in the same name,for example `<p>` `</p>` is a HTML paragrph element.
the selector be:

p{<br/> 
    property:vaule; <br/> 
}<br/> 

#### Class selector - (.)
The Class selector reference all of the HTML elements with the same class name for example `<p class= "red_p">` `</p>` is a HTML paragrph element with class name.
the selector be:

##### Must start with point
.red_p{<br/> 
    color:red; <br/> 
}<br/> 

#### Id selector - (#)
The ID selector reference single HTML element with the same id for example `<p id= "Error">` `</p>` is a HTML paragrph element with uniq id name (can be apear only one).
the selector be:

##### Must start with #
#Error{<br/> 
    color:red; <br/> 
}<br/> 

#### Attribute selector - ( [] )
The Attribute selector reference all HTML elements with the same Attribute for example `<a href = "www.google.com" >` `www.google.com` `</a>`.

a[`href`]{<br/> 
    color:red; <br/> 
}<br/> 

p[`draggable = True`]{<br/> 
    color:red; <br/> 
}<br/> 

#### Universal selector - (*)
That means apply for all the HTML file 

*{<br/> 
    color:red; <br/> 
}