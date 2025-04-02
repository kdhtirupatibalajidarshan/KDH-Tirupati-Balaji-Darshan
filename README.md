<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>KDH Tirupati Balaji Darshan - Complete Travel Packages</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        
        body {
            background-color: #f5f5f5;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(135deg, #ff9933, #ff6600);
            color: white;
            padding: 20px 0;
            text-align: center;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        
        .logo {
            font-size: 2.5rem;
            font-weight: bold;
            margin-bottom: 10px;
        }
        
        .tagline {
            font-size: 1.2rem;
            font-style: italic;
        }
        
        nav {
            background-color: #333;
            padding: 15px 0;
        }
        
        nav ul {
            display: flex;
            justify-content: center;
            list-style: none;
        }
        
        nav ul li {
            margin: 0 15px;
        }
        
        nav ul li a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            padding: 5px 10px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        
        nav ul li a:hover {
            background-color: #ff6600;
        }
        
        .hero {
            background: url('https://example.com/tirupati-temple.jpg') no-repeat center center/cover;
            height: 500px;
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            color: white;
            position: relative;
        }
        
        .hero::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0,0,0,0.5);
        }
        
        .hero-content {
            position: relative;
            z-index: 1;
            max-width: 800px;
            padding: 20px;
        }
        
        .hero h1 {
            font-size: 3rem;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0,0,0,0.5);
        }
        
        .hero p {
            font-size: 1.2rem;
            margin-bottom: 30px;
        }
        
        .btn {
            display: inline-block;
            background: #ff6600;
            color: white;
            padding: 12px 30px;
            border: none;
            border-radius: 5px;
            font-size: 1.1rem;
            cursor: pointer;
            text-decoration: none;
            transition: background 0.3s;
        }
        
        .btn:hover {
            background: #cc5200;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        
        section {
            padding: 50px 0;
        }
        
        h2 {
            text-align: center;
            margin-bottom: 40px;
            color: #ff6600;
            font-size: 2.2rem;
        }
        
        .packages {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            gap: 30px;
        }
        
        .package-card {
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            overflow: hidden;
            flex: 1 1 300px;
            transition: transform 0.3s;
        }
        
        .package-card:hover {
            transform: translateY(-10px);
        }
        
        .package-img {
            height: 200px;
            overflow: hidden;
        }
        
        .package-img img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.5s;
        }
        
        .package-card:hover .package-img img {
            transform: scale(1.1);
        }
        
        .package-content {
            padding: 20px;
        }
        
        .package-content h3 {
            color: #ff6600;
            margin-bottom: 15px;
            font-size: 1.5rem;
        }
        
        .package-content p {
            margin-bottom: 15px;
            color: #666;
        }
        
        .price {
            font-size: 1.8rem;
            font-weight: bold;
            color: #333;
            margin: 20px 0;
        }
        
        .price span {
            font-size: 1rem;
            color: #666;
            font-weight: normal;
        }
        
        .features {
            margin: 30px 0;
        }
        
        .features h3 {
            text-align: center;
            margin-bottom: 20px;
            color: #ff6600;
        }
        
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }
        
        .feature-item {
            background: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 3px 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        
        .feature-item i {
            font-size: 2.5rem;
            color: #ff6600;
            margin-bottom: 15px;
        }
        
        .feature-item h4 {
            margin-bottom: 10px;
            color: #333;
        }
        
        .itinerary {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
            margin-top: 30px;
        }
        
        .day {
            margin-bottom: 30px;
            border-left: 3px solid #ff6600;
            padding-left: 20px;
        }
        
        .day h3 {
            color: #ff6600;
            margin-bottom: 10px;
        }
        
        .day ul {
            list-style-position: inside;
            margin-left: 10px;
        }
        
        .day ul li {
            margin-bottom: 8px;
        }
        
        .testimonials {
            background: #f9f9f9;
            padding: 50px 0;
        }
        
        .testimonial-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
        }
        
        .testimonial-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .testimonial-card p {
            font-style: italic;
            margin-bottom: 20px;
        }
        
        .client-info {
            display: flex;
            align-items: center;
        }
        
        .client-info img {
            width: 60px;
            height: 60px;
            border-radius: 50%;
            object-fit: cover;
            margin-right: 15px;
        }
        
        .client-name {
            font-weight: bold;
            color: #333;
        }
        
        .contact {
            background: linear-gradient(135deg, #ff9933, #ff6600);
            color: white;
            padding: 50px 0;
            text-align: center;
        }
        
        .contact h2 {
            color: white;
        }
        
        .contact-form {
            max-width: 600px;
            margin: 0 auto;
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .form-group {
            margin-bottom: 20px;
            text-align: left;
        }
        
        .form-group label {
            display: block;
            margin-bottom: 5px;
            color: #333;
            font-weight: bold;
        }
        
        .form-group input,
        .form-group textarea,
        .form-group select {
            width: 100%;
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 5px;
            font-size: 1rem;
        }
        
        .form-group textarea {
            height: 150px;
        }
        
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 30px 0;
        }
        
        .footer-links {
            display: flex;
            justify-content: center;
            margin-bottom: 20px;
        }
        
        .footer-links a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
        }
        
        .footer-links a:hover {
            text-decoration: underline;
        }
        
        .social-icons {
            margin-bottom: 20px;
        }
        
        .social-icons a {
            color: white;
            margin: 0 10px;
            font-size: 1.5rem;
        }
        
        /* Contact Sections Styling */
        .contact-sections {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 40px;
        }
        
        .contact-section {
            background: rgba(255,255,255,0.1);
            backdrop-filter: blur(5px);
            border-radius: 10px;
            overflow: hidden;
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        
        .contact-section-header {
            background: rgba(0,0,0,0.2);
            padding: 20px;
            display: flex;
            align-items: center;
            gap: 15px;
        }
        
        .contact-section-header i {
            font-size: 1.5rem;
            color: #ff9933;
        }
        
        .contact-section-header h3 {
            margin: 0;
            color: white;
        }
        
        .contact-section-body {
            padding: 20px;
        }
        
        /* Contact Methods Styling */
        .contact-method {
            display: flex;
            gap: 15px;
            margin-bottom: 20px;
            align-items: center;
        }
        
        .contact-method i {
            font-size: 1.5rem;
            color: #ff9933;
            width: 40px;
            height: 40px;
            background: rgba(255,255,255,0.1);
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        
        .contact-method h4 {
            color: white;
            margin-bottom: 5px;
            font-size: 1.1rem;
        }
        
        .contact-method p {
            margin: 0;
            color: #ddd;
            font-size: 0.9rem;
        }
        
        .whatsapp-link {
            display: inline-block;
            background: #25D366;
            color: white;
            padding: 5px 10px;
            border-radius: 5px;
            font-size: 0.8rem;
            margin-top: 5px;
            text-decoration: none;
        }
        
        /* Business Hours Styling */
        .business-hours {
            margin-bottom: 20px;
        }
        
        .day-hour {
            display: flex;
            justify-content: space-between;
            padding: 10px 0;
            border-bottom: 1px solid rgba(255,255,255,0.1);
        }
        
        .day-hour.emergency {
            color: #ff9933;
            border-bottom: none;
        }
        
        .day-hour .day {
            font-weight: bold;
        }
        
        .day-hour .hours {
            color: #ddd;
        }
        
        /* Social Media Styling */
        .social-media {
            margin-top: 30px;
        }
        
        .social-media h4 {
            color: white;
            text-align: center;
            margin-bottom: 15px;
        }
        
        .social-media .social-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
        }
        
        .social-media .social-icons a {
            color: white;
            background: rgba(255,255,255,0.1);
            width: 40px;
            height: 40px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: all 0.3s;
        }
        
        .social-media .social-icons a:hover {
            background: #ff9933;
            transform: translateY(-3px);
        }
        
        /* Map Styling */
        .contact-map {
            margin-top: 20px;
            border-radius: 8px;
            overflow: hidden;
        }
        
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                align-items: center;
            }
            
            nav ul li {
                margin: 5px 0;
            }
            
            .hero {
                height: 400px;
            }
            
            .hero h1 {
                font-size: 2rem;
            }
            
            .contact-sections {
                grid-template-columns: 1fr;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
</head>
<body>
    <header>
        <div class="logo">KDH Tirupati Balaji Darshan</div>
        <div class="tagline">Experience Divine Bliss with Our Exclusive Pilgrimage Packages</div>
    </header>
    
    <nav>
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#packages">Packages</a></li>
            <li><a href="#itinerary">Itinerary</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#testimonials">Testimonials</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    
    <section class="hero" id="home">
        <div class="hero-content">
            <h1>Divine Tirupati Balaji Darshan Packages</h1>
            <p>Experience the spiritual journey of a lifetime with our carefully curated Tirupati packages. We handle all arrangements so you can focus on your devotion.</p>
            <a href="#packages" class="btn">View Packages</a>
        </div>
    </section>
    
    <section class="container" id="packages">
        <h2>Our Exclusive Packages</h2>
        <div class="packages">
            <div class="package-card">
                <div class="package-img">
                    <img src="https://example.com/standard-package.jpg" alt="Standard Package">
                </div>
                <div class="package-content">
                    <h3>Standard Darshan Package</h3>
                    <p>Perfect for budget-conscious pilgrims who want a comfortable journey with all essential amenities.</p>
                    <ul>
                        <li>2 Days / 1 Night</li>
                        <li>General Darshan</li>
                        <li>AC Accommodation</li>
                        <li>Veg Meals</li>
                    </ul>
                    <div class="price">₹4,999 <span>per person</span></div>
                    <a href="#contact" class="btn">Book Now</a>
                </div>
            </div>
            
            <div class="package-card">
                <div class="package-img">
                    <img src="https://example.com/premium-package.jpg" alt="Premium Package">
                </div>
                <div class="package-content">
                    <h3>Premium Darshan Package</h3>
                    <p>Enjoy priority darshan and premium accommodations for a more comfortable spiritual experience.</p>
                    <ul>
                        <li>3 Days / 2 Nights</li>
                        <li>Special Entry Darshan</li>
                        <li>3-Star Hotel Stay</li>
                        <li>All Meals Included</li>
                    </ul>
                    <div class="price">₹7,999 <span>per person</span></div>
                    <a href="#contact" class="btn">Book Now</a>
                </div>
            </div>
            
            <div class="package-card">
                <div class="package-img">
                    <img src="https://example.com/vip-package.jpg" alt="VIP Package">
                </div>
                <div class="package-content">
                    <h3>VIP Darshan Package</h3>
                    <p>The ultimate spiritual experience with VIP darshan, luxury accommodations, and personalized services.</p>
                    <ul>
                        <li>4 Days / 3 Nights</li>
                        <li>VIP Darshan with Less Wait Time</li>
                        <li>4-Star Hotel Stay</li>
                        <li>Guided Temple Tour</li>
                    </ul>
                    <div class="price">₹12,999 <span>per person</span></div>
                    <a href="#contact" class="btn">Book Now</a>
                </div>
            </div>
        </div>
    </section>
    
    <section class="features" id="features">
        <div class="container">
            <h2>Why Choose Our Packages?</h2>
            <div class="features-grid">
                <div class="feature-item">
                    <i class="fas fa-hands-praying"></i>
                    <h4>Hassle-Free Darshan</h4>
                    <p>We arrange all necessary passes and tokens for smooth darshan experience.</p>
                </div>
                
                <div class="feature-item">
                    <i class="fas fa-bus"></i>
                    <h4>Comfortable Transport</h4>
                    <p>AC vehicles for all local transfers and pick-up/drop from your city.</p>
                </div>
                
                <div class="feature-item">
                    <i class="fas fa-hotel"></i>
                    <h4>Quality Accommodation</h4>
                    <p>Carefully selected hotels close to the temple with all basic amenities.</p>
                </div>
                
                <div class="feature-item">
                    <i class="fas fa-utensils"></i>
                    <h4>Satvik Meals</h4>
                    <p>Delicious vegetarian meals included as per the package.</p>
                </div>
                
                <div class="feature-item">
                    <i class="fas fa-user-tie"></i>
                    <h4>Expert Guides</h4>
                    <p>Knowledgeable guides to enhance your spiritual journey.</p>
                </div>
                
                <div class="feature-item">
                    <i class="fas fa-headset"></i>
                    <h4>24/7 Support</h4>
                    <p>Our team is available round the clock to assist you.</p>
                </div>
            </div>
        </div>
    </section>
    
    <section class="container" id="itinerary">
        <h2>Sample Itinerary</h2>
        <div class="itinerary">
            <div class="day">
                <h3>Day 1: Arrival in Tirupati</h3>
                <ul>
                    <li>Pickup from airport/railway station/bus stand</li>
                    <li>Transfer to hotel and check-in</li>
                    <li>Evening visit to Govindaraja Swamy Temple</li>
                    <li>Dinner and overnight stay at hotel</li>
                </ul>
            </div>
            
            <div class="day">
                <h3>Day 2: Tirumala Darshan</h3>
                <ul>
                    <li>Early morning departure to Tirumala</li>
                    <li>Breakfast enroute</li>
                    <li>Darshan of Lord Venkateswara (as per package type)</li>
                    <li>Hair tonsuring (optional) and temple rituals</li>
                    <li>Visit to Padmavathi Temple and other shrines</li>
                    <li>Return to Tirupati in the evening</li>
                    <li>Dinner and overnight stay at hotel</li>
                </ul>
            </div>
            
            <div class="day">
                <h3>Day 3: Local Sightseeing & Departure</h3>
                <ul>
                    <li>Morning visit to Kapila Theertham and other temples</li>
                    <li>Shopping for religious souvenirs</li>
                    <li>Check-out from hotel</li>
                    <li>Drop at airport/railway station/bus stand</li>
                </ul>
            </div>
        </div>
    </section>
    
    <section class="testimonials" id="testimonials">
        <div class="container">
            <h2>What Our Pilgrims Say</h2>
            <div class="testimonial-grid">
                <div class="testimonial-card">
                    <p>"The KDH Tirupati package made our pilgrimage so smooth. The VIP darshan arrangement saved us hours of waiting and the hotel was excellent. Will definitely use their services again!"</p>
                    <div class="client-info">
                        <img src="https://example.com/client1.jpg" alt="Ramesh Patel">
                        <div>
                            <div class="client-name">Ramesh Patel</div>
                            <div>Mumbai</div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p>"As first-time visitors to Tirupati, we were nervous about the arrangements. KDH took care of everything - transport, accommodation, darshan passes. Their guide was very knowledgeable."</p>
                    <div class="client-info">
                        <img src="https://example.com/client2.jpg" alt="Sunita Sharma">
                        <div>
                            <div class="client-name">Sunita Sharma</div>
                            <div>Delhi</div>
                        </div>
                    </div>
                </div>
                
                <div class="testimonial-card">
                    <p>"We booked the premium package for our family of 5. Everything was well-organized, the food was good, and the darshan experience was divine. Highly recommended!"</p>
                    <div class="client-info">
                        <img src="https://example.com/client3.jpg" alt="Vikram Reddy">
                        <div>
                            <div class="client-name">Vikram Reddy</div>
                            <div>Bangalore</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <section class="contact" id="contact">
        <h2>Book Your Divine Journey</h2>
        <div class="contact-form">
            <form action="#" method="POST">
                <div class="form-group">
                    <label for="name">Full Name</label>
                    <input type="text" id="name" name="name" required>
                </div>
                
                <div class="form-group">
                    <label for="email">Email Address</label>
                    <input type="email" id="email" name="email" required>
                </div>
                
                <div class="form-group">
                    <label for="phone">Phone Number</label>
                    <input type="tel" id="phone" name="phone" required>
                </div>
                
                <div class="form-group">
                    <label for="package">Select Package</label>
                    <select id="package" name="package" required>
                        <option value="">-- Select Package --</option>
                        <option value="standard">Standard Darshan Package</option>
                        <option value="premium">Premium Darshan Package</option>
                        <option value="vip">VIP Darshan Package</option>
                    </select>
                </div>
                
                <div class="form-group">
                    <label for="travel-date">Travel Date</label>
                    <input type="date" id="travel-date" name="travel-date" required>
                </div>
                
                <div class="form-group">
                    <label for="people">Number of People</label>
                    <input type="number" id="people" name="people" min="1" required>
                </div>
                
                <div class="form-group">
                    <label for="message">Special Requirements</label>
                    <textarea id="message" name="message"></textarea>
                </div>
                
                <button type="submit" class="btn">Submit Booking Request</button>
            </form>
        </div>
        
        <div class="container">
            <div class="contact-sections">
                <!-- Office Address Section -->
                <div class="contact-section">
                    <div class="contact-section-header">
                        <i class="fas fa-map-marker-alt"></i>
                        <h3>Our Office</h3>
                    </div>
                    <div class="contact-section-body">
                        <p>123 Temple Street<br>
                        Near Balaji Temple<br>
                        Tirupati, Andhra Pradesh - 517501</p>
                        
                        <div class="contact-map">
                            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3880.123456789012!2d79.12345678901234!3d13.123456789012345!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMTPCsDA3JzI0LjQiTiA3OcKwMDcnMjQuNCJF!5e0!3m2!1sen!2sin!4v1234567890123!5m2!1sen!2sin" 
                            width="100%" height="200" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
                        </div>
                    </div>
                </div>
                
                <!-- Contact Methods Section -->
                <div class="contact-section">
                    <div class="contact-section-header">
                        <i class="fas fa-phone-alt"></i>
                        <h3>Contact Us</h3>
                    </div>
                    <div class="contact-section-body">
                        <div class="contact-method">
                            <i class="fas fa-phone"></i>
                            <div>
                                <h4>Phone</h4>
                                <p>+91 98765 43210</p>
                                <p>+91 98765 43211</p>
                            </div>
                        </div>
                        
                        <div class="contact-method">
                            <i class="fab fa-whatsapp"></i>
                            <div>
                                <h4>WhatsApp</h4>
                                <p>+91 98765 43210</p>
                                <a href="https://wa.me/919876543210" class="whatsapp-link">Chat Now</a>
                            </div>
                        </div>
                        
                        <div class="contact-method">
                            <i class="fas fa-envelope"></i>
                            <div>
                                <h4>Email</h4>
                                <p>bookings@kdhtirupati.com</p>
                                <p>support@kdhtirupati.com</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <!-- Business Hours Section -->
                <div class="contact-section">
                    <div class="contact-section-header">
                        <i class="fas fa-clock"></i>
                        <h3>Business Hours</h3>
                    </div>
                    <div class="contact-section-body">
                        <div class="business-hours">
                            <div class="day-hour">
                                <span class="day">Monday - Saturday</span>
                                <span class="hours">8:00 AM - 8:00 PM</span>
                            </div>
                            <div class="day-hour">
                                <span class="day">Sunday</span>
                                <span class="hours">9:00 AM - 6:00 PM</span>
                            </div>
                            <div class="day-hour emergency">
                                <span class="day">24/7 Support</span>
                                <span class="hours">For existing bookings only</span>
                            </div>
                        </div>
                        
                        <div class="social-media">
                            <h4>Connect With Us</h4>
                            <div class="social-icons">
                                <a href="#"><i class="fab fa-facebook-f"></i></a>
                                <a href="#"><i class="fab fa-instagram"></i></a>
                                <a href="#"><i class="fab fa-twitter"></i></a>
                                <a href="#"><i class="fab fa-youtube"></i></a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <footer>
        <div class="footer-links">
            <a href="#home">Home</a>
            <a href="#packages">Packages</a>
            <a href="#itinerary">Itinerary</a>
            <a href="#features">Features</a>
            <a href="#testimonials">Testimonials</a>
            <a href="#contact">Contact</a>
            <a href="#">Privacy Policy</a>
            <a href="#">Terms & Conditions</a>
        </div>
        
        <div class="social-icons">
            <a href="#"><i class="fab fa-facebook-f"></i></a>
            <a href="#"><i class="fab fa-twitter"></i></a>
            <a href="#"><i class="fab fa-instagram"></i></a>
            <a href="#"><i class="fab fa-youtube"></i></a>
        </div>
        
        <p>&copy; 2023 KDH Tirupati Balaji Darshan. All Rights Reserved.</p>
    </footer>
</body>
</html>
