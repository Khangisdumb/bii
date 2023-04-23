# bii
body{
    margin: 0;
    padding: 0;
    background: url(mẹ\ khuyên.jpg) no-repeat; 
    background-size: cover;
}
.box{
    width: 450px;
    background: rgba(0, 0, 0, 0.7);
    padding: 40px;
    text-align: center;
    margin: auto;
    margin-top: 5%;
    color: white;
    font-family: sans-serif;
    border-radius: 2%;
    
}
.box-img{
    border-radius: 5%;
    width: 200px;
    height: 200px;

}
.box h1{
    font-size: 30px;
    letter-spacing: 4px;
    font-weight: 100;
    
    text-align: center;

}
.box h5{
    font-size: 10px;
    letter-spacing: 3px;
    font-weight: 100; 
    text-align: center;
}
.box p{
    text-align: justify;
}
.u{
    width: 400px;
    text-align: center;
}
.change-txt li span{
    position: relative;
    margin: 5px 0;
    line-height: 90px;
}
.change-txt li span ::after{
    content: '';
    position: absolute;
    left: 0;
    width: 100%;
   
    animation: typing 3s steps(10) infinite;
    height: 100%;
}
@keyframes typing{
    40%,
    60%{ 
        left: calc(100% + 30px);
    }
    100%{
        left: 0;
    }

}
.wrapper .change-txt{
    margin-right: 20px;
    height: 90px;
    line-height: 50px;
    overflow: hidden;
    text-align: center;
    justify-content: center;
}
.change-txt li{
    list-style: none;
    color: white;
    font-size: 30px;
    font-weight:500;
    position: relative;
    top: 0;
    animation: slide 3s steps(4) infinite;
    text-align: center;
}
@keyframes slide{
    100% {
        top: -360px;
    }
}
.b{
    color: transparent;
    font-size: 20px;
    -webkit-text-stroke: 1px white;
    position: relative;
}
.b::before{
    content: "Nhân ngày sinh nhật mẹ Khuyên, chúng con chúc mẹ luôn luôn mạnh khỏe, tràn đầy năng lượng và hạnh phúc bên gia đình, Luôn gặp nhiều điều may mắn và thành công trong cuộc sống!!!";
    position: absolute;
    width: 0%;
    height: 100%;
    overflow: hidden;
    color: white;
    border-right: 5px solid white;
    transition: 1s ease-in-out;
}
.b:hover::before{
    width: 100%;
    filter:drop-shadow(0 0 25px white);
}
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>HAPPY BIRTHDAY !!!!!</title>
</head>
<body>
    <div class="box">
        <img src="birthday-gif-8.gif" alt=""class="box-img">
        
        <h5><div class="wrapper">
        
            <ul class="change-txt">
                <li><span>Chúc Mừng</span></li>
                <li><span>Sinh Nhật</span></li>
                <li><span>của</span></li>
                <li><span>mẹ Khuyên</span></li>
                <li><span>Minecrafter</span></li>
                <li><span>Reader</span></li>
                <li><span>Proessional</span></li>
                <li><span>Human</span></li>
            </ul>
            
            </div></h5>
            
        <p class="b"> Nhân ngày sinh nhật mẹ Khuyên, chúng con chúc mẹ luôn luôn mạnh khỏe, tràn đầy năng lượng và hạnh phúc bên gia đình, Luôn gặp nhiều điều may mắn và thành công trong cuộc sống!!!
                  </p>
                  ⠀⠀⠀⠀⣰⣶⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⢀⣤⣤⣿⣯⣻⣴⣶⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⢿⣿⣿⣷⣿⣿⣿⣿⣄⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠐⣿⣿⣿⣿⣿⣿⢋⡴⢚⣹⠗⢦⣄⡀⠀⠀⠀⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠙⢻⣿⣿⣿⢿⣤⠔⢉⡤⠒⣫⡿⠛⢲⣤⣞⠉⠙⣦⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠈⠋⠀⠙⠋⢣⡤⠋⡠⠛⣡⣴⣾⡿⠗⠚⣷⠢⣿⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⣘⣷⣞⡠⠞⣡⠞⠋⠀⠀⠀⠘⢷⠀⠉⠻⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠐⡏⠀⠈⠻⡎⠀⠀⠀⠀⣴⣷⠀⠈⠛⣷⣦⣧⣤⣤⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢹⣄⠀⠀⠁⠀⠀⠀⠀⠛⢹⣿⣶⡖⠋⢽⣿⣿⢧⠙⡏⠙⢷⡶⢤⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠉⢶⠂⠀⠀⠀⠀⠀⠀⠈⠉⢹⡀⠀⠀⠉⠉⡼⠀⡿⠀⠀⠙⠷⢿⣴⣶⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⣦⠀⠀⠀⠀⠀⠀⠀⠀⢸⣧⣄⠀⢀⡴⠃⣴⠇⠀⠀⠀⠀⠸⡟⢻⡀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣈⣇⠀⠀⠀⠀⠀⠀⠀⠀⠈⢿⣿⣧⡄⣴⠇⠀⠀⠀⠀⢀⣰⡇⠸⡷⠶⠶⡦⠤⣄⡀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠸⣏⠺⠷⠶⠶⠶⢶⠶⠶⢤⣀⡀⠹⢏⡼⣹⠀⣀⡴⣾⢿⣿⡼⣇⢀⡷⠒⣲⣶⠶⢋⣹⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢿⡃⠀⠀⠀⠀⠉⠓⠦⣄⡀⠉⣳⠯⠼⣏⣿⣷⣶⣿⣿⣾⢟⠛⠛⢉⣉⣡⡤⠾⠋⢭⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⠃⠀⠀⠀⠀⠀⠀⠀⠉⣹⠿⠿⣆⣀⣘⣮⢿⣿⣿⣿⡟⠛⠒⠋⠉⠁⠀⠀⠀⣀⡾⣿⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⣰⠏⠀⠳⡀⠀⠀⠀⠀⠀⡼⠃⠀⠀⠀⠀⠈⠉⠉⠀⠀⠀⠉⣦⢀⣀⣀⣠⠤⠖⠋⣁⣼⡟⠀
