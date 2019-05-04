# clickTyper


 clickTyper is click.js based Component which provide animated automatic typing effect for click.js based application.
 This component dosn't use any external package , services or shared global states.
 
 ## Component :
 
 ```js
     <c-Typer />
 ```
 
 This Component takes Props for it's internal configurations.
 
 ## Props :
 
   typespeed   : This prop takes typing speed on micro seconds. It's default value is 1 seconds (1000ms).
     
   text        : This prop takes multiple strings seperated by *|* sign.
     
   erasespeed  : This prop takes typed text erasing speed on micro seconds. It's default value is 1 seconds (1000ms).
   
   endsymbol   : This prop takes symbol that should be at the end of animated text . It's default symbol is *|*

    
## Usage :
 
 ```js
 
 <c-Typer typespeed="100" erasespeed='90' text=" Hi, I am click.js | I am click typed component | I was created by Nirikshan Bhusal"/>
 
 ```
