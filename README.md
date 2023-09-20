<!DOCTYPE html>
<html lang="vi" style="font-family: Sans-serif;">
<head>
        <title>My Page</title>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <link rel="icon" type="image/x-icon" href="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/Mao%201/logo-removebg-preview.png">
        <style>
            *{
                padding: 0;
                margin: 0;
            }
            /* style cho background*/
            .background {
                height: 100vh;/*1/100 chiều cao khung hình*/
                width: 100%;
                background-image: url('https://media.istockphoto.com/id/1420755455/photo/grunge-dirty-background-overlay.jpg?b=1&s=612x612&w=0&k=20&c=Fy12nzrJP6dWK7NPWeAHNL0rsob1HfA8Ypn91jSUA1g=');
                background-position: center;
                background-size: cover;/*tự chia tỉ lệ để phù hợp với nội dung*/
                padding-left: 5%;
                padding-right: 5%;
                box-sizing: border-box;/*Chiều rộng và chiều cao áp dụng cho tất cả các phần của phần tử*/
                position: relative;/*vị trí tương đối*/
            }
            .navbar{
                background-color: whitesmoke;
                font-size:150%;
                width: 100%;
                height: 15vh;
                margin: auto;
                padding-right: 2cm;
                padding-left: 2cm;
                margin-left: -2cm;
                margin-right: 2cm;
                display: flex;/*Dùng để hiển thị một phần tử dưới dạng khối*/
                align-items: center;/*Căn giữa các căn chỉnh cho tất cả các mục của phần tử <div>*/
            }
            .logo{
                width: 130px;
                cursor: pointer;
            }
            nav{
                flex: 1;
                padding-left: 60px;
            }
            nav ul li{
                display: inline-block;
                list-style: none;
                margin: 0px 20px;
            }
            nav ul li a{
                text-decoration: none;/*đặt kiểu trang trí cho văn bản*/
                color: #333;
            }
            .content h1 {
                font-size: 60px;
                font-weight: 100;
                margin-top: 15px;
                margin-bottom: 15px;
                color:white;

            }
            .content p{
                font-size: 30px;
                color: white;
                margin-left: 9cm;
                margin-top: 4.5cm;    
                margin-right: 4cm;
            }
            .content img{
                position: absolute;
                margin-left:-2cm;
                width: 40%;
                height: auto;
            }
            .content {
                margin-left: 10%;
                margin-top: 5%;
            }
            tr {
                list-style-type: none;
                padding-left: 0;
                text-align: left;
            }
            .section {
                margin: 50px auto;
                max-width: 800px;/*đặt chiều rộng tối đa cho phần tử*//*Nếu nội dung lớn hơn chiều rộng tối đa, nó sẽ tự động thay đổi chiều cao của phần tử.*/
                background-color: whitesmoke;
                opacity: 0.8;
                padding: 30px;
                display: flex;
                flex-direction: row;
                flex-wrap: wrap;
                align-items:center;
            }
            .sections {
                margin: 10px auto;
                max-width: 800px;
                background-color: whitesmoke;
                opacity: 0.8;
                padding: 30px;
            }
            .sections h{
                margin-left: 7cm;
                font-size: 28px;
            }
            .sections table{
                margin-top: 0.2cm;
                margin-left: 7cm;
            }
            .about{

                margin: 10px auto;
                max-width: 800px;
                background-color: whitesmoke;
                opacity: 0.8;
                padding: 30px;
            }
            .about img{
                width: 70%;
                height: auto;
                border-radius: 50px;
            }
            .about-text{
                text-align: justify;
            }
            .about-text table{
                display: flex;
                flex-wrap: wrap;
            }
            .main{
                width: 1130px;
                max-width: 95%;
                margin: 0 auto;
                display: flex;
                align-items: center;
                justify-content: space-around;
                flex-wrap: wrap;
            }
            .about-text h2{
                color: black;
                font-size: 75px;
                text-transform: capitalize;
                margin-bottom: 20px;
                margin-top: 30px;
            }
            .about-text h5{
                color: black;
                letter-spacing: 2px;
                font-size: 22px;
                margin-bottom: 25px;
                text-transform: capitalize;
            }
            .about-text p{
                color: black;
                letter-spacing: 1px;
                line-height: 28px;
                font-size: 18px;
                margin-bottom: 45px;
            }
            .about-text table{
                color: black;
                padding: 12px;
                margin-bottom: 50px;
                border-collapse: collapse;
                border-right-color: #191919;
                border-left-color: #191919 ;
            }
            .about-text table td{
                padding: 20px;
            }
        </style>
    </head>
    <body>
        <div class="background">
                <div class="navbar">
                    <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/Mao%201/blacklogo-removebg-preview.png" alt="Logo" class="logo">
                    <nav>
                        <ul id="menu">
                            <li><a href="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/PHINEAS.html">Trang chủ</a></li>
                            <li><a href="#ttcnl">Thông tin cá nhân</a></li>
                            <li><a href="#aboutme">Về chính tôi</a></li>
                            <li><a href="#mas">Ngành tôi học</a></li>
                            <li><a href="#ykr">Ý kiến về tôi</a></li>
                        </ul>
                    </nav>
                </div>
            <div class="content">
                <h1>Chào mọi người!!!</h1>
                <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/adorable-logo-design-cat-donut-suitable-cake-petshop_553860-138-removebg-preview.png">
                <p>Có thể thông qua trang web này, mọi người sẽ hiểu rõ mình hơn... !!!</p>
            </div>
        </div>
        <section class="about" id="About-me">
            <div class="main">
                <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/lam.jpg">
                <div class="about-text">
                    <h2>Thông tin về tôi</h2>
                    <h5>MAS 1 - <span>21080323</span></h5>
                    <p> Tôi là Đinh Xuân Lâm</p>
                    <style>
                        table {
                            border: 0px;
                            border-collapse: collapse;  
                        }
                        th, td {  
                            border: 1px solid #f9004d;  
                            padding: 10px;  
                            position: relative;
                            text-align: center;
                        }  
                        </style>
                    <table border="1px">
                        
                        <tbody><tr>
                            <td>Số điện thoại</td>
                            <td>Ngày sinh</td>
                            <td>Facebook</td>
                        </tr>
                        
                        <tr>
                            <td><a href="tel:0979161663">0979161663</a></td>
                            <td>07/11/2003</td>
                            <td><a href="https://www.facebook.com/little.maoo.k3">Xuân Lâm</a></td>
                        </tr>
                        
                        </tbody></table>
                </div>
            </div>
        </section>
        <div class="sections">
            <h3 id="aboutme">🧑‍🎓Về bản thân tôi</h3>
            <p>Chào mọi người, tôi tên Lâm đệm Xuân họ Đinh. Mọi người có thể gọi tôi là Lâm chứ đọc cả họ cả tên dài lắm. Tôi còn một cái tên khác cũng khá thân thuộc hơn là Mao. Tôi sinh ra và lớn lên ở Hà Nội còn cội nguồn ở Ninh Bình nơi bạt ngàn đá vôi và dê núi. Hiện thì tôi đang là sinh viên năm 2 trường Quản trị và Kinh doanh (HSB). Ngành tôi theo học là Quản trị và An ninh (MAS). Sở thích của tôi là chơi game, chơi thể thao và đặc biệt là kiếm tiền. Đây là một ví dụ nè.😉</p>
            <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/ck.png" width="100%" height="auto">
            <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/cp.jpg" width="100%" height="auto">
            <br><br>
            <p>Ngoài ra mình còn thích ăn vặt nữa. À không phải là "rất" thích ăn vặt :)))))</p>
            <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/food.jpg" width="100%" height="auto">
            <p>Và đi chơi với những anh em thiện lành.</p>
            <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/homie.png" width="100%" height="auto">
            <p>Tí nữa thì quên không giới thiệu thằng con của mình nữa.......Nuôi nó không được lâu lắm nhưng mà yêu hơn bồ và quý hơn bạn "xã giao :)"</p>
            <img src="https://mao-nek.000webhostapp.com/index.html/Nh%C3%B3m%202/Mao/mon.jpg" width="100%" height="auto">
        </div>
        <div class="sections">
            <h4 id="mas">🧑‍🎓Một xíu về ngành tôi học:</h4>    
                <iframe width="100%" height="450" src="https://www.youtube.com/embed/TQ7NXmucrDI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen=""></iframe>
        </div>
        <div class="section">
            <h4 id="ykr">🙍‍♂️Một số ý kiến riêng</h4>
                <form action="" method="get">
                    <label for="name">Họ và tên:</label><br>
                    <input type="text" id="name" name="name"><br>
                    <label for="msv">Mã sinh viên:</label><br>
                    <input type="text" id="msv" name="msv"><br>
                    <label for="pnb">Số điện thoại:</label><br>
                    <input type="text" id="pnb" name="pnb"><br>
                    <label for="mail">Mail:</label><br>
                    <input type="email" id="mail" name="mail"><br>
                    <label for="gt">Giới tính:</label>
                    <select id="gt" name="gt">
                        <option value="Nam">Nam</option>
                        <option value="Nữ">Nữ</option>
                        <option value="Ngoài">Ngoài</option>
                    </select>
                    <br><textarea name="comment" rows="5" cols="40">Nhập ý kiến ở đây!!!</textarea><br><br>
                    <input type="submit" value="Submit">
                    <input type="reset">
                </form> 
        </div>
 </body></html>
