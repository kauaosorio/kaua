<!DOCTYPE html>
<html lang="PT-BR">
<head>
    <title>site 2</title>
    <link rel="stylesheet" href="Sitee2.css">
</head>
<body>
     <header>
        <div>
            <h1 id="title">
                BROWNY
            </h1>
        </div>

        <nav class="links">
            <a class="links1" href="#">Education</a>
            <a class="links1" href="#">Skills</a>
            <a class="links1" href="#">Experience</a>
            <a class="links1" href="#">Profile</a>
            <a class="links1" href="#">Portfolio</a>
            <a class="links1" href="#">Clients</a>
            <a class="links1" href="#">Contact</a>
        </nav>

     </header>

     <section id="hero">
        <div id="heroContentContainer">
            <div>
                <h1 id="heroTitle">
                    HI<span> ,</span> I AM BROWNY STAR<span> .</span>
                </h1>
            </div>
            <div>
                <p id="heroText">
                    ui/ux designer and web developer
                </p>
            </div>
            <div>
                <button> Dowload Resume </button>
            </div>
        </div>
     </section>

     <section>
        <div class="about"> 
             <h1 id="titleAbout"> About Me </h1>
        </div>

        <div id="aboutContentContainer">
            <div id="aboutTextContainer">
                 <div>
                     <p> It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum</p>  
                </div>
                
                 <div>
                     <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and scrambled it to make a type specimen book. It has survived not only five centuries, but also the leap into electronic typesetting, remaining essentially unchanged. It was popularised in the 1960s with the release of Letraset sheets containing Lorem Ipsum passages, and more recently with desktop publishing software like Aldus PageMaker including versions of Lorem Ipsum.</p>
                </div>

                 <div>

                </div>
            </div>

            <div>
                      
            </div>
        </div>
     </section>
</body>
</html>

header {
    display: flex;
    justify-content: space-evenly;
    align-items: center;
    height: 80px;
}
#title {
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-weight: 600;
    font-size: 15px;
    color: blueviolet;

}
nav {
    display: flex;
    width: 45%;
    justify-content: space-between;
}
.links1{
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    font-weight: 600;
    font-size: 14px;
    text-decoration: none;
    color: gray;
}
.links :hover {
  color: cornflowerblue;
}


#hero {
    display: flex;
    height: 800px;
    justify-content: center;
    align-items: center;
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url(https://cdn.pixabay.com/photo/2022/08/03/13/09/moon-7362632_1280.jpg);
}   
button {
    color: white;
    padding: 15px;
    background-color: blueviolet;
    border-radius: 3px;
    border: none;

}

#heroContentContainer {
    display: flex;
    
    height: 65%;
    width: 300px;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
}
#heroTitle {
   color: white;
   font-size: 46px;
   font-family: Arial, Helvetica, sans-serif;
   font-weight: 700;
   text-align: center;
}
#heroText {
text-transform: uppercase;
font-family: Arial, Helvetica, sans-serif;
color: white;
font-size: 13px;

}

span {
    color: rgb(179, 31, 179);
}

.about {
    display: flex;
    justify-content: center;
    border-bottom: solid 0.5px;

}
#titleAbout {
    display: flex;
 font-family: Arial, Helvetica, sans-serif;
 font-size: 18px;
 font-weight: 100px;
 height: 70px;
 align-items: center;
 
}
 
#aboutContentConteiner  {
    display: flex;
}

#aboutTextContainer {
    display: flex;
    flex-direction: column;
    width: 40%;
    
}