⠀⠀⠀⠀⠀⠀⠀⠀⢴⣯⣀⠀⠀⠙⢦⣄⢀⡀⠰⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣼⣋⣿⣿⣴⣤⡴⠖⠋⠁⢨⣿⣤
⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⠏⠛⠦⣀⠀⠈⠉⠙⢶⣉⠿⠲⠶⢤⣤⣤⣤⣀⡤⠶⠋⠁⠀⠉⠀⠀⠀⠀⣀⣠⠔⠋⣸⡿
⠀⠀⠀⠀⠀⠀⠀⠀⠀⣼⠀⠀⠀⠀⠉⠛⠒⠒⠶⠶⠷⠶⠒⠛⠉⢸⠀⢾⣷⣶⣤⣤⣴⠶⠶⠶⡖⡚⣋⣀⣴⠾⠋⠀
⠀⠀⠀⠀⠀⠀⠀⠀⣴⠇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡆⠈⣿⠿⠿⠾⠷⠿⠧⠶⠿⠟⠛⠉⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢠⡏⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢸⡆⢀⡇⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⢸⡇⠀⠀⠀⠀⠀⠀⠀⣀⣀⣀⡀⠀⠀⠀⠀⠀⢨⠇⣸⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⣠⡶⠛⢦⣀⣷⠀⠀⠀⠀⣠⠖⠋⠉⠀⠀⠙⠓⠦⣤⡀⠀⠜⣰⠃⠀⣠⠤⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⢀⣾⠋⡀⠀⠀⠉⠛⢧⡀⠀⠈⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠳⣼⠁⣠⠋⡀⠀⠈⣧⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⢠⣿⠁⠠⢳⣄⠀⠀⠀⠀⠙⠦⣄⡘⠷⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢙⠇⢠⠇⠀⠀⢹⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⢸⡟⠀⠈⠉⢻⡦⣄⣀⠀⠀⢀⣀⡬⠿⠛⠛⠲⠤⢤⣀⡀⠀⠀⠀⠀⠸⡀⣿⠀⠀⠀⣾⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠈⢧⡀⠀⢀⡾⠀⠀⠉⠙⠛⠋⠁⠀⠀⠀⠀⠀⠀⠀⠈⠉⠛⠢⢄⡀⠀⠀⣿⠀⠀⣴⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠛⠒⠋⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠙⠳⠤⠤⠴⠚⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⡀⣀⣀⣀⢀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣀⣤⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
⣠⣤⣶⣾⣷⣾⣿⣿⠿⠿⢿⠟⠿⠛⠛⠛⠛⠛⢻⢾⠿⡿⡿⠛⠛⡛⠛⠛⠛⠀⠀⠛⡛⠛⠛⠛⠀
Chúng con: Meo và Tò⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
                </p>
    </div>
</body>
</html>
