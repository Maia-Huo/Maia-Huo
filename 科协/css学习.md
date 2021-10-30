<div class="box1">
            <h1>Hello World</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Officia iure temporibus reprehenderit autem. Voluptatem, veniam vitae eligendi dignissimos consequatur perspiciatis numquam officiis maxime, recusandae quidem veritatis? Dolorum deserunt ex possimus.</p>
</div>

新建一个盒子，将内容放入对其格式修改

<!--文体部分-->

body{

  background-color: lavenderblush;

  font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;<!--字体类型-->

  font-size:25px ;<!--字体大小为25像素-->

  font-weight: bold;<!--黑体字，粗体字-->

}

<!---盒子内部分-->

.box1 {

  background-color: antiquewhite;

  color: brown;

  border:5px cyan dotted;<!--边框-->

}

.box1 h1{<!--盒子中h1标题装饰-->

  font-family: 'Times New Roman', Times, serif;

  font-style: italic;

  text-decoration:underline;

  text-transform: uppercase;<!--大写字母-->

  letter-spacing: 1em;

}

<div class="list">
        <ul>
            <li><a href="">list1</a></li>
            <li><a href="">list2</a></li>
            <li><a href="123.abc">list3</a></li>
            <li><a href="">list4</a></li>
            <li><a href="">list5</a></li>
        </ul>
    </div>

<!--表格形式改变-->

.list li {

  background-color: darkorange;

  list-style-image: url(OIP-C.jpg);<!--表格list前标志图片-->

  list-style:lower-roman

 }





<button><a href="http://www.baidu.com">button</a></button>

<!--按钮形式转变-->

button {

  background-color: darkorange;

  color: royalblue;

  padding:  10px 15px;

}

<!--鼠标在按钮上悬停时-->

button:hover{

  background-color: tomato;

}

<!--按钮被点击时-->

button:active{

  background-color: white;

}





<!--超链接-->

<li><a href="">list1</a></li>

​      <li><a href="">list2</a></li>

​      <li><a href="123.abc">list3</a></li>

​      <li><a href="">list4</a></li>

​      <li><a href="">list5</a></li>

<!---------------->

a {

  text-decoration:none ;

  color: slategrey;

}

a :hover {

​    color: springgreen;

}

a:visited{<!--超链接被访问过-->

  color: tomato;

}





<!--三段文字并排占据网页宽度-->

assume there are three paragraphs



.block{

  float: left;

  width: 33.3%;

  border: 1px solid red;

  box-sizing: border-box;<!--加上边框之后，3个33.3%的文字会超过网页宽度，便需要此语句-->

}







