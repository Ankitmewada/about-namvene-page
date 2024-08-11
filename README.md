# about-namvene-page
about us section for food website.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400..700&family=Playfair+Display:ital,wght@0,400..900;1,400..900&family=Work+Sans:ital,wght@0,100..900;1,100..900&display=swap');
        </style>
        <link rel="stylesheet" href="style.css">
</head>
<body>
        <div id="page1">
            <div id="left-div">
                <img src="https://plus.unsplash.com/premium_photo-1668618295237-f1d8666812c9?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8Njl8fGJ1cmdlcnxlbnwwfHwwfHx8MA%3D%3D" alt="">
            </div>
            <div id="right-div">
                <h1>About Samvene: The Bagel Cafe</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Facilis explicabo excepturi aspensequatur. Odit hic, qui odio enim, facilis amet in necessitatibus ullam expedita corrupti eaque, sint eum saepe vitae explicabo laudantium.</p>
                <div id="about-btn">Check Menu</div>
            </div>
        </div>

    <div id="page2">
        
    </div>
    <!-- <div id="page3"></div> -->
</body>
</html


  ///css////

  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
}
html,body{
    height: 100%;
    width: 100%;
}

#page1{
    height: 100%;
    width: 100%;
    background-color: #222831;
    display: flex;
    padding: 4vw 6vw;
    /* border: 3px solid red; */
}

#page1 #left-div{
    height: 65%;
    width: 45%;
    overflow: hidden;
    /* background-color: blue; */
}
#left-div img{
    height: 100%;
    width: 100%;
    object-fit: cover;
    transition: transform 1s ease,box-shadow 1s;
    border-radius: 40% 10% 40%;
}
#left-div img:hover{
    /* border-radius: inherit; */
    transform: scale(1.0222);
    box-shadow: 0 0.8vw 1.5vw rgba(0, 0, 0, 0.36);
}

#page1 #right-div{
    height: 70%;
    width: 60%;
    /* border: 1px solid red; */
    /* background-color: red; */
}

#right-div{
    position: relative;
    display: flex;
    flex-direction: column;
    gap: 2vw;
    padding: 5vw 6vw;
    color: white;
}

#right-div h1{
    font-size: 3.2vw;
    font-weight: 400;
    font-family: "Dancing Script", cursive;
}

#right-div p{
    font-size: 1.3vw;
    font-weight: 300;
    line-height: 1.8vw;
    max-width: 36vw;
    word-wrap: break-word;
    /* word-spacing: 3px; */
    letter-spacing: 1.5px;
}
#about-btn{
    font-size: 1.3vw;
    font-weight: 400;
    position: absolute;
    background-color: #F79F4C;
    /* border: 2px solid black; */
    margin-top: 19vw;
    padding: 0.8vw 0.9vw;
    border-radius: 5vw;
    letter-spacing: 1.4px;
    transition: transform 0.1s ease, box-shadow 0.3s;
}
#about-btn:hover{
    background-color: #fa902d;
    cursor: pointer;
    box-shadow: 0 0.8vw 1.5vw rgba(0, 0, 0, 0.4);
}


#page2{
    height: 70vh;
    width: 100%;
    background-color: #222831;
    /* border: 1px solid yellow; */
}
