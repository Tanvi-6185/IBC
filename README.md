<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Intelligent Border Control System</title>
 <!-- Custom CSS file link -->
 <link rel="stylesheet" href="style.css">

 <!-- Custom script file Link -->
 <script src="script.js"defer></script>
</head>
<body>
    <div class="container">
        <!-- Sidebar -->
        <div class="sidebar">
            <div class="sidebar-header">
                <h2>IBC SYSTEM</h2>
            </div>
            <div class="profile">
                <img src="agent.jpg" alt="Agent Profile" class="profile-pic">
                <p>Hi, Agent Last</p>
            </div>
            <ul class="sidebar-menu">
                <li><a href="#" class="active">Traveler Identity</a></li>
                <li><a href="#">Traveler History</a></li>
                <li><a href="#">Abnormal Behavior</a></li>
                <li><a href="#">Lock Screen</a></li>
                <li><a href="#">Logout</a></li>
            </ul>
        </div>

        <!-- Main content -->
        <div class="main-content">
            <h1>Verify Passenger Identity</h1>
            <div class="steps">
                <div class="step active">STEP 1</div>
                <div class="step">STEP 2</div>
                <div class="step">RESULT</div>
            </div>
            <div class="identity-verification">
                <p>Take a picture of the passenger (passenger.png)</p>
                <div class="passenger-image">
                    <img src="passenger.png" alt="Passenger">
                </div>
                <div class="buttons">
                    <button class="upload-btn">Upload a picture</button>
                    <span>or</span>
                    <button class="camera-btn">Use Camera</button>
                </div>
                <button class="next-btn">Next</button>
            </div>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
<div id="step-1" class="step active">
    <h2>Step 1: Verify Passenger Identity</h2>
    <button id="go-to-step-2">Next</button>
</div>

<div id="step-2" class="step">
    <h2>Step 2: Additional Information</h2>
    <button id="go-to-step-1">Back</button>
    <button id="finish">Finish</button>
</div>
