<!--Registraion--->
<!---Web Development using HTML and CSS--->
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eaten Limited / Registration</title>
    <!--One Time Registration-->
    <link rel="stylesheet" href="registration.css">
</head>
<body>
    <form action="" method="">
        <div class="outerDiv">
            <!--Head-->
            <div class="Heading">
                <h1>Register</h1>
            </div>

            <!--Main-->
            <div class="flexcontainer">
                <div class="outerContainer">
                    <div class="innerContainer">
                        <label for="fname">First Name</label>
                        <input type="text" id="fname"/>
                    </div>
                    <div class="innerContainer">
                        <label for="mname">Middle Name</label>
                        <input type="text" id="mname"/>
                    </div>
                    <div class="innerContainer">
                        <label for="lname">Last Name</label>
                        <input type="text" id="lname">
                    </div>
                    <div class="innerContainer">
                        <label for="age">Age</label>
                        <input type="digit" id="age"/>
                    </div>
                    <div class="innerContainer">
                        <label for="gender" class="select">Gender</label>
                        <select name="" id="gender">
                            <option value="">&lt;---Select---&gt;</option>
                            <option value="">Male</option>
                            <option value="">Female</option>
                            <option value="">Others</option>
                        </select>
                    </div>
                    <div class="innerContainer">
                        <label for="dob">Date of Birth</label>
                        <input type="date" id="dob" />
                    </div>
                    <div class="innerContainer">
                        <label for="father">Father's Name</label>
                        <input type="text" id="father"/>
                    </div>
                    <div class="innerContainer">
                        <label for="mother">Mother's Name</label>
                        <input type="text" id="mother"/>
                    </div>
                    <div class="innerContainer">
                        <label for="pan">PAN</label>
                        <input type="alphanumeric" id="pan" required/>
                    </div>
                    <div class="innerContainer">
                        <label for="locality">Locality</label>
                        <input type="text" id="locality"/>
                    </div>
                    <div class="innerContainer">
                        <label for="post">Post Office</label>
                        <input type="text" id="post"/>
                    </div>
                    <div class="innerContainer">
                        <label for="police">Police Station</label>
                        <input type="text" id="police"/>
                    </div>
                    <div class="innerContainer">
                        <label for="district">District</label>
                        <input type="text" id="district"/>
                    </div>
                    <div class="innerContainer">
                        <label for="state">State</label>
                        <input type="text" id="state"/>
                    </div>
                    <div class="innerContainer">
                        <label for="nationality">Nationality</label>
                        <input type="text" id="nationality"/>
                    </div>
                    <div class="innerContainer">
                        <label for="religion">Religion</label>
                        <input type="text" id="religion"/>
                    </div>
                    <div class="innerContainer">
                        <label for="commity">Community</label>
                        <select name="" id="commity">
                            <option value="">&lt;---Select---&gt;</option>
                            <option value="">ST</option>
                            <option value="">SC</option>
                            <option value="">OBC || MOBC</option>
                            <option value="">General</option>
                        </select>
                    </div>
                    <div class="innerContainer">
                        <label for="mobile">Mobile Number</label>
                        <input type="digit" id="mobile" class=""/>
                    
                    </div>
                    <div class="innerButton">
                        <button id="" class="button">Get OTP</button>
                    </div>
                    <div class="innerContainer">
                        <label for="otp">OTP</label>
                        <input type="digit" id="otp" class=""/>
                    </div>
                    <div class="innerButton">
                        <button id="" class="button">Verify</button>
                    </div>
                </div>
            </div>

            <!--Footer-->
            <div class="mybutton">
                <div class="buttonDiv">
                    <button type="submit" class="buttonStyle" onsubmit="MyRegistration()">Register</button>
                    <button type="reset" class="buttonStyle">Reset</button>
                </div>
            </div>
            <div class="myFuter">
                <div class="myFutter">
                    <p>Already Have an Account ! &nbsp;<a href="Login.html">Login</a></p>
                </div>
            </div>
        </div>

        <!--Javascript-->
        <script>
           
        </script>
    </form>    
</body>
</html>
