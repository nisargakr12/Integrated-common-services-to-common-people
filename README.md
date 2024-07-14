<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Integrated Common Services</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #0073e6;
            color: #fff;
            padding: 1rem;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #005bb5;
            padding: 0.5rem;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            padding: 0.5rem 1rem;
        }
        .search-bar {
            display: flex;
            justify-content: center;
            margin: 1rem 0;
        }
        .search-bar input {
            width: 50%;
            padding: 0.5rem;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        .container {
            padding: 2rem;
        }
        .service-section {
            background-color: #fff;
            margin-bottom: 1rem;
            padding: 1rem;
            border-radius: 4px;
            box-shadow: 0 2px 4px rgba(0,0,0,0.1);
        }
        .service-item {
            margin-bottom: 1rem;
        }
        footer {
            background-color: #0073e6;
            color: #fff;
            text-align: center;
            padding: 1rem;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 1rem;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 0.5rem;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
        h2, h3, h4 {
            font-size: larger;
            font-weight: bold;
            text-decoration: underline;
        }
        @media (max-width: 768px) {
            .search-bar input {
                width: 80%;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Integrated Common Services</h1>
        <p>Access all public services in one place</p>
    </header>

    <nav>
        <a href="#health">Health</a>
        <a href="#education">Education</a>
        <a href="#transportation">Transportation</a>
    </nav>

    <div class="search-bar">
        <input type="text" id="search-input" placeholder="Search for services..." onkeyup="searchServices()">
    </div>

    <div class="container">
        <section id="health" class="service-section">
            <h2>Health Services</h2>
            <p>Information about healthcare resources, hospitals, and clinics.</p>
            <!-- Hospitals in Bangalore -->
    <div class="service-item">
        <h3>Hospitals</h3>
        <div>
            <table>
                <thead>
                    <tr>
                        <th>Hospital Name</th>
                        <th>Address</th>
                        <th>Facilities</th>
                        <th>Contact</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Apollo Hospitals</td>
                        <td>154/11, Opp. IIM-B, Bannerghatta Road, Bengaluru</td>
                        <td>Cardiology, Neurology, Orthopedics</td>
                        <td><a href="tel:+918041414141">+91 80 4141 4141</a></td>
                    </tr>
                    <tr>
                        <td>Narayana Health City</td>
                        <td>258/A, Bommasandra Industrial Area, Hosur Road, Bengaluru</td>
                        <td>Oncology, Cardiology, Orthopedics</td>
                        <td><a href="tel:+918033033033">+91 80 3303 3033</a></td>
                    </tr>
                    <tr>
                        <td>Manipal Hospital</td>
                        <td>98, HAL Airport Road, Bengaluru</td>
                        <td>Emergency Services, Pediatrics, Dermatology</td>
                        <td><a href="tel:+918033222222">+91 80 3322 2222</a></td>
                    </tr>
                    <tr>
                        <td>Columbia Asia Hospital</td>
                        <td>Survey No. 10P & 12P, Whitefield Main Road, Bengaluru</td>
                        <td>General Surgery, ENT, Urology</td>
                        <td><a href="tel:+918066002000">+91 80 6600 2000</a></td>
                    </tr>
                    <tr>
                        <td>Fortis Hospital</td>
                        <td>154/9, Bannerghatta Road, Opp. IIM-B, Bengaluru</td>
                        <td>Cardiology, Neurology, Gastroenterology</td>
                        <td><a href="tel:+918033661234">+91 80 3366 1234</a></td>
                    </tr>
                    <tr>
                        <td>Sakra World Hospital</td>
                        <td>SY NO 52/2 & 52/3, Devarabeesanahalli, Varthur Hobli, Bengaluru</td>
                        <td>Neurosurgery, Cardiology, Nephrology</td>
                        <td><a href="tel:+918048202222">+91 80 4820 2222</a></td>
                    </tr>
                    <tr>
                        <td>Bowring and Lady Curzon Hospital</td>
                        <td>Bangalore Medical College and Research Institute, Shivajinagar, Bengaluru</td>
                        <td>Emergency Services, General Medicine, Pediatrics</td>
                        <td><a href="tel:+918022114146">+91 80 2211 4146</a></td>
                    </tr>
                    <tr>
                        <td>M S Ramaiah Memorial Hospital</td>
                        <td>MSR Nagar, MSRIT Post, Mathikere, Bengaluru</td>
                        <td>Orthopedics, Neurology, Oncology</td>
                        <td><a href="tel:+918023166200">+91 80 2316 6200</a></td>
                    </tr>
                    <tr>
                        <td>St. John's Medical College Hospital</td>
                        <td>Sarjapur Road, John Nagar, Bengaluru</td>
                        <td>Cardiology, Oncology, Psychiatry</td>
                        <td><a href="tel:+918022549001">+91 80 2254 9001</a></td>
                    </tr>
                    <tr>
                        <td>Bangalore Baptist Hospital</td>
                        <td>Bellary Road, Hebbal, Bengaluru</td>
                        <td>Orthopedics, Gynecology, Pediatrics</td>
                        <td><a href="tel:+918023519000">+91 80 2351 9000</a></td>
                    </tr>
                    <tr>
                        <td>Mallya Hospital</td>
                        <td>No. 2, Vittal Mallya Road, Bengaluru</td>
                        <td>Cardiology, Nephrology, Endocrinology</td>
                        <td><a href="tel:+918022243000">+91 80 2224 3000</a></td>
                    </tr>
                    <tr>
                        <td>Vikram Hospital</td>
                        <td>71/1, Millers Road, Opposite St. Anne's College, Bengaluru</td>
                        <td>Cardiology, Neurology, Dermatology</td>
                        <td><a href="tel:+918043203333">+91 80 4320 3333</a></td>
                    </tr>
                    <tr>
                        <td>Ramaiah Medical College Hospital</td>
                        <td>MSRIT Post, Mathikere, Bengaluru</td>
                        <td>General Medicine, Surgery, Pediatrics</td>
                        <td><a href="tel:+918023166400">+91 80 2316 6400</a></td>
                    </tr>
                    <tr>
                        <td>Victoria Hospital</td>
                        <td>KR Market, Fort Road, Bengaluru</td>
                        <td>Emergency Services, General Medicine, Psychiatry</td>
                        <td><a href="tel:+918022842000">+91 80 2284 2000</a></td>
                    </tr>
                    <tr>
                        <td>Command Hospital</td>
                        <td>Old Airport Road, Bengaluru</td>
                        <td>Orthopedics, Neurology, Dermatology</td>
                        <td><a href="tel:+918025575505">+91 80 2557 5505</a></td>
                    </tr>
                    <tr>
                        <td>Shanthi Hospital and Research Centre</td>
                        <td>40/1, Thindlu Main Road, Vidyaranyapura, Bengaluru</td>
                        <td>Orthopedics, Cardiology, Neurology</td>
                        <td><a href="tel:+918023726222">+91 80 2372 6222</a></td>
                    </tr>
                    <tr>
                        <td>Sagar Hospitals</td>
                        <td>Shavige Malleshwara Hills, Kumaraswamy Layout, Bengaluru</td>
                        <td>Cardiology, Neurology, Gastroenterology</td>
                        <td><a href="tel:+918026522222">+91 80 2652 2222</a></td>
                    </tr>
                    <tr>
                        <td>Cloudnine Hospital</td>
                        <td>Old Airport Road, Bengaluru</td>
                        <td>Maternity Care, Pediatrics, Neonatology</td>
                        <td><a href="tel:+918041221111">+91 80 4122 1111</a></td>
                    </tr>
                    <tr>
                        <td>Motherhood Hospital</td>
                        <td>Sarjapur Road, Bengaluru</td>
                        <td>Maternity Care, Neonatology, Pediatrics</td>
                        <td><a href="tel:+918041722222">+91 80 4172 2222</a></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>

</section>
        <section id="education" class="service-section">
            <h2>Education Services</h2>
            <p>Details on schools, colleges, and educational programs in Bangalore.</p>
            <div class="service-item">
                <h3>Schools</h3>
                <p>Find information about public and private schools in Bangalore, including admission procedures, facilities, and contact details.</p>
                <!-- Schools in Bangalore -->
    <div class="service-item">
        <div>
            <table>
                <thead>
                    <tr>
                        <th>School Name</th>
                        <th>Address</th>
                        <th>Facilities</th>
                        <th>Contact</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Bishop Cotton Boys' School</td>
                        <td>St. Mark's Road, Bengaluru</td>
                        <td>Sports Facilities, Auditorium, Labs</td>
                        <td><a href="tel:+918022126100">+91 80 2212 6100</a></td>
                    </tr>
                    <tr>
                        <td>Bishop Cotton Girls' School</td>
                        <td>St. Mark's Road, Bengaluru</td>
                        <td>Library, Sports Grounds, Labs</td>
                        <td><a href="tel:+918022210058">+91 80 2221 0058</a></td>
                    </tr>
                    <tr>
                        <td>Baldwin Boys' High School</td>
                        <td>Hosur Road, Richmond Town, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918022273181">+91 80 2227 3181</a></td>
                    </tr>
                    <tr>
                        <td>Baldwin Girls' High School</td>
                        <td>Broadway Road, Richmond Town, Bengaluru</td>
                        <td>Library, Sports Grounds, Labs</td>
                        <td><a href="tel:+918022287272">+91 80 2228 7272</a></td>
                    </tr>
                    <tr>
                        <td>St. Joseph's Boys' High School</td>
                        <td>Museum Road, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918022881000">+91 80 2288 1000</a></td>
                    </tr>
                    <tr>
                        <td>St. Joseph's Girls' High School</td>
                        <td>Langford Road, Bengaluru</td>
                        <td>Library, Sports Grounds, Labs</td>
                        <td><a href="tel:+918022231233">+91 80 2223 1233</a></td>
                    </tr>
                    <tr>
                        <td>Army Public School</td>
                        <td>Kamaraj Road, Bengaluru</td>
                        <td>Computer Labs, Sports Facilities, Auditorium</td>
                        <td><a href="tel:+918022270276">+91 80 2227 0276</a></td>
                    </tr>
                    <tr>
                        <td>National Public School</td>
                        <td>Indiranagar, Bengaluru</td>
                        <td>Library, Sports Complex, Labs</td>
                        <td><a href="tel:+918025200510">+91 80 2520 0510</a></td>
                    </tr>
                    <tr>
                        <td>DPS Bangalore North</td>
                        <td>Survey No 35/1, Sathnur Village, Bagalur Post, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918028761770">+91 80 2876 1770</a></td>
                    </tr>
                    <tr>
                        <td>DPS Bangalore East</td>
                        <td>Survey No 43/1B & 45, Sulikunte Village, Dommasandra Post, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918025732220">+91 80 2573 2220</a></td>
                    </tr>
                    <tr>
                        <td>Vidya Niketan School</td>
                        <td>Hebbal, Bengaluru</td>
                        <td>Library, Sports Grounds, Labs</td>
                        <td><a href="tel:+918023617115">+91 80 2361 7115</a></td>
                    </tr>
                    <tr>
                        <td>Delhi Public School</td>
                        <td>11th KM, Bikaspura Main Road, Kanakapura Road, Konanakunte, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918026648880">+91 80 2664 8880</a></td>
                    </tr>
                    <tr>
                        <td>Kendriya Vidyalaya</td>
                        <td>DRDO Township, CV Raman Nagar, Bengaluru</td>
                        <td>Computer Labs, Sports Facilities, Library</td>
                        <td><a href="tel:+918025277137">+91 80 2527 7137</a></td>
                    </tr>
                    <tr>
                        <td>Greenwood High International School</td>
                        <td>Varthur Sarjapur Road, Bengaluru</td>
                        <td>Library, Sports Complex, Labs</td>
                        <td><a href="tel:+918025903000">+91 80 2590 3000</a></td>
                    </tr>
                    <tr>
                        <td>Inventure Academy</td>
                        <td>Whitefield - Sarjapur Road, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918025081900">+91 80 2508 1900</a></td>
                    </tr>
                    <tr>
                        <td>Greenwood High Pre School</td>
                        <td>Koramangala, Bengaluru</td>
                        <td>Playground, Library, Labs</td>
                        <td><a href="tel:+918025570202">+91 80 2557 0202</a></td>
                    </tr>
                    <tr>
                        <td>Harvest International School</td>
                        <td>Kanakapura Main Road, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918033020000">+91 80 3302 0000</a></td>
                    </tr>
                    <tr>
                        <td>The International School Bangalore (TISB)</td>
                        <td>Whitefield - Sarjapur Road, Bengaluru</td>
                        <td>Library, Sports Complex, Labs</td>
                        <td><a href="tel:+918025318000">+91 80 2531 8000</a></td>
                    </tr>
                    <tr>
                        <td>Vibgyor High School</td>
                        <td>Haralur Road, Off Sarjapur Road, Bengaluru</td>
                        <td>Library, Sports Facilities, Labs</td>
                        <td><a href="tel:+918049003000">+91 80 4900 3000</a></td>
                    </tr>
                    <tr>
                        <td>Ryan International School</td>
                        <td>Kundalahalli, Bengaluru</td>
                        <td>Library, Sports Grounds, Labs</td>
                        <td><a href="tel:+918041513700">+91 80 4151 3700</a></td>
                    </tr>
                    <tr>
                        <td>Stonehill International School</td>
                        <td>Tarahunise Post, Jala Hobli, Bengaluru</td>
                        <td>Library, Sports Complex, Labs</td>
                        <td><a href="tel:+918028909200">+91 80 2890 9200</a></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
        
        
        </div>
            <div class="service-item">
                <h3>Colleges</h3>
                <p>Details on various colleges in Bangalore, including courses offered, admission criteria, and campus facilities.</p>
                <!-- Colleges in Bangalore -->
    <div class="service-item">
        <div>
            <table>
                <thead>
                    <tr>
                        <th>College Name</th>
                        <th>Address</th>
                        <th>Facilities</th>
                        <th>Contact</th>
                    </tr>
                </thead>
                <tbody>
                    <tr>
                        <td>Christ University</td>
                        <td>Hosur Road, Bengaluru</td>
                        <td>Library, Labs, Sports Facilities</td>
                        <td><a href="tel:+918030504000">+91 80 3054 0000</a></td>
                    </tr>
                    <tr>
                        <td>St. Joseph's College of Commerce</td>
                        <td>Brigade Road, Bengaluru</td>
                        <td>Computer Labs, Auditorium, Library</td>
                        <td><a href="tel:+918022850264">+91 80 2285 0264</a></td>
                    </tr>
                    <tr>
                        <td>Mount Carmel College</td>
                        <td>Pallavan House, Vasanth Nagar, Bengaluru</td>
                        <td>Hostel, Gym, Cafeteria</td>
                        <td><a href="tel:+918022240265">+91 80 2224 0265</a></td>
                    </tr>
                    <tr>
                        <td>Bangalore Medical College and Research Institute</td>
                        <td>Fort, K.R. Road, Bengaluru</td>
                        <td>Medical Labs, Hospital Facilities</td>
                        <td><a href="tel:+918022672222">+91 80 2267 2222</a></td>
                    </tr>
                    <tr>
                        <td>Ramaiah Institute of Technology</td>
                        <td>MSR Nagar, Bengaluru</td>
                        <td>Engineering Labs, Library, Sports Complex</td>
                        <td><a href="tel:+918023870000">+91 80 2387 0000</a></td>
                    </tr>
                    <tr>
                        <td>Indian Institute of Science (IISc)</td>
                        <td>C V Raman Ave, Bengaluru</td>
                        <td>Research Labs, Library, Auditorium</td>
                        <td><a href="tel:+918022939999">+91 80 2293 9999</a></td>
                    </tr>
                    <tr>
                        <td>BMS College of Engineering</td>
                        <td>Bull Temple Road, Basavanagudi, Bengaluru</td>
                        <td>Computer Labs, Library, Hostel</td>
                        <td><a href="tel:+918026610614">+91 80 2661 0614</a></td>
                    </tr>
                    <tr>
                        <td>Jain University</td>
                        <td>Jakkasandra Post, Kanakapura Taluk, Ramanagara District, Bengaluru</td>
                        <td>Library, Sports Facilities, Auditorium</td>
                        <td><a href="tel:+918026664626">+91 80 2664 6264</a></td>
                    </tr>
                    <tr>
                        <td>Dayananda Sagar College of Engineering</td>
                        <td>Kumaraswamy Layout, Bengaluru</td>
                        <td>Computer Labs, Library, Sports Complex</td>
                        <td><a href="tel:+918026676161">+91 80 2667 6161</a></td>
                    </tr>
                    <tr>
                        <td>RV College of Engineering</td>
                        <td>Mysore Road, Bengaluru</td>
                        <td>Workshops, Hostel, Library</td>
                        <td><a href="tel:+918026675171">+91 80 2675 1711</a></td>
                    </tr>
                    <tr>
                        <td>Presidency College</td>
                        <td>Kempapura, Hebbal, Bengaluru</td>
                        <td>Library, Cafeteria, Hostel</td>
                        <td><a href="tel:+918032370000">+91 80 3237 0000</a></td>
                    </tr>
                    <tr>
                        <td>International Institute of Information Technology (IIIT-B)</td>
                        <td>Electronic City, Bengaluru</td>
                        <td>Research Labs, Library, Auditorium</td>
                        <td><a href="tel:+918025262000">+91 80 2526 2000</a></td>
                    </tr>
                    <tr>
                        <td>St. Joseph's Institute of Management (SJIM)</td>
                        <td>Mysore Road, Bengaluru</td>
                        <td>Library, Auditorium, Hostel</td>
                        <td><a href="tel:+918026716314">+91 80 2671 6314</a></td>
                    </tr>
                    <tr>
                        <td>MS Ramaiah Medical College</td>
                        <td>MSR Nagar, Bengaluru</td>
                        <td>Hospital Facilities, Medical Labs</td>
                        <td><a href="tel:+918023876000">+91 80 2387 6000</a></td>
                    </tr>
                    <tr>
                        <td>St. John's Medical College</td>
                        <td>Sarjapur Road, Bengaluru</td>
                        <td>Medical Labs, Hospital Facilities</td>
                        <td><a href="tel:+918025371616">+91 80 2537 1616</a></td>
                    </tr>
                    <tr>
                        <td>Mount Carmel Institute of Management</td>
                        <td>Pallavan House, Vasanth Nagar, Bengaluru</td>
                        <td>Library, Auditorium, Hostel</td>
                        <td><a href="tel:+918022240265">+91 80 2224 0265</a></td>
                    </tr>
                    <tr>
                        <td>Army Institute of Hotel Management and Catering Technology</td>
                        <td>Nagareshwara Nagenahalli, Bengaluru</td>
                        <td>Training Kitchens, Hostel, Library</td>
                        <td><a href="tel:+918025535060">+91 80 2553 5060</a></td>
                    </tr>
                    <tr>
                        <td>Kristu Jayanti College</td>
                        <td>K Narayanapura, Kothanur (Post), Bengaluru</td>
                        <td>Library, Auditorium, Sports Facilities</td>
                        <td><a href="tel:+918025814444">+91 80 2581 4444</a></td>
                    </tr>
                    <tr>
                        <td>MES College of Arts, Commerce and Science</td>
                        <td>15th Cross, Malleshwaram, Bengaluru</td>
                        <td>Computer Labs, Library, Sports Facilities</td>
                        <td><a href="tel:+918023326903">+91 80 2332 6903</a></td>
                    </tr>
                </tbody>
            </table>
        </div>
    </div>
            </div>
            <div class="service-item">
             
        </section>

        <section id="transportation" class="service-section">
            <h2>Transportation Services</h2>

            <!-- BMTC Services -->
            <div class="service-item">
                <h3>BMTC Buses</h3>
                <p>Information about Bangalore Metropolitan Transport Corporation (BMTC) bus services, routes, and fare details.</p>
                <div class="service-item">
                    <h4>BMTC Bus Routes</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Bus Number</th>
                                <th>Route</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>201</td>
                                <td>Majestic to Electronic City</td>
                            </tr>
                            <tr>
                                <td>285</td>
                                <td>Shivajinagar to Whitefield</td>
                            </tr>
                            <tr>
                                <td>500C</td>
                                <td>Banashankari to ITPL</td>
                            </tr>
                            <tr>
                                <td>356K</td>
                                <td>Majestic to Kengeri</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>BMTC Bus Fares</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Distance</th>
                                <th>Fare (₹)</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>0-2 km</td>
                                <td>5</td>
                            </tr>
                            <tr>
                                <td>2-4 km</td>
                                <td>10</td>
                            </tr>
                            <tr>
                                <td>4-6 km</td>
                                <td>15</td>
                            </tr>
                            <tr>
                                <td>6-8 km</td>
                                <td>20</td>
                            </tr>
                            <tr>
                                <td>8-10 km</td>
                                <td>25</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>BMTC Passes</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Type</th>
                                <th>Duration</th>
                                <th>Price (₹)</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Monthly Pass</td>
                                <td>1 Month</td>
                                <td>1000</td>
                            </tr>
                            <tr>
                                <td>Student Pass</td>
                                <td>Academic Year</td>
                                <td>550</td>
                            </tr>
                            <tr>
                                <td>Senior Citizen Pass</td>
                                <td>1 Year</td>
                                <td>400</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>BMTC Contact Information</h4>
                    <p>Contact details for BMTC customer support and helpline.</p>
                    <p>Phone: 1800-425-1663</p>
                    <p>Email: feedback@mybmtc.com</p>
                </div>
            </div>

            <!-- Namma Metro Services -->
            <div class="service-item">
                <h3>Namma Metro</h3>
                <p>Information about metro routes, stations, and fare details for Namma Metro in Bangalore. Visit the <a href="http://english.bmrc.co.in" target="_blank">Namma Metro website</a> for more details.</p>
                <div class="service-item">
                    <h4>Metro Routes</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Line</th>
                                <th>Route</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Green Line</td>
                                <td>Nagasandra to Yelachenahalli</td>
                            </tr>
                            <tr>
                                <td>Purple Line</td>
                                <td>Baiyappanahalli to Mysore Road</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>Metro Stations</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Station Name</th>
                                <th>Line</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>MG Road</td>
                                <td>Purple Line</td>
                            </tr>
                            <tr>
                                <td>Vidhana Soudha</td>
                                <td>Purple Line</td>
                            </tr>
                            <tr>
                                <td>Majestic</td>
                                <td>Interchange</td>
                            </tr>
                            <tr>
                                <td>Yelachenahalli</td>
                                <td>Green Line</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>Metro Fare</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Distance</th>
                                <th>Fare (₹)</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>0-2 km</td>
                                <td>10</td>
                            </tr>
                            <tr>
                                <td>2-4 km</td>
                                <td>15</td>
                            </tr>
                            <tr>
                                <td>4-6 km</td>
                                <td>20</td>
                            </tr>
                            <tr>
                                <td>6-8 km</td>
                                <td>25</td>
                            </tr>
                            <tr>
                                <td>8-10 km</td>
                                <td>30</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Suburban Train Services -->
            <div class="service-item">
                <h3>Suburban Trains</h3>
                <p>Details on suburban train routes, timings, and fare in Bangalore.</p>
                <div class="service-item">
                    <h4>Train Routes</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Train Number</th>
                                <th>Route</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>76552</td>
                                <td>Yelahanka to KR Puram</td>
                            </tr>
                            <tr>
                                <td>76523</td>
                                <td>Bangalore City to Hosur</td>
                            </tr>
                            <tr>
                                <td>76555</td>
                                <td>Whitefield to Yeshwantpur</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>Train Timings</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Train Number</th>
                                <th>Departure</th>
                                <th>Arrival</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>76552</td>
                                <td>08:00 AM</td>
                                <td>08:45 AM</td>
                            </tr>
                            <tr>
                                <td>76523</td>
                                <td>09:15 AM</td>
                                <td>10:30 AM</td>
                            </tr>
                            <tr>
                                <td>76555</td>
                                <td>07:30 AM</td>
                                <td>08:15 AM</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>Train Fare</h4>
                    <table>
                        <thead>
                            <tr>
                                <th>Distance</th>
                                <th>Fare (₹)</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>0-5 km</td>
                                <td>10</td>
                            </tr>
                            <tr>
                                <td>5-10 km</td>
                                <td>15</td>
                            </tr>
                            <tr>
                                <td>10-15 km</td>
                                <td>20</td>
                            </tr>
                            <tr>
                                <td>15-20 km</td>
                                <td>25</td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>

            <!-- Ride-sharing Services -->
            <div class="service-item">
                <h3>Ride-sharing Services</h3>
                <p>Information on ride-sharing apps like Uber and Ola, including fare estimates and booking options.</p>
                <div class="service-item">
                    <h4>Uber</h4>
                    <p>Fare Estimate: ₹150-200 for 10 km</p>
                    <p><a href="https://www.uber.com" target="_blank">Book Uber</a></p>
                </div>
                <div class="service-item">
                    <h4>Ola</h4>
                    <p>Fare Estimate: ₹140-190 for 10 km</p>
                    <p><a href="https://www.olacabs.com" target="_blank">Book Ola</a></p>
                </div>
            </div>

            <!-- Bike Sharing Services -->
            <div class="service-item">
                <h3>Bike Sharing</h3>
                <p>Details on bike-sharing services such as Bounce and Yulu, including locations and pricing.</p>
                <div class="service-item">
                    <h4>Bounce</h4>
                    <p>Locations: Available at major metro stations and bus stops.</p>
                    <p>Pricing: ₹5 per km + ₹0.50 per minute</p>
                </div>
                <div class="service-item">
                    <h4>Yulu</h4>
                    <p>Locations: Available at tech parks, metro stations, and public places.</p>
                    <p>Pricing: ₹10 for the first 30 minutes, ₹5 per 10 minutes thereafter</p>
                </div>
            </div>

            <!-- Flight Services -->
            <div class="service-item">
                <h3>Flight Services</h3>
                <p>Information about flights from Kempegowda International Airport, Bangalore.</p>
                <div class="service-item">
                    <h4>Domestic Flights</h4>
                    <p>Find details on domestic flights, including airlines, destinations, and booking options.</p>
                    <table>
                        <thead>
                            <tr>
                                <th>Airline</th>
                                <th>Destination</th>
                                <th>Booking Link</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>IndiGo</td>
                                <td>Delhi</td>
                                <td><a href="https://www.goindigo.in" target="_blank">Book Now</a></td>
                            </tr>
                            <tr>
                                <td>Air India</td>
                                <td>Mumbai</td>
                                <td><a href="https://www.airindia.in" target="_blank">Book Now</a></td>
                            </tr>
                            <tr>
                                <td>SpiceJet</td>
                                <td>Hyderabad</td>
                                <td><a href="https://www.spicejet.com" target="_blank">Book Now</a></td>
                            </tr>
                        </tbody>
                    </table>
                </div>
                <div class="service-item">
                    <h4>International Flights</h4>
                    <p>Find details on international flights, including airlines, destinations, and booking options.</p>
                    <table>
                        <thead>
                            <tr>
                                <th>Airline</th>
                                <th>Destination</th>
                                <th>Booking Link</th>
                            </tr>
                        </thead>
                        <tbody>
                            <tr>
                                <td>Emirates</td>
                                <td>Dubai</td>
                                <td><a href="https://www.emirates.com" target="_blank">Book Now</a></td>
                            </tr>
                            <tr>
                                <td>Singapore Airlines</td>
                                <td>Singapore</td>
                                <td><a href="https://www.singaporeair.com" target="_blank">Book Now</a></td>
                            </tr>
                            <tr>
                                <td>British Airways</td>
                                <td>London</td>
                                <td><a href="https://www.britishairways.com" target="_blank">Book Now</a></td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2024 Integrated Common Services. All rights reserved.</p>
    </footer>

    <script>
        function searchServices() {
            let input = document.getElementById('search-input').value.toLowerCase();
            let sections = document.querySelectorAll('.service-section');
            let items = document.querySelectorAll('.service-item');
            
            sections.forEach(section => {
                section.style.display = 'none'; // Hide all sections initially
            });

            items.forEach(item => {
                item.style.display = 'none'; // Hide all items initially
            });

            sections.forEach(section => {
                if (section.textContent.toLowerCase().includes(input)) {
                    section.style.display = ''; // Show section if it matches the search input
                }
            });

            items.forEach(item => {
                if (item.textContent.toLowerCase().includes(input)) {
                    let parentSection = item.closest('.service-section');
                    parentSection.style.display = ''; // Show parent section if any item matches the search input
                    item.style.display = ''; // Show the item itself
                }
            });
        }
    </script>
</body>
</html>
