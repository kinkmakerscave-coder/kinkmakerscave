<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KINK MAKER's CAVE</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background-color: #931f18; /* Deep red background */
            color: #fff;
        }
        header {
            background-color: #000000; /* Black header */
            color: white;
            text-align: center;
            padding: 0.5em;
            position: relative;
        }
        .hamburger {
            position: absolute;
            top: 1.5em;
            right: 1.5em;
            cursor: pointer;
            font-size: 1.5em;
            z-index: 2000;
        }
        .hamburger span {
            display: block;
            width: 25px;
            height: 2.5px;
            background: white;
            margin: 10px 0;
            transition: all 0.3s ease;
        }
        .hamburger.open span:nth-child(1) {
            transform: rotate(45deg) translate(5px, 5px);
        }
        .hamburger.open span:nth-child(2) {
            opacity: 0;
        }
        .hamburger.open span:nth-child(3) {
            transform: rotate(-45deg) translate(7px, -7px);
        }
        nav {
            position: fixed;
            top: 0;
            right: -200px;
            width: 200px;
            height: 100%;
            background-color: #000000; /* Black menu */
            padding: 0.5em;
            transition: right 0.3s ease;
            z-index: 999;
        }
        nav.open {
            down: 0;
        }
        nav a {
            color: white;
            display: block;
            margin: 1.5em 0;
            text-decoration: none;
            font-weight: bold;
            font-size: 1em;
        }
        nav a:hover {
            color: #ff4040;
        }
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 1.5em;
        }
        .section {
            display: none;
            background: rgba(0, 0, 0, 0.8); /* Semi-transparent black for sections */
            padding: 1.5em;
            border-radius: 8px;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.5);
        }
        .section.active {
            display: block;
        }
        #home {
            display: block;
            text-align: center;
        }
        #home img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin: 1.5em 0;
        }
        .room {
            display: inline-block;
            width: 100%;
            max-width: 400px;
            margin: 1.5em;
            text-align: center;
        }
        .room img {
            max-width: 100%;
            height: auto;
            border-radius: 8px;
        }
        .form-group {
            margin-bottom: 1.2em;
        }
        .form-group label {
            display: block;
            margin-bottom: 0.5em;
            font-weight: bold;
        }
        .form-group input, .form-group select {
            width: 100%;
            padding: 0.7em;
            border: 1px solid #fff;
            border-radius: 5px;
            background: #222;
            color: white;
        }
        .payment-options {
            display: none;
        }
        .payment-options.active {
            display: block;
        }
        button {
            background-color: #000000;
            color: white;
            padding: 0.7em 1.5em;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 1em;
        }
        button:hover {
            background-color: #ff4040;
        }
        footer {
            background-color: #000000;
            color: white;
            text-align: center;
            padding: 1em;
            width: 100%;
        }
        @media (max-width: 768px) {
            .container {
                padding: 1em;
            }
            .room {
                width: 100%;
                margin: 0.5em 0;
            }
            nav {
                width: 60%;
                right: -60%;
            }
            nav.open {
                right: 0;
            }
            .hamburger {
                font-size: 1em;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>WELCOME TO</h1>        
        <h1>KINK MAKER'S CAVE</h1>        
        <p>Unleash Your Desires</p>
        
        <a href=><img src="https://i.ibb.co/zV9q4CjM/Screen-Shot-2015-01-19-at-10-15-47-AM.png" alt="Screen-Shot-2015-01-19-at-10.15.47-AM" border="0"></a>                
        
        <div class="hamburger" onclick="toggleMenu()">
            <span></span>
            <span></span>
            <span></span>
        </div>
    </header>
    <nav id="nav-menu">
        <a href="#" onclick="showSection('introduction')">Introduction</a>
        <a href="#" onclick="showSection('rooms')">Rooms</a>
        <a href="#" onclick="showSection('booking')">Book a Reservation</a>
        <a href="#" onclick="showSection('payment')">Payment</a>
    </nav>
    <div class="container">
        <div id="home" class="section active">
            <h2>Step Into Kinkmaker's Cave</h2>
            <p>Indulge in a world of seduction and mystery. Our exclusive dungeon rooms await to fulfill your deepest fantasies. Explore the Black or Red Room and surrender to an unforgettable night of passion.</p>
    <img src="https://i.ibb.co/chZtq4Zd/kink-bg2.png" alt="kink_bg2" border="0"></a><br /><a target='_blank' href='</a><br />
            <p><em>Book now to experience pleasure like never before.</em></p>
            
        </div>
        <div id="introduction" class="section">
            <h2>Introduction</h2>
            <p>Kinkmaker's Cave is your sanctuary for exploration and indulgence. Our Black and Red Rooms offer a provocative escape, blending luxury with raw desire. Perfect for those craving a discreet, sensual adventure.
            
            <div>            
   <h2> <a>Why Choose the Luxurious Kinky Room</a> </h2>  
  

    <h2>Play Room</h2>
<a>A beautifully designed dungeon room equipped with luxurious furnishings and premium BDSM gear.</a>

<p>    
    </p>
    
    <h2>100% Privacy</h2>
<a>Enjoy exclusive access 
no sharing, no interruptions – for your session.</a>
    
    <p>
        </p>
    
    <h2>1H Minimum (50$)</h2>
Everyone can enjoy daytime hire starting at 1H, perfect for an indulgent escape.</a></div>

<div><h1> <a>Explore Our Equipment.</a> </h1>

<p>   
    </p>

       <h2>St. Andrew's Cross</h2>
       
       <a href=><img src="https://i.ibb.co/8LCTzWbd/Whats-App-Image-2024-06-04-at-22-35-19-1-1.jpg" alt="WhatsApp-Image-2024-06-04-at-22.35.19-1-1" border="0"></a>

<div></div>
       
Experience the ultimate restraint with our St. Andrew's Cross, perfect for exploring your limits in a safe and controlled environment.

<p>    
   </p>

         <h2>Whipping Bench</h2>
         
         <a href=><img src="https://i.ibb.co/67ZK0Grd/Whats-App-Image-2024-06-04-at-22-35-21-1-1.jpg" alt="WhatsApp-Image-2024-06-04-at-22.35.21-1-1" border="0"></a>
         
      <div></div>   
         
Enjoy the thrill of impact play with our sturdy whipping bench, designed for comfort and maximum pleasure.

<p></p>

<h2>Throne</h2>

<a href=><img src="https://i.ibb.co/4gV6Gbn1/Whats-App-Image-2024-06-04-at-22-35-19-2.jpg" alt="WhatsApp-Image-2024-06-04-at-22.35.19-2" border="0"></a>

<div></div>

Rule or be ruled from our beautifully crafted throne, offering a regal experience for any dominant or submissive.

<p></p>

<h2>Large Cage</h2>

<a href=><img src="https://i.ibb.co/xtMkFH8S/Il-794x-N-7049631216-72bo.jpg" alt="Il_794xN.7049631216_72bo" border="0"></a>

<div></div>

Embrace your fantasies with our spacious cage, providing a secure and thrilling environment for your play sessions.

<p></p>

<h2>Floggers and Canes</h2>

<a href=><img src="https://i.ibb.co/RtZCBQb/images-1.jpg" alt="images-1" border="0"></a>

<div></div>

A wide variety of floggers and canes are available, allowing you to customize your play and explore different sensations.

<p></p>

<h2>Nipple Clamps and Paddles</h2>



Add intensity to your sessions with our assortment of nipple clamps and paddles, perfect for both gentle and extreme play</a>

</div>

            <div id="rooms" class="section">
              <h3>OUR SEDUCTIVE ROOMS</h3>
                  <div class="room">
                
                
         <div class="room">
             
             <div>
                <h3>RED ROOM</h3>
                 <img src="https://i.ibb.co/twd2tYGj/70-461133-E86-FDAB6-CF59-FEFA92099-FD228.jpg" alt="70-461133-E86-FDAB6-CF59-FEFA92099-FD228" border="0"></a><br /><a target='_blank' href='''</a><br 
                 </div>
                 
        <a>A fiery, passionate retreat with rich decor, igniting your senses for an intense experience.</a>
                 
                </div>       
                
                <h3>BLACK ROOM</h3>
                <a
 href="https://ibb.co/MyP0SHKK"><img src="https://i.ibb.co/HLG84yRR/dsc-0199.jpg" alt="dsc-0199" border="0"></a><br /><a target='_blank' href='''</a><br />
               </div>
               <a href=><img src="https://i.ibb.co/8LCTzWbd/Whats-App-Image-2024-06-04-at-22-35-19-1-1.jpg" alt="WhatsApp-Image-2024-06-04-at-22.35.19-1-1" border="0"></a>

<a href=><img src="https://i.ibb.co/bMF7HGZ5/Whats-App-Image-2024-06-04-at-22-35-20-1.jpg" alt="WhatsApp-Image-2024-06-04-at-22.35.20-1" border="0"></a>
<a href=><img src="https://i.ibb.co/W4KrNyDv/Whats-App-Image-2024-06-04-at-22-35-21.jpg" alt="WhatsApp-Image-2024-06-04-at-22.35.21" border="0"></a>
    
          </div>                       
                         
      <a>A shadowy haven of sleek design, where dark desires come to life with premium amenities.</a>
            </div>
        </div>
        <div id="booking" class="section">
            <h2>Book Your Escape</h2>
            <form id="booking-form">
                <div class="form-group">
                    <label for="room-type">Room Type</label>
                    <select id="room-type" required>
                        <option value="">Select Room</option>
                        <option value="black">Black Room</option>
                        <option value="red">Red Room</option>
                    </select>
                </div>
                <div class="form-group">
                    <label for="date">Date</label>
                    <input type="date" id="date" required>
                </div>
                <div class="form-group">
                    <label for="time">Time</label>
                    <input type="time" id="time" required>
                </div>
                <div class="form-group">
                    <label for="duration">Duration</label>
                    <select id="duration" required>
                        <option value="">Select Duration</option>
                        <option value="1">1 Hour</option>
                        <option value="2">2 Hours</option>
                        <option value="3">3 Hours</option>
                        <option value="4">4 Hours</option>
                        <option value="5">5
Hours</option>   
                        <option value="6">6
Hours</option>                        
                        <option value="overnight">Overnight (12 Hours)</option>
                    </select>
                </div>
                <button type="submit">Proceed to Payment</button>                
            </form>            
        </div>
        <div id="payment" class="section">
            <h2>Secure Your Pleasure</h2>
            <div class="form-group">
                <label for="payment-type">Payment Type</label>
                <select id="payment-type" onchange="togglePaymentOptions()" required>
                    <option value="">Select Payment Type</option>
                    <option value="high-discretion">                  CRYPTO</option>
                    <option value="low-discretion">BANK</option>
                </select>
            </div>
            <div id="high-discretion" class="payment-options">
                <h3>Crypto Payment</h3>
                <div class="form-group">
                    <label for="crypto">Cryptocurrency</label>
                    <select id="crypto" required>
                        <option value="usdt">USDT</option>
                        <option value="usdc">USDC</option>
                    </select>
                </div>
            </div>
            <div id="low-discretion" class="payment-options">
                <h3>Bank Payment</h3>
                <div class="form-group">
                    <label for="bank-payment">Payment Method</label>
                    <select id="bank-payment" required>
                        <option value="paypal">PayPal</option>
                        <option value="cashapp">CashApp</option>
                        <option value="applepay">Apple Pay</option>
                        <option value="venmo">Venmo</option>
                        <option value="zelle">Zelle</option>
                        <option
value="venmo">E-transfer</option>                                   
                    </select>                    
                </div>
            </div>
            <button onclick="reserve()">Reserve</button>
        </div>
    </div>
    <footer>
        <p>&copy; 2023 Kink maker's Cave. All rights reserved.</p>
    </footer>
    <script>
        function toggleMenu() {
            const menu = document.getElementById('nav-menu');
            const hamburger = document.querySelector('.hamburger');
            menu.classList.toggle('open');
            hamburger.classList.toggle('open');
        }

        function showSection(sectionId) {
            document.querySelectorAll('.section').forEach(section => {
                section.classList.remove('active');
            });
            document.getElementById(sectionId).classList.add('active');
            toggleMenu();
            document.getElementById(sectionId).scrollIntoView({ behavior: 'smooth' });
        }

        function togglePaymentOptions() {
            const paymentType = document.getElementById('payment-type').value;
            const highDiscretion = document.getElementById('high-discretion');
            const lowDiscretion = document.getElementById('low-discretion');
            highDiscretion.classList.remove('active');
            lowDiscretion.classList.remove('active');
            if (paymentType === 'high-discretion') {
                highDiscretion.classList.add('active');
            } else if (paymentType === 'low-discretion') {
                lowDiscretion.classList.add('active');
            }
        }

        function reserve() {
            const roomType = document.getElementById('room-type').value;
            const date = document.getElementById('date').value;
            const time = document.getElementById('time').value;
            const duration = document.getElementById('duration').value;
            const paymentType = document.getElementById('payment-type').value;
            let paymentMethod = '';

            if (paymentType === 'high-discretion') {
                paymentMethod = document.getElementById('crypto').value;
            } else if (paymentType === 'low-discretion') {
                paymentMethod = document.getElementById('bank-payment').value;
            }

            if (roomType && date && time && duration && paymentType && paymentMethod) {
                const subject = encodeURIComponent("New Reservation - Kinkmaker's Cave");
                const body = encodeURIComponent(
                    `Reservation Details:\n` +
                    `Room: ${roomType}\n` +
                    `Date: ${date}\n` +
                    `Time: ${time}\n` +
                    `Duration: ${duration}\n` +
                    `Payment Method: ${paymentMethod}`
                );
                window.location.href = `mailto:kinkmakerscave@gmail.com?subject=${subject}&body=${body}`;
                alert('Reservation submitted.');
            } else {
                alert('Please complete all fields before reserving.');
            }
        }

        document.getElementById('booking-form').addEventListener('submit', function(e) {
            e.preventDefault();
            showSection('payment');
        });
    </script>
</body>
</html>
