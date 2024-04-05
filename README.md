<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="login.css">
</head>

<header>
    <div class="logo">
        <h1 class="line">Nice Car</h1>
        <a href="#myModal4" class="modalclick4">Service</a>
        <a href="#myModal" class="modalclick">About</a>
        <a href="#myModal2" class="modalclick2">Contact</a>

        <div id="myModal4" class="modal">
            <div class="modal-content">
                <span class="close"><a href="#">&times;</a></span>
                <p class="mcontent">
                Nice Car is committed to providing exceptional car rental services for your travels in the Philippines. Whether you're exploring the bustling streets of Manila or the serene beaches of Boracay, we have a wide range of well-maintained vehicles to suit your needs. From muscle cars to sports cars, vans to sedans, and pickup trucks, we offer a diverse selection to cater to your preferences. Our customer service team is dedicated to ensuring a seamless rental experience, from booking to drop-off. With competitive rates, flexible rental periods, and convenient pickup and drop-off locations, Nice Car is your go-to choice for hassle-free car rentals. Experience the beauty of the Philippines with Nice Car - your journey starts here!</p>
            </div>
        </div>


        <div id="myModal" class="modal">
            <div class="modal-content">
                <span class="close"><a href="#">&times;</a></span>
                <p class="mcontent">About Us:
                    <br>
                    At Nice Car, we're dedicated to providing exceptional car rental services for your travels within the Philippines. Our goal is to make your journey unforgettable, whether you're exploring the scenic countryside or navigating the vibrant streets of our cities.
                    With a passion for exploration and a commitment to reliable service, we offer a seamless rental experience, allowing you to focus on the road ahead. Our fleet of well-maintained vehicles is ready to take you on your next adventure, ensuring that every mile is a memory worth cherishing.
                    As a local, family-owned business, we understand the importance of creating lasting memories with loved ones. That's why we strive to make every journey with Nice Car a memorable one, filled with comfort, convenience, and the freedom to explore at your own pace.
                    Join us at Nice Car and experience the beauty of our country from behind the wheel. Your next adventure awaits!</p>
            </div>
        </div>

        <div id="myModal2" class="modal">
            <div class="modal-content">
                <span class="close"><a href="#">&times;</a></span>
                <p class="mcontent">Contact Us: <br>
                    Have questions or need assistance? We're here to help! Reach out to us using the contact information below:<br>  
                    Phone: 09618079349<br>
                    Email: nicecarph.carrental@gmail.com<br>
                    Address: Purok.6, Natvidad, Guagua, Pampanga<br>
                    Our customer service team is available 8:00am-5:00pm to assist you with any inquiries or concerns you may have. We're eager to speak with you and help you with all of your vehicle rental needs!</p>
            </div>
        </div>
        <button onclick="window.location.href='nice car.html'" class="signinbutton" href>Home</button>
    </div>
</header>

<section>
    <h1> WELCOME</h1>
    <p> Let's get you started!</p>
        <input type="text" name="First Name" placeholder="First Name">
        <input type="text" name="Last Name" placeholder="Last Name">
        <br>
        <input type="tel" name="number" placeholder="Phone">
        <input type="Username" name="Username" placeholder="E-mail">
        <br>
        <input type="password" name="password" placeholder=" Create Password">
        <br>
        <input type="checkbox" name="scales"/>
        <label for="scales">I agree to the
        <a href="#myModal3" class="modalclick3">Terms and Conditions</a>
            <div id="myModal3" class="modal">
                <div class="modal-content">
                    <span class="close"><a href="#">&times;</a></span>
                    <p class="mcontent">Terms and Conditions:
                        <br>
                        1. Rental Agreement: By renting a car from Nice Car, you agree to abide by the terms and conditions outlined in this agreement.
                        <br>
                        2. Rental Period: The rental period begins at the scheduled pickup time and ends at the scheduled drop-off time. Any extension of the rental period must be approved in advance.
                        <br>
                        3. Driver Requirements: All drivers must be at least 21 years old and possess a valid driver's license.
                        <br>
                        4. Payment: Payment for the rental must be made in advance. We accept cash, credit/debit cards, and other forms of electronic payment.
                        <br>
                        5. Insurance: Basic insurance is included in the rental price. Additional insurance options are available for purchase.
                        <br>
                        6. Damage and Liability: The renter is responsible for any damage to the car during the rental period. The renter is also liable for any fines or penalties incurred during the rental period.
                        <br>
                        7. Vehicle Use: The rented vehicle may be used for both personal and commercial purposes, provided that the renter complies with all relevant laws and regulations regarding commercial vehicle use.
                        <br>
                        8. Maintenance: The renter is responsible for regular maintenance, such as checking fluid levels and tire pressure, during the rental period.
                        <br>
                        9. Return of Vehicle: The vehicle must be returned in the same condition as it was rented, at the scheduled drop-off time. There is no requirement to return the vehicle with a full tank of gas; however, any fuel consumed during the rental period is the renter's responsibility.
                        <br>
                        10. Cancellation Policy: Cancellations must be made at least 24 hours in advance to avoid a cancellation fee.
                        <br>
                        11. Governing Law: This agreement is governed by the laws of the Philippines.
                        <br>
                        By renting a car from Nice Car, you agree to these terms and conditions.</p>
                </div>
            </div>
        <br>
        <button>Sign Up</button>
        <br>
        <label for="scales">Already have an account?
        <a href="">Log in</a>
</section>
</html
