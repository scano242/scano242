<!DOCTYPE html>
<html>
<head>
    <title>Kurland</title>
    <style>
        body {
            /* Variable background */
            background: url('background.jpg');
            background-size: cover;
        }
        #sidebar {
            position: fixed;
            width: 200px;
            height: 100%;
            background: #333;
            color: #fff;
            /* Site sections */
            display: flex;
            flex-direction: column;
            padding: 20px;
        }
        #main-content {
            margin-left: 200px;
            padding: 20px;
        }
        /* Animated address bar */
        @keyframes address-bar {
            0% { width: 0; }
            100% { width: 100%; }
        }
        #address-bar {
            height: 20px;
            background: #00f;
            animation: address-bar 2s linear infinite;
        }
    </style>
</head>
<body>
    <div id="sidebar">
        <h2>Site Sections</h2>
        <!-- Add your site sections here -->
    </div>
    <div id="main-content">
        <div id="address-bar"></div>
        <!-- Add your main content here -->
    </div>
</body>
</html>
<style>
    body {
        background: url('background.jpg');
        background-size: cover;
    }
    #sidebar {
        width: 100%;
        height: auto;
        background: #333;
        color: #fff;
        display: flex;
        flex-direction: column;
        padding: 20px;
    }
    #main-content {
        margin-top: 100px;
        padding: 20px;
    }
    @media (min-width: 600px) {
        #sidebar {
            position: fixed;
            width: 200px;
            height: 100%;
        }
        #main-content {
            margin-left: 200px;
            margin-top: 0;
        }
    }
    @keyframes address-bar {
        0% { width: 0; }
        100% { width: 100%; }
    }
    #address-bar {
        height: 20px;
        background: #00f;
        animation: address-bar 2s linear infinite;
    }
</style>
