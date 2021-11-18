*{
    margin: 0;
    padding: 0;
}
body{
background-color: rgb(248, 224, 88);

}
.logo img{
    width: 130px;
}
header{
margin-top: -90px;
justify-content: space-between;
}
header ul{
    text-align: right;
    flex: 1 1 300px;
    justify-content: flex-end;
    margin-right: 80px;
    align-items: center;
}
header ul a{
    text-decoration: none;
    padding: 10px 10px;
    font-weight: 500;
    color: black;
    font-family:Verdana, Geneva, Tahoma, sans-serif;
    position: relative;
    font-size: 18px;
    letter-spacing: 0.5px;
}
.title{
    display: flex;
    flex-direction: column;
    flex: 1;
    align-items: center;
    justify-content: center;
}
.title h1{
    font-size: 3em;
    margin-top: 90px;
}
.text1{
    margin-top: 60px;
    margin-left: 40px;
}
.photos img{
    width: 300px;
    margin-left: 800px;
    margin-top: -240px;
}
.text2{
    margin-top:60px ;
    margin-left: 40px;
}
.photos2 img{
width: 300px;
margin-left:800px ;
margin-top:-240px ;
}
.text3{
    margin-top: 60px;
    margin-left: 40px;
}
.photos3 img{
    width: 300px;
    margin-left: 800px;
    margin-top: -230px;
}
.text4{

    margin-top: 60px;
    margin-left: 40px;
}
.photos4{
    width: 300px;
    margin-left: 800px;
    margin-top: -230px;
}
.text5{
    margin-top:60px ;
    margin-left: 40px;
}
.photos5{
    width:300px ;
    margin-left: 800px;
    margin-top: -150px;
}
header ul a::after{
content: "";
position: absolute;
background-color: black;
height: 3px;
width: 100%;
left: 0;
bottom: -10px;
transition: 0.3s;
}
header ul a:hover ::after{
width: 100%;
}
.text6{
    margin-top: 60px;
    margin-left: 40px;
}
.photos6 img{
    width: 300px;
    margin-left: 800px;
    margin-top: -140px;
}
