
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Novo</title>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="novo.css">
</head>

<body>
    <header>
        <nav>

            <div class="logo">
                <a href="#">Camp Alpha</a>
            </div>
            <div class="nav-links">
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#reservation">Reservation</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <div class="home" id="home">
            <h1>Welcome to Camp Alpha</h1>
            <p>Camp Alpha is primarily a summer facillity, but does have winter capacity for 66 persons in our
                motels, which also include kitchens and private baths. Additional seasonal cabins (374 beds) are also
                available (family cabins with private baths, dorm-style cabins with shared baths, some of which are for
                housekeeping). There are 27 RV sites, as well as designated tents pads, both with and without hookups.
                Recreation includes swimming, boating, softball, basketball, volleyball, and 300 acres of wooded hiking
                trails. The main auditorium seats 1,600, and five meeting rooms are also available.</p>
            <div class="home-img">
                <img src="https://images.unsplash.com/photo-1511632765486-a01980e01a18?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80"
                    alt=""><img
                    src="https://images.unsplash.com/photo-1533873984035-25970ab07461?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1748&q=80"
                    alt=""><img
                    src="https://images.unsplash.com/photo-1440317539597-ad354a025165?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80"
                    alt="">
            </div>
        </div>


        <div class="reservation" id="reservation">
            <h1>Reservation</h1>
            <form action="action_page.php">
                <div class="container">
                    <p id="fill-form">Please fill in this form to make a reservation</p>
                    <hr>
                    <label for="name"><b>Full Name</b></label>
                    <input type="text" placeholder="Full name" name="name" id="name" required>

                    <label for="email"><b>Email Address</b></label>
                    <input type="email" placeholder="Enter Email" name="email" id="email" required>

                    <label for="phone"><b>Phone Number</b></label>
                    <input type="number" placeholder="Phone Number" name="phone" id="phone" required>
                    <hr>
                    <p>Select your room:</p>
                    <div class="radiobtn">
                        <label for="room1"><input type="radio" name="room" id="room1" required>Suite 1</label>
                        <label for="room2"><input type="radio" name="room" id="room2" required>Suite 2</label>
                        <label for="room3"><input type="radio" name="room" id="room3" required>Suite 3</label>
                        <label for="room4"><input type="radio" name="room" id="room4" required>Suite 4</label>
                    </div>
                    <hr>
                    <hr>
                    <label for="address"><b>Address</b></label>
                    <input type="text" name="address" id="address" required>

                    <label for="city"><b>City</b></label>
                    <input type="text" name="city" id="city" required>

                    <label for="state"><b>State</b></label>
                    <input type="text" name="state" id="state" required>

                    <label for="zipcode"><b>Zip Code</b></label>
                    <input type="number" name="zipcode" id="zipcode" required>

                    <hr>
                    <h2>Select Payment Option</h2>
                    <p>A valid form of payment must be presented at check-in</p>
                    <hr>
                    <div class="radiobtn">
                        <label for="payment"><input type="radio" name="payment" id="payment" required>Pay using
                            Credit/Debit Card</label>
                    </div>
                    <hr>
                    <p>Card Information</p>
                    <label for="cardnumber">Credit/Debit Card Number</label>
                    <input type="number" name="cardnumber" id="cardnumber" required>

                    <div class="month-year-input">
                        <label for="expdate"><b>Expiration Date</b></label>
                        <input type="text" placeholder="MM/YYYY" name="expdate" id="expdate" required>
                    </div>
                    <hr>

                    <label for="cvv"><b>CVV Number</b></label>
                    <input type="number" name="cvv" id="cvv" required>

                    <label for="billing"><b>Billing Zip Code</b></label>
                    <input type="number" name="billing" id="billing" required>
                    <hr>

                    <button type="submit" class="registerbtn">Reserve</button>
                </div>

            </form>
        </div>
        <div class="about" id="about">
            <h2>Our History</h2>
            <p>Camp Alpha, a former country club, is located in the beautiful hills of upstate New York, just 80
                miles from New York City. It was purchased in April of 1963 by the Greater New York Conference under the
                administration of Eric Jones. The camp has seen many changes since the early years and remains a
                blessing and haven of rest for those in New York City, as well as those from the surrounding areas. </p>
            <p>Camp Alpha hosts up to six different language campmeetings throughout the year, as well as a United
                campmeeting, youth camp, family camp, and spiritual retreats. We also host many training seminars and
                special events, not only for the Greater New York Conference but for the surrounding conferences as
                well.</p>
            <div class="about-img">
                <img src="https://images.unsplash.com/photo-1520857014576-2c4f4c972b57?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1740&q=80"
                    alt=""><img
                    src="https://scontent-lga3-1.xx.fbcdn.net/v/t39.30808-6/293623127_1394187357749110_3495527142588561350_n.jpg?stp=cp6_dst-jpg&_nc_cat=110&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=vtw0qRYxrB4AX_zKP4T&_nc_ht=scontent-lga3-1.xx&oh=00_AfCe9CzTuWshVH24axs4gdsPF7_D4KAGwWoLZcMUdpo9fQ&oe=6456A91A"
                    alt=""><img
                    src="https://scontent-lga3-2.xx.fbcdn.net/v/t39.30808-6/306638416_1432467690587743_6553786597904401046_n.jpg?stp=cp6_dst-jpg&_nc_cat=101&ccb=1-7&_nc_sid=8bfeb9&_nc_ohc=Du6cGK4sluQAX87Q4Pm&_nc_ht=scontent-lga3-2.xx&oh=00_AfAtGHLaYzw69Oesob5ahUJGrFHpfij2aB4ve1CfhgNl0A&oe=64569674"
                    alt="">
            </div>
            <h2>Facitilies</h2>
            <p>Camp Alpha is primarily a summer facillity, but does have winter capacity for 66 persons in our
                motels, which also include kitchens and private baths. Additional seasonal cabins (374 beds) are also
                available (family cabins with private baths, dorm-style cabins with shared baths, some of which are for
                housekeeping). There are 27 RV sites, as well as designated tents pads, both with and without hookups.
                Recreation includes swimming, boating, softball, basketball, volleyball, and 300 acres of wooded hiking
                trails. The main auditorium seats 1,600, and five meeting rooms are also available</p>
            <h2>Policies</h2>
            <h3>Individual Policies</h3>
            <p>Individual reservation (less than 20 guests)</p>
            <h3>Deposit</h3>
            <p>All reservations require a deposit equal to the minimum cost per lodging unit for the first night’s stay.
                Personal checks are not accepted.
            <p>-Deposits by credit cards will be charged at the time the reservation is taken</p>
            <p>-Deposits by cash can only be accepted in person at Camp</p>
            <p>Please Note:</p>
            <p>$20 of the deposit is non-refundable. </p>
            <h3>Chech in/Check out</h3>
            <p>- Check in 3:00 pm</p>
            <p>- Check out 11:00 am</p>
            <h3>Groups Policies</h3>
            <p>Group (minimum 20 guests)</p>
            <h3>Deposit</h3>
            <p>All group reservations require a deposit equal to the minimum cost per lodging unit for the first night’s
                stay.</p>
            <p> - Deposits by credit cards will be charged at the time the reservation is taken.</p>
            <p> - Deposits by check are accepted only from Conference entities and must be received
                within 10 days.
                or the reservation will be cancelled.</p>
            <p>- Deposits by cash can only be accepted in person at Camp.</p>
            <p> Please Note:</p>
            <p>$100 of the deposit is non-refundable. </p>
            <h2 id="staff">Staff</h2>
            <div class="staff">
                <img src="https://images.unsplash.com/photo-1519085360753-af0119f7cbe7?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
                    alt="">
                <p>Camp Manager</p>
            </div>
            <div class="staff">
                <img src="https://plus.unsplash.com/premium_photo-1674854858248-8987c02e74cf?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=687&q=80"
                    alt="">
                <p>Maintanance Director</p>
            </div>
        </div>

    </main>
    <footer>
        <div class="contact" id="contact">
            <h2>Contact Us</h2>
            <p>Camp - 000 Street Rd, City State 00000</p>
            <p>Reservation (000)000-0000</p>
            <p>Email - camp@gmail.com</p>
            <p><a href="#">camp.org</a></p>
        </div>
    </footer>
</body>

</html>
