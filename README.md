# CovidChatBot
<!DOCTYPE html>
<html>
<head>
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <style>
        body, html {
            height: 100%;
            margin: 0;
            font-family: Arial, Helvetica, sans-serif;
        }

        * {
            box-sizing: border-box;
        }

        .bg-image {
            /* The image used */
            background-image: url("https://www.who.int/images/default-source/mca/mca-covid-19/coronavirus-2.tmb-1920v.jpg?Culture=en&sfvrsn=4dba955c_6%201920w");
            /* Add the blur effect */
            filter: blur(2px);
            -webkit-filter: blur(2px);
            /* Full height */
            height: 100%;
            /* Center and scale the image nicely */
            background-position: center;
            background-repeat: no-repeat;
            background-size: cover;
        }

        /* Position text in the middle of the page/image */
        .bg-text {
            background-color: rgb(0,0,0); /* Fallback color */
            background-color: rgba(0,0,0, 0.4); /* Black w/opacity/see-through */
            color: white;
            font-weight: bold;
            border: 3px solid #f1f1f1;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            z-index: 2;
            width: 80%;
            padding: 20px;
            text-align: left;
        }
    </style>
    
</head>
<body>

    <div class="bg-image"></div>

    <div class="bg-text">
        <h2></h2>
        <h1 style="font-size:50px">Welcome to Covid_ChatBot!</h1>

        <h2>Ask me anything:-)</h2>

        <iframe src='https://webchat.botframework.com/embed/covidchatbot-abbcc-bot?s=raU66RR_0wM.12c2bH137-uuUxkk-tfytCXr5GWWwizitXFtrfiqmBk'  style='min-width: 400px; width: 100%; min-height: 500px;'></iframe>
      
    </div>
        

</body>
</html>
