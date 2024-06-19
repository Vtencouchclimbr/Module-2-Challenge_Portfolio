# Module-2-Challenge_Portfolio

## Technology Used 

| Technology Used         | Resource URL           | 
| ------------- |:-------------:| 
| HTML    | [https://www.w3schools.com/html/default.asp](https://www.w3schools.com/html/default.asp) | 
| CSS     | [https://www.w3schools.com/css/default.asp](https://www.w3schools.com/css/default.asp)      | 
| CSS     | [https://developer.mozilla.org/en-US/docs/Web/Guide](https://developer.mozilla.org/en-US/docs/Web/Guide)      |  
| Git | [https://bootcampspot.instructure.com/](https://bootcampspot.instructure.com/)     | 

## Description

This is my second project for the bootcamp. This project is meant to show what we have been learning so far and serve as a template to improve upon. This exercise includes manipulating images, adding links to completed projects for future use, as well as using semantic html elements and other fundamental concepts. For this challenge, I took extra time to explore flexbox. This is, hopefully, reflected in my code and structure.

Visit the deployed site here: https://vtencouchclimbr.github.io/Module-2-Challenge_Portfolio/
Visit the github repo here: https://github.com/Vtencouchclimbr/Module-2-Challenge_Portfolio


An example of multiple link types and containers/divisions shown below:

~~~html
<section>
    <div class="container1">
        <div style="border-color: #091016; border-style: ridge;">
        <div class="mypic"><img src="Me.jpg" alt="Picture of myself" width="250" height="200"></div>
        <div class="mypic"><h1>My name<br>is Jesse</h1></div>
        <div class="mypic"><h5 style="color: rgb(233, 190, 49);">Click the links<br>to learn more</h5></div>
    </div>
    <div>
        <nav>
            <ul class="link-list">
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
            <li><a href="#projects">Projects</a></li>
            </ul>
        </nav>
    </div>
</section>
<aside style="float: right;">
    <div class="container2">
        <ul>
            <div><li class="image"><img src="game.jpg" alt="gamer" width="150" height="150"></li></ div>
            <div style="text-align: center; padding-bottom: 100px;"><li><a href="https://freegames. org/">Game</a></li></div>
            <div><li class="image"><img src="matrix.jpg" alt="code falling" width="150"     height="150"></li></div>
            <div style="text-align: center;"><li><a href="https://developer.mozilla.org/en-US/docs/ Web/Guide">Code Library</a></li></div>
        </ul>
    </div>
</aside>
~~~

 Here is an example of the flexbox CSS

~~~css
.container1 {
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 50px;

}

.mypic {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 7px;
  font-size: 20px;
  text-align: center;
  border-color: #091016;
  border-style: ridge;
}

.link-list {
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 7px;
  font-size: 20px;
  margin-right: 30px;
  text-decoration: none;
  list-style-type: none;
}

nav a:hover {
  background-color: var(--orange);
  font-size: 35px;
}

ul {
  list-style-type: none;
}
~~~



## License

This is the section where I will eventually put a license