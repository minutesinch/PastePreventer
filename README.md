#Paste Preventer
=====================

<p align="center">
 
![xcv](https://user-images.githubusercontent.com/11364402/28755333-5f413874-756d-11e7-826a-8d0b38eb8abd.jpeg)

</p>

Simple Jquery plugin to prevent copying and pasting in all browsers( focused on mobile browsers )
----------------------------------------------------------------------------------------------------
This plugin is based on answers from this [SO Question]( http://stackoverflow.com/questions/32796176/prevent-user-from-copying-text-on-browsers )


[Demo]( http://jsfiddle.net/pv6r0x1a/2/ )





Iinstallation:

```html
    <script src="pastepreventer.min.js"></script>
```



Usage:
```javascript

    $(document).ready(function(){
    
        $(".words").blockCopy({ // Block copy on elements which have 'words' class
            blockPasteClass : "noPasting",  // Optional: block pasting on inputs (or textareas) which have 'noPasting' class
            message:"Shame on you!"         // Optional: Message to show if user tried to paste
        });
        
    });

```
