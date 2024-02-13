# Lesson3-Sushi-header 😊

#### 1.Create sections directory inside css directory then 
#### Create sections/header.css file
![Lesson3-01](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-01.png)
#### 2. uncomment  ``` @import url("sections/header.css");``` in style.css file.

![Lesson3-02](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-02.png)
#### 3.In index.html file,
#### 1.Create HTML5 semantic header element and inside it , 
#### Create nav element with class="header__nav".
![Lesson3-03](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-03.png)
#### 2.Inside nav element 
#### First, Create div with class="header__logo" that will contain the logo, so inside it we can add the h4 element that is going to say sushiman, and below it , we can create a div with class="header__logo-overlay"

#### Second, Create unordered list with class="header__menu", inside it create a couple of list items 
#### The first list item has an anchor element inside it so it is actually a clickable link, and that anchor element has href="#menu" and says menu.
#### The second list item has anchor element with href="food" and says food.
#### The third list item has anchor element with href="services" and says services.
#### The fourth list item has anchor element with href="about-us" and says about us.
#### The last list item has an image element with src="assets/search.svg and alt="search".

![Lesson3-04](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-04.png)

![Lesson3-05](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-05.png)

#### 3. If we are on mobile devices then we will not be able to see all these elements on the screen. so below this ul element we need to create another ul element with class="header__menu-mobile" it will be for mobile devices, and it will render just one li element that will render an image with src="assets/menu.svg" and alt="menu".

![Lesson3-06](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-06.png)
![Lesson3-07](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-07.png)
#### White menu appears here, but later on they're going to be divided depending on which device size.


#### 4.In css/sections/header.css file,
![Lesson3-08](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-08.png)
#### Notice that the elements appear in a row , first the title , then ul element , then menu.

![Lesson3-09](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-09.png)

#### class of flex:1; means that it will expand however long it needs to. the sushiman is on the left side and the menu is on the right side.

![Lesson3-10](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-10.png)

#### position:absolute; means that it will not be bound to other elements on the page it will be absolutely positioned.


#### In style.css file, there is instance of :root{} , this allows us to create CSS variables, we can reuse them across all files by using the name of css variable later.

#### Example: background-color: rgb(121,45,45); 
#### Every time that you use the same instance of the color you would have to manually type rgb(121,45,45), so we can use css variables.

![Lesson3-11](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-11.png)


#### to create css variable
#### --name:"specify-the-color";
```
--primary-color: #b1454a;
--secondary-color: #121212;
```
#### in css/sections/header file, use
```
background-color:var(--primary-color);
```
#### This is powerful because you do not have to remember the actual hexadecimal color code.


![Lesson3-12](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-12.png)

![Lesson3-13](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-13.png)

![Lesson3-14](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-14.png)

![Lesson3-15](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-15.png)

![Lesson3-16](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-16.png)

![Lesson3-17](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-17.png)

![Lesson3-18](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-18.png)

![Lesson3-19](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-19.png)

![Lesson3-20](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-20.png)

![Lesson3-21](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-21.png)

![Lesson3-22](https://github.com/fatmakhaledosman/Vite-Sushi-Themed-Website-2024/blob/main/Lesson3-sushi-header/images-readme-file/img3-22.png)




