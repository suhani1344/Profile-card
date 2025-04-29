# Profile-card<!DOCTYPE html>
<html lang="en">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Profile card UI Design</title>
    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;

        }
        body{
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: #f4f4f4;

        }
    .profile-card{
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 370px;
            width: 100%;
            background: #fff;
            border-radius: 24px;
            padding: 25px;
            box-shadow:0 5px 10px rgba(0,0,0,0.1);
            position: relative;
        }
        .profile-card::before{
            content: "";
            position: absolute;
            top: 0;
            left: 0;
            height: 36%;
            width: 100%;
            border-radius: 24px 24px 0 0;
            background-color: #4070f4;
        }
        .image{
            position: relative;
            height: 150px;
            width: 150px;
            border-radius: 50%;
            background-color: #4070f4;
            padding: 3px;
            margin-bottom: 10px;
        }
        .profile-img{
            height: 100%;
            width: 100%;
            object-fit: cover;
            border-radius: 50%;
            border: 3px solid#fff;
        }
    .text-data{
        display: flex;
        flex-direction: column;
        align-items: center;
        color: #333;
    }
    .name{
        font-size: 22px;
        font-weight: 500;
    }
    .job{
        font-size: 15px;
        font-weight: 400;
    }
    .media-button{
        display: flex;
        align-items: center;
        margin-top: 15px;

    }
    .link{
        display: flex;
        align-items: center;
        justify-content: center;
        color: #fff;
        font-size: 18px;
        height: 34px;
        width: 34px;
        border-radius: 50%;
        margin: 0 8px;
        background-color: #4070f4;
        text-decoration: none;
    }
    .buttons{
        display: flex;
        align-items: center;
        margin-top: 25px;
    }
    .button{
        color: #fff;
        font-size: 14px;
        font-weight: 400;
        border: none;
        border-radius: 24px;
        margin: 0 10px;
        padding: 8px 24px;
        background-color: #4070f4;
        cursor: pointer;
        transition: all 0.3s ease;
    }
    .analytics{
        display: flex;
        align-items: center;
        margin-top: 25px ;
    }
.data{
    display: flex;
    align-items: center;
    color: #333;
    padding: 0 20px;
    border: 1px solid #e7e7e7;
    border-radius: 8px;

    }
    .data:last-child{
        border-radius: none;
    }
    i{
        font-size: 18px;
        margin-right: 6px;
    }
        
    </style>
</head>
<body>
    <div class="profile-card">
        <div class="image">
            <img src="suhani.jpeg" alt="" class="profile-img">
        </div>

        <div class="text-data">
            <span class="name">CodingLab</span>
            <span class="job">YouTuber & Blogger</span>
        </div>


        <div class="media-button">
            <a href="#" style="background: #4267b2;" class="link">
                <i class='bx bxl-facebook'></i>
            </a>
            <a href="#" style="background: #1da1fa;" class="link">
                <i class='bx bxl-instagram' ></i>
            </a>
            <a href="#" style="background: #e1306c;" class="link">
                <i class='bx bxl-twitter'></i>
            </a>
            <a href="#" style="background: #f00;" class="link">
                <i class='bx bxl-whatsapp'></i>
            </a>

        </div>
 
        <div class="buttons">
            <button class="button">Subscribe</button>
            <button class="button">Message</button>
        </div>

        <div class="analytics">
            <div class="data">
                <i class='bx bx-heart'></i>
                <span class="number">60K</span>
            </div>

            <div class="data">
                <i class='bx bx-message-rounded'></i>
                <span class="number">20K</span>
            </div>

            <div class="data">
                <i class='bx bx-share'></i>
                <span class="number">12K</span>
            </div>


        </div>
    </div>
</body>
</html>
