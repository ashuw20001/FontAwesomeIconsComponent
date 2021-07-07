# Fontawesome Icons Kony Component 

<table>
  <tr>
    <td>
    <img width="312" alt="Screen Shot 2021-07-07 at 11 07 27 AM" src="https://user-images.githubusercontent.com/5238143/124716018-a83f6900-df14-11eb-9ff3-238423b6171f.png">
    </td>
    <td> 
    <h4>
      1. Scalable/Vector web font icons for mobile & desktop application </br> </br> 
      2. No Blur issues for any resolution of mobile devices.</br> </br> 
      3. Easy to use in Kony project.</br> </br> 
      4. Can accomodate any color and size.</br> </br> 
      5. Supported Platform's: Android,iOS & Desktop web.</br> </br> 
      6. onTouchEnd event support.</br> </br>
      7. Dynmaic icon assignment method avaiable.</br> </br> 
      8. No need to maintain all resolution images (mdpi,hdpi,xxdpi,xdpi or 2x-3x images), hence application size can be saved.</br> </br>
      9. Very lightweight font icons to load on mobile screens for both iOS & Android platform.
      
      
  </h4>
    </td>
    </tr>
  </table>


<h1>What is FontAwesome Icons?</h1>
Font Awesome is a webfont used by websites designer & developers for icons instead of traditional old images.
Its flexible in terms of coloring, sizing & stacking on top of other background styles using skin properties.

<h1>FontAwesome categories</h1>
<ul>
  <li>
<a href = "https://fontawesome.com/v5/cheatsheet/free/solid">Solid Icons </a></li>
  <li><a href = "https://fontawesome.com/v5/cheatsheet/free/regular">Regular Icons </a></li>
  <li>
<a href = "https://fontawesome.com/v5/cheatsheet/free/brands">Brand Icons </a></li>
 </ul>
 
 <table>
  <tr>
    <td>
      <img width="1651" alt="Screen Shot 2021-07-07 at 11 18 23 AM" src="https://user-images.githubusercontent.com/5238143/124717592-54358400-df16-11eb-81c7-1f83eb05bfe4.png">
      </td>
    <td>
      <img width="1663" alt="Screen Shot 2021-07-07 at 11 17 30 AM" src="https://user-images.githubusercontent.com/5238143/124738409-f27f1500-df29-11eb-822d-dda2866eec21.png">
      </td>
    <td>
      <img width="1663" alt="Screen Shot 2021-07-07 at 11 17 30 AM" src="https://user-images.githubusercontent.com/5238143/124716422-1e43d000-df15-11eb-8218-35fd79d27aeb.png">
      </td>
    </tr>
  </table>

<h1>How to use this fontawesome component in Kony Visualizer?</h1>
Steps :<br>
1. Download the zip file.<br>
2. Import it in your Kony Project (Project Explorer->Templates->Component->import)<br>
<img src="https://user-images.githubusercontent.com/5238143/124718143-daea6100-df16-11eb-8c75-d5f07ba6f232.png" /><br>
3. Insert the component in Form directly and change the skin properties according to requirement.<i>(color,font-size,weight)</i><br>
4. Copy the unicode value from website of respecitve icon and place in properties tab 

![image](https://user-images.githubusercontent.com/5238143/124721988-aaa4c180-df1a-11eb-940a-d8874b4083d1.png)  
   <img width="415" alt="konyvisualizer" src="https://user-images.githubusercontent.com/5238143/124721601-4eda3880-df1a-11eb-9320-5b86a064f313.png">

<h3> Note : Select the proper font family depends on icon type you choose it from Above URL's</h3>
<h4>If you set the solid icon, so make sure to select the font-family FontAwesome5_Solid and similar way for brands and regular.</h4>
    1.FontAwesome5_Brands.<br>
    2.FontAwesome5_Regular.<br>
    3.FontAwesome5_Solid.<br>

<h1>Methods Available</h1>
<ul>
  <li>onTouchEnd</li>
  <li>setFontAwesomeIcon</li>
  <li>getFontAwesomeIcon</li>
  <li>setVisiblity</li>
  <li>setEnabled</li>
 </ul>
    
<h1>Code Snippets</h1> 

```
this.view.FONTAWESOMEWIDGET_ID.onTouchEnd = function(){
//TODO user clickevent
}
```

```
this.view.FONTAWESOMEWIDGET_ID.setFontAwesomeIcon(FontAwesome_SOLID.address_book)
//FontAwesome_REGULAR.XXX
//FontAwesome_BRANDS.XXX
```

```
this.view.FONTAWESOMEWIDGET_ID.setVisiblity(true); // boolean true/ false
```

<h1>Platform Availability</h1>
<ul>
  <li>Android</li>
  <li>iPhone</li>
  <li>Desktop Web</li>
 </ul>



