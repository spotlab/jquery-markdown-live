# jQuery Markdown live
Minimalist but customizable jQuery markdown editor with live preview

[Demo](http://www.spotlab.net/jquery-markdown-live/demo.html "Demo jQuery Markdown live")

![Sreenshot](http://www.spotlab.net/jquery-markdown-live/screenshot.png)

###Installation

    bower install jquery-markdown-live

###Configuration
Editor bar can be set with HTML only (look **demo.html** for more customization examples)

    <ul class="bar">
        <li title="Bold" data-before="**" data-after="**" data-placeholder="some text in bold">
            <i class="fa fa-bold"></i>
        </li>
        <li title="Italics" data-before="*" data-after="*" data-placeholder="some text in italic">
            <i class="fa fa-italic"></i>
        </li>
        <li title="Link" data-before="[ " data-after="](http:// &quot;Link title&quot;)" data-placeholder="link">
            <i class="fa fa-link"></i>
        </li>
        <li title="Image" data-before="![Alt text](" data-after=")" data-placeholder="http://">
            <i class="fa fa-picture-o"></i>
        </li>
    </ul>
			
Setup your preview html :	
	
    <div class="preview"></div>

Setup your texarea html :  
**data-bar** : class of the bar to get events  
**data-preview** : class to target the preview   

    <textarea data-bar=".bar" data-preview=".preview"></textarea>

Init the editor :

     $('textarea').markdownlive();
     
 


