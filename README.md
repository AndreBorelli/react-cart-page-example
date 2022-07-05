# react-cart-page-example







## Exercise from John Smilga's course, where several simple React projects are taught:
    [https://www.youtube.com/watch?v=a_7Z7C_JCyo]



## Link of the course final setup:
    Prototype website link after configured, made available by the course author. The code available
    in this repository has some modifications made by me.
   
   
   [   https://react-projects-14-usereducer-cart.netlify.app/   ]

## Functionalities:
    Interactive cart page, who shows dynamically the amount of each item, you can change, 
    the amount of each of those items using buttons, delete the whole item and the whole 
    list if buttons;
    
    API fetch and await Loading;
    
    useReducer and useContext Hooks allies to useGlobalContext custom Hook use to simplify  and optimize code;

    Increase and decrease function made separately ('INCREASE' , 'DECREASE) or together ('TOGGLE_AMOUNT'), 
    both using useReducer; Both can be used, but on this one i choosed the function action ('TOGGLE_AMOUNT');

    Inline SVG instead of React-icons;

    ParseFloat toFixed method;

    Acess to the total amount of items;

    useReducer Hook to callback fetchData function every change in API's and other useReducer
    use to change dynamically the total cart's price.



## Changes regarding the course design:

    Two new css variables were created, changing the colors of texts,backgrounds, buttons and icons 
    to my enjoy;

   I Added my logo.
