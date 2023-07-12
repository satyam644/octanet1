<!DOCTYPE html>
<html>
<head>
     <title>Octanet Internship Program </title>
<style type="text/css">
     *{padding:0; margin:0; box-sizing: border-box;}
    header{
        width: 100%;
        height: 100vh;
        background-image:linear-gradient(rgba(0,0,0,0.8),rgba(0,0,0,0.2)), url("img/rty.jpg");
        background-size: cover;
        font-family: sans-serif;
        
    }
nav{
    width: 100%;
    height: 100px;
    color:rgb(236, 156, 8);
    display: flex;
    justify-content: space-around;
    align-items: center;
}
.logo{
    font-size: 2em;
    letter-spacing: 2px;
}
.menu a{
    text-decoration: none;
    color: rgb(245, 238, 240);
    padding: 10px 20px;
    font-size: 20px;
    position: relative;
}
.menu a::before{
    content: none;
    position: absolute;
    top: 0;
    left: 0;
    width: 0%;
    height: 100%;
    border-bottom: 2px solid indianred;
    transition: 0.4s linear;

}
.menu a:hover::before{
    width:90%;
}
.Register a{ text-decoration: none;
    color:  rgb(253, 242, 244);
    padding: 10px 20px;
    font-size: 20px;
    background: lightcoral;
    border-radius: 8px;
    }
    .h-txt{
        max-width: 650px;
        position: absolute;
        top:50%;
        left: 50%;
        transform: translate(-50%,-50%);
        text-align: center;
        color: rgb(239, 245, 240);
       
    
    }
    .h-txt span{
        letter-spacing: 5px;
        font-size: 30px;
    }
    .htxt h1{
        font-size: 6.5em;
    }
    .h-txt h2{
        font-size: 3.5em;
    }
    .h-txt a{
        text-decoration: none;
        background: rgb(77, 219, 124);
        color: ivory;
        padding: 10px 20px;
        letter-spacing: 5px;
    }
</style>
</header>
<body>
    <header>
        <nav>
            <div class="logo">
                Octanet Iternship
            </div>
            <div class="menu">
                <a href="#">Home</a>
                <a href="#">Info</a>
                <a href="#">Course</a>
                <a href="#">Contact</a>
        </div>
        <div class="Register">
            <a href="#">Get Into internship</a>
        </div>
        </nav>
        <section class="h-txt">
            <span>GET</span>
            <h1>FREE INTERNSHIP OF</h1>
            <h2>WEB DEVELOPMENT</h2>
            
            <br>
            <a href="#">GET ENROLL TODAY</a>
        </section>
    </header>
</body>
