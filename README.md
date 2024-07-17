<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Product Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        .header {
            background: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        .showcase {
            background: #f4f4f4;
            padding: 20px 0;
            text-align: center;
        }
        .showcase img {
            width: 300px;
            height: auto;
        }
        .features {
            display: flex;
            justify-content: space-between;
            padding: 20px 0;
        }
        .feature {
            flex: 1;
            padding: 10px;
        }
        .testimonials {
            background: #f4f4f4;
            padding: 20px 0;
        }
        .testimonial {
            margin-bottom: 20px;
        }
        .footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>

    <header class="header">
        <div class="container">
            <h1>Noise Ear Buds</h1>
        </div>
    </header>

    <section class="showcase">
        <div class="container">
            <h2>Amazing Product</h2>
            <p>Our product is the best in the market. It offers fantastic features and great value for money.

			</p>
             <img src="https://cdn1.smartprix.com/rx-iF70NDPbW-w1200-h1200/F70NDPbW.jpg" alt="Product Image"> 
        </div>
    </section>

    <section class="features">
        <div class="container">
            <div class="feature">
                <h3>Audio</h3>
                <p>Speaker Driver: 13mm</p>
            </div>
            <div class="feature">
                <h3></h3>
                <p>BT : 5.3
					Wireless Range : 10m
					BT Supported Profile : A2DP, HFP, HSP, AVRCP
					Compatibility : Android & iOS</p>
            </div>
            <div class="feature">
                <h3>Battery Charging</h3>
                <p>Playtime : Up to 6 hours on a single charge and 
					an additional 34 hours with the charging case
					Earbud Charging Time : Up to 60 minutes
					Charging Case Charge time : Up to 90 minutes
					Charging Indicator : Yes</p>
            </div>
        </div>
    </section>

    <section class="testimonials">
        <div class="container">
            <h2>What Our Customers Say</h2>
            <div class="testimonial">
                <p>"This product has changed my life! I can't imagine going back to the way things were before."</p>
                <cite>- Satisfied Customer</cite>
				<img src="https://judgeme.imgix.net/noise/1671165383__1671164857813__original.JPEG?auto=format&w=1024" width="10%">
            </div>
            <div class="testimonial">
                <p>"Excellent product with fantastic support. Highly recommended."</p>
                <cite>- Happy User</cite>
            </div>
        </div>
    </section>

    <footer class="footer">
        <div class="container">
            <p>&copy; 2024 Product Name. All rights reserved.</p>
        </div>
    </footer>

</body>
</html>
