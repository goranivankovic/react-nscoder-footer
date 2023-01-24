
<h1>React responsiv Footer with props</h1>



<h4>react-nscoder-footer is a React component to build  simple and responsive footer component</h4>



## Installation

<h5>Use the npm package manager to install react-nscoder-footer</h5>

</br>





```bash
npm i --save react-nscoder-footer
```


</br>


[Link with Example](https://goranivankovic.github.io/react-nscoder-footer/)



</br>




  <img src="https://media.giphy.com/media/VYDcGcFl0UvgtAfcsq/giphy.gif" heigt="500" width="50%" />
  
  
  <h4>
  Responsive footer with props.</br>
  Technologies use: react, react-hooks, css.</br>
  Don't waste your time building your own footer, just simple downloaded with npm.</br>
  Required: Node.js, NPM, React.</br>
  Simple to use send props in your main components. </br>
  Add colors of: text-headline, border-headline, background, text-rows.<br/>
  Add row headline-names , row-items, footer-items. </br> 
  I hope you liked and feel happy to enjoy and download.</br> 
  Position of FooterBar is relative.
  

  </h4>
  
  
  
  ## Usage

```javascript

import react from 'react';
import FooterBar from 'react-nscoder-footer';

//Import Css File in Your Component from node_modules/react-nscoder-footer/App.css. 
// Be aware of your path,it depends where you're component is.

import '../node_modules/react-nscoder-footer/App.css'

function App() {
  return (
    <div>


    
      <FooterBar 

      //For Better Performance refresh a website when you make changes.



   
    //Change background color   
      bgColor="#0D5DCD"

      //Change text color
      textcolor="white"
 
     //Change headline color of 4 rows
      headlineColor="white"

    //Change border color of 4 headline itmes 
      bordercolor="#FFA500"

      //Change Color on Mouse on 
      hoverTextColor="#FFA500"




     //Change first row headline
      firstHeadlineName="PRODUCTS"
    
      //Change first row items minimum 3 items - Maximum 6 items for responsiveness.
      //If second item value == true. Item will be displayed. Else item will not be displayed.
      firstROWitems={[["Web Sites",true],["Web Design",true],["Custom API",true],["30 Day Kick Start Plan",true],["Web Solutions",true],["Data AI",false]]}







     //Change second row headline
      secondHeadlineName="COMPANY"
 
      //Change second row items minimum 3 items - Maximum 6 items for responsiveness.
      //If second item value == true. Item will be displayed. Else item will not be displayed.
      secondROWitems={[["Years Active",true],["Transparent",true],["Be a Part of company",true],["Since 1976 - ",true],["Together We Create",false],["Business Leader",false]]}






     //Change thred row headline
      threeHeadlineName="COMMUNITY"


      //Change thred row items minimum 3 items - Maximum 6 items for responsiveness.
      //If second item value == true. Item will be displayed. Else item will not be displayed.
      threedROWitems={[["footballapiuk@gmail.com",true],["Discord",true],["Snapchat",true],["Facebook - ",false],["Youtube",false],["Instagram",false]]}







     //Change four row headline
      fourHeadlineName="CONTACT US"

     //Change four row items minimum 3 items - Maximum 6 items for responsiveness.
      //If second item value == true. Item will be displayed. Else item will not be displayed.
      fourROWitems={[["footerpackage@gmail.com",true],["Support Centre",true],["Newsletter",true],["@facebook",true],["Youtube Channel",true],["@instagram",true]]}




      //Change text color Of three Bootom Items

       threeBottomItemsColor='white'


     //Change Three Bottom Items.
    //If second item value == true. Item will be displayed. Else item will not be displayed.
    //Best practice is too have 3 items.
     threeBottomItems={[["2023TERMS & CONDITION",true],["FOOTER PACKAGE",true],["@ PRIVACY POLICY COOKIE",true]]}

      
      
      />



    
    
     
    

    </div>
  );
}

export default App;

```

</br>

</br>

<img  align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/npm/npm.png" alt="npm" />https://www.npmjs.com/package/react-nscoder-footer

</br>


<img align="left" alt="GitHub" width="26px" src="https://raw.githubusercontent.com/github/explore/78df643247d429f6cc873026c0622819ad797942/topics/github/github.png" />https://github.com/goranivankovic/react-nscoder-footer


</br>
## License

[MIT](https://choosealicense.com/licenses/mit/)

<hr></hr>

##
[developed](https://github.com/goranivankovic)


