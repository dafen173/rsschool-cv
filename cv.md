# __Olexandr Nikandrov__
#### Junior Front End Developer

![my-photo](/my-photo2.jpg)

## Contacts
- __Location:__ Kyiv, Ukraine

- __Phone:__ +380974698757 (Telegram, Viber)
* __Emeil:__ [dafen@ukr.net](dafen@ukr.net)
* __Discord:__ Olexandr Nikandrov (dafen173)
* __GitHub:__ [dafen173](https://github.com/dafen173/)
* __LinkedIn:__ [LinkedIn](https://www.linkedin.com/in/olexandr-nikandrov-a0175875?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_contact_details%3BBzmhToCCTe22u92fjoUE2w%3D%3D)

## About Me
About three years ago, I started to learn HTML and CSS using the HTML Academy resource. Then I learned JS using FreeCodeCamp and Udacity.

## Skills
- Javascript ES6, HTML5, CSS3, Bootstrap
- Node.js
- REST API
- JSON, XML, AJAX
- Git, Github
- PostgreSQL, MongoDB
- Understanding principles of OOP and functional programming
- NPM scripts, Webpack, Parcel, Babel, Prettier
- Postman (beginner), Docker (beginner)

## Code Example
6 kyu 
Array Deep Count
```
function deepCount(a){
  let res = 0
  res += a.length
      
  function calc (arr){       
    for (let i = 0; i < arr.length; i++){      
      if ( Array.isArray(arr[i]) ){
        res += arr[i].length   
        calc(arr[i])   
      }      
    }  
  }
  
  calc (a)  
  return res
}

console.log(deepCount( [1, 7, 2, [3, 7], [4, 8, 9]] ))  // 10

```

## Experience

### Project 1.
This project is a customer management system built with React, Node.js,
Express, PostgreSQL and Redux.


Initial task condition
Create a simple website with two pages: List of Users, List of Groups for
Users.
Description of the first page: List of Users consist of: username,
created,group, actions. username – User nickname created – Date of
creating the user group - Group, to which the user will be added actions –
two buttons 'Edit' and 'Delete' Also, under the list, there should be a
button ‘Add User' for editing and adding new pages with such fields:
username (text input) and group(select).
Description of the second page: The list of groups should consist of: ID,
Name,Description, Actions. Actions – Edit and Delete buttons Also,
under the list,there should be a button Add Group For editing and adding
new pages with such fields: Name (text input) and Description (text
input). Group deletion is impossible if the user is assigned to this group.
[Link to this project](https://github.com/dafen173/react-redux-user-manage)

### Project 2.
Wrote and launched a telegram bot for CTC Capital UA (my current place
of work from 2008). With it, you can find out our exchange rate, the next
arrivals of goods to our warehouse, quickly calculate the sides of the
screen in relation to the format, etc.
Used Telegram API and Node.js.
[Link to this project](https://github.com/dafen173/real-bot-ctc)

## Education
- __University:__ National Technical University of Ukraine 'Kyiv Polytechnic Institute'. Faculty of Electronics. Department of Sound Engineering and Information Registration

- __Courses:__
    - HTML Academy
    - FreeCodeCamp
    - Udacity

## English
A2 (Limited Working)
