!DOCTYPE html>
<html>
<head>
    <title>My Website</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            background-image: url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e');
            background-size: cover;
            background-position: center;
            font-family: Arial, sans-serif;
            text-align: center;
            padding-top: 50px;
            color: white;
        }

        .logo {
            width: 80px;
            height: auto;
            margin-bottom: 20px;
        }

        .header-box {
            background-color: rgba(0, 0, 0, 0.5);
            display: inline-block;
            padding: 40px;
            border-radius: 15px;
        }

        .button-container {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 20px;
        }

        .youtube-btn {
            background-color: #FF0000;
            color: white;
            border: none;
            padding: 12px 25px;
            font-size: 16px;
            border-radius: 8px;
            cursor: pointer;
        }

        .youtube-btn:hover {
            background-color: #cc0000;
        }

        .affiliate-btn {
            background-color: #28a745;
            color: white;
            border: none;
            padding: 12px 25px;
            font-size: 16px;
            border-radius: 8px;
            cursor: pointer;
        }

        .affiliate-btn:hover {
            background-color: #1e7e34;
        }

        .affiliate-btn:disabled {
            background-color: #6c757d;
            cursor: not-allowed;
            opacity: 0.7;
        }

        .social-container {
            margin-top: 30px;
            display: flex;
            justify-content: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        .social-container a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            padding: 8px 15px;
            background-color: rgba(0,0,0,0.5);
            border-radius: 8px;
            transition: background-color 0.3s;
        }

        .social-container a:hover {
            background-color: rgba(0,0,0,0.8);
        }

        .form-container {
            margin-top: 40px;
            background-color: rgba(0,0,0,0.5);
            display: inline-block;
            padding: 30px 40px;
            border-radius: 15px;
            text-align: center;
        }

        .form-container h2 {
            margin-bottom: 15px;
            color: #FFD700;
        }

        .email-input {
            padding: 10px;
            width: 250px;
            border-radius: 8px;
            border: none;
            margin-right: 10px;
            font-size: 16px;
        }

        .subscribe-btn {
            background-color: #1e90ff;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            border-radius: 8px;
            cursor: pointer;
        }

        .subscribe-btn:hover {
            background-color: #3742fa;
        }

        @media (max-width: 600px) {
            .header-box {
                padding: 20px;
                font-size: 16px;
            }

            .button-container {
                flex-direction: column;
                gap: 15px;
            }

            .youtube-btn, .affiliate-btn {
                width: 80%;
                font-size: 14px;
                padding: 10px 0;
            }

            .logo {
                width: 60px;
                margin-bottom: 15px;
            }

            .email-input, .subscribe-btn {
                width: 70%;
                margin-bottom: 10px;
            }
        }
    </style>
</head>
<body>
    <!-- Logo -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/89/HD_transparent_picture.png" 
         alt="My Logo" class="logo">

    <!-- Header -->
    <div class="header-box">
        <h1>Welcome to my website</h1>
        <p>I am happy to see you here!</p>
    </div>

    <!-- Buttons -->
    <div class="button-container">
        <button class="youtube-btn" onclick="window.open('https://www.youtube.com/@SundayMorenikedji', '_blank')">
            ▶️ Visit My YouTube Channel
        </button>

        <button class="affiliate-btn" disabled>
            💰 Check Out This Offer
        </button>
    </div>

    <!-- Social Media Links -->
    <div class="social-container">
        <a href="https://www.instagram.com/YourProfile" target="_blank">📸 Instagram</a>
        <a href="https://www.tiktok.com/@YourProfile" target="_blank">🎵 TikTok</a>
        <a href="https://www.facebook.com/YourProfile" target="_blank">📘 Facebook</a>
    </div>

    <!-- Subscribe Form -->
    <div class="form-container">
        <h2>Stay Updated!</h2>
        <p>Enter your email to subscribe:</p>
        <input type="email" placeholder="Your email" class="email-input" required>
        <button class="subscribe-btn">Subscribe</button>
    </div>

    <!-- JavaScript for alert -->
    <script>
        const subscribeBtn = document.querySelector('.subscribe-btn');
        subscribeBtn.addEventListener('click', function() {
            const email = document.querySelector('.email-input').value;
            if(email) {
                alert(`Thank you for subscribing, ${email}!`);
            } else {
                alert('Please enter a valid email.');
            }
        });
    </script>
</body>
</html>
