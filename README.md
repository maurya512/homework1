# Homework 1

<h3>In this homework we were assigned a task to refactor an existing source code for a web page, increasing the accessibility of the page without compromising the usability of the users.</h3>

<p>This was achieved by reducing the amount of div elements used in the original source code.

While div elements are helpful and can serve a variety of purposes one of the main problems with implementing multiple div elements in the code is it becomes hard to keep track of which section of the code is enclosed in which div element. This makes it harder for the reader to make sense of the code at a first glance. 

Scouting the code gives us an opportunity to enhance the already functional code. 

Div being a non-semantic element we can replace div with semantic elements such as header, footer, article, section, figure etc. 

Using semantic element is not only a good practice as a programmer, they are highly descriptive and can be used similarly as a div element in css/javascript. 

Replacing the div elements not only made the code more readable to the naked eye, it made the code more shorter and precise.

Along with that I removed the ul and li tags and replace that with nav semantics. 

Used article to specify independent, self-containe content. Figure to specify the image source and alt to describe what the image would look like in case it didn't load properly. 

The css file had many style attributes that were the same for similar classes and div elements. Since we changed them into semantics, their corresponding style attributes also become more succint and accessible.
</p>


