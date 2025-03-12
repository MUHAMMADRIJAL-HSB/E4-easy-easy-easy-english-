<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>beranda e4</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #f0f2f7, #a777e3);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            
            text-align: center;
            overflow: hidden;
        }
        .profile-container {
            text-align: center;
            margin-top: 20px;
        }
        .profile-img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            object-fit: cover;
            border: 4px solid #e2f109;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
        }
        .cover-container {
            background: #C8AAAA;
            padding: 40px;
            border-radius: 15px;
            box-shadow: 10px 20px 20px rgb(17, 17, 17);
            animation: fadeIn .1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        h1 {
            font-size: 3em;
            margin-bottom: 10px;
            animation: slideIn 1.5s ease-in-out;
        }
        @keyframes slideIn {
            from { opacity: 0; transform: translateY(-30px); }
            to { opacity: 1; transform: translateY(0); }
        }
        p {
            font-size: 1.2em;
            margin-bottom: 20px;
            animation: fadeIn 2s ease-in-out 0s forwards;
        }
        .btn {
            display: inline-block;
            padding: 12px 24px;
            background: #78ff8a;
            color: black;
            text-decoration: none;
            border-radius: 8px;
            font-size: 1.2em;
            transition: 0.3s;
            animation: bounce 1.5s infinite;
        }
        .btn:hover {
            background: #f72500;
        }
        @keyframes bounce {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-5px); }
        }
        .floating-bg {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            background: url(e4.png) no-repeat center center/cover;
            opacity: 0.2;
            animation: scaleUp 10s infinite alternate ease-in-out;
        }
        @keyframes scaleUp {
            from { transform: scale(1); }
            to { transform: scale(1.1); }
        }
    </style>
</head>

<body>
   
    <div class="floating-bg"></div>
    <div class="cover-container">
        <div class="profile-container">
            <img style="width: 180px;height:200px;" src="gambar30.jpg" alt="Foto Profil" class="profile-img">
        </div>
        <h1>Welcome To</h1>
        <p>E4 (easy easy easy english)</p>
        <a href="web_profile.html" class="btn">NEXT</a>
    </div>
</body>
</html>
