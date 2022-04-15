<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>email signature</title>
    <script src="https://kit.fontawesome.com/ea2601600a.js" crossorigin="anonymous"></script>
</head>
<body>
    <div class="box-container">
        <div class="box">
            <div class="image">
                <img src="1635965106892.jpg">
            </div>
            <div class="content">
                <div class="icon">
                    <i class="fas fa-user"></i>
                    <i class="fas fa-phone"></i>
                    <i class="fas fa-globe"></i>
                    <i class="fas fa-envelope"></i>

                </div>
                <div class="info">
                    <h3 class="titel">sanoar <span>hossen</span></h3>
                    <span class="post">web developer</span>
                    <a href="">+8801831650705</a>
                    <a href="">www.google.com</a>
                    <a href="">soar9185@gmail.com</a>
                </div>
            </div>
            <div class="share">
                <a href=""><i class="fab fa-facebook"></i></a>
                <a href=""><i class="fab fa-twitter"></i></a>
                <a href=""><i class="fab fa-instagram"></i></a>
                <a href=""><i class="fab fa-linkedin"></i></a>

            </div>
        </div>
    </div>
</body>
</html>


*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
    text-decoration: none;
    transition: all .2s;
}
.box-container{
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background: #ccc;
}
.box{
    width: 700px;
    background: #2c3e50;
    border-radius: 10px;
    overflow: hidden;
    box-shadow: 0 5px 10px #0007;
    display: flex;
    align-items: center;
    margin: 20px;
}
.image{
    padding: 60px 0;
    width: 260px;
    text-align: center;
    background: #0005;
    clip-path: polygon(0 0, 80% 0, 100% 15%, 100% 85%, 76% 100%, 0 100%);
}
.image img{
    width: 150px;
    height: 150px;
    border-radius: 50%;
    box-shadow: 0 0 0 10px coral;
    object-fit: cover;
}
.content{
    display: flex;
    padding: 0 10px;
}
.icon{
    background: #fff;
    margin: 0 10px;
}
.icon i{
    font-size: 20px;
    margin: 10px 13px;
    color: coral;
    display: block;
}
.icon i:first-child{
    margin-bottom: 70px;
}
.titel{
    font-size: 29px;
    color: #fff;
    padding: 0 5px;
    text-transform: capitalize;
}
.titel span{
    color: coral;
}
.post{
    color: #ccc;
    display: block;
    padding-bottom: 32px;
    font-size: 18px;
    padding-left: 5px;

}
.info a{
    display: block;
    color: #aaa;
    padding: 6px 0;
}
.info a:hover{
    color: #fff;
}
.share{
    display: flex;
    height: 274px;
    padding: 0 7px;
    background: #fff;
    align-items: center;
    justify-content: center;
    flex-flow: column;
    margin-left: auto;
}
.share a{
    margin: 10px;
    font-size: 23px;
    color: #666;
}
.share a:hover{
    color: coral;
}
@media(max-width: 650px){
    .box-container.box{
        flex-flow: column;
        width: 340px;
    }
    .box-container .box .image{
        width: 100%;
        height: 200px;
        padding: 40px 0;
        clip-path: polygon(0 0, 100% 0, 100% 70%, 80% 100%, 20% 100%, 0 70%);
    }
    .box-container .box .image img{
        height: 120px;
        width: 120px;
    }
    .box-container .box .content{
        padding: 30px 5px;
    }
    .box-container .box .share{
        height: auto;
        width: 100%;
        flex-flow: row;
        padding: 5px 0;
    }
}
