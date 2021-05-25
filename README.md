<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width-devicewidth, initial-scale=1.0">
    <title>Media Query</title>
    <script type="text/javascript" src="https://gc.kis.v2.scr.kaspersky-labs.com/FD126C42-EBFA-4E12-B309-BB3FDD723AC1/main.js?attr=ysE4vMIiU92YTAYlMXes4qH-4CotCP2pB1czycvNaoOcvtdf70uS6vvJxnQnTBtgJW9D5YAyzl88B9omC1m15DBcKuJ35mHZdehRDI4NB6HdvWmGt2LdBiU0E41Vq4uDIrD7x3INbvchcztlaaVqUyp3Ve1k-wx8oJVpoz6dPH_5jwr1O5IqobbxeY8P3oo0pdIVagxPQ8wk81Od1rw2j53apmWnBg9Jr-CiVQQHjXxu2xZ8_-YQVzyRMT2cj3PFmTU9Q3LuqkHEiZ0-WKSiaAUHFB71q1dJmnEp2CsBqIHpcKIIG6Tz1e94ogxqofNNtdGpkBF69fgZ-f2N4wzsuO4gug_hNotzNya5qfDDrUc8tJWp2Iqi9zO75orMZTh7DvakbdR_Zon1pKtbZ-xGreMNVq-wmJ3KzpgtIbHz2Tcph1ZJctMZ7fZE12xjUhO-lN3Io4EpCtniD0og5tlGTpN9f49gIhI97j51xt2GA5o" charset="UTF-8"></script><style>
        h1 {
            margin-bottom: 10px;
        }
        
        p {
            margin-bottom: 10px;
            border: 1px solid black;
        }
        
        #p1 {
            background-color: blueviolet;
            width: 300px;
            height: 300px;
        }
        
        #p2 {
            background-color: darkgreen;
            width: 50px;
            height: 50px;
        }
        
        @media(min-width:1200px) {
            #p1 {
                background-color: red;
                width: 80%;
            }
            #p2 {
                background-color: brown;
                width: 100px;
            }
        }
        
        @media(min-width:992px) and (max-width:1199px) {
            #p1 {
                background-color: goldenrod;
                width: 50%;
            }
            #p2 {
                background-color: black;
                width: 100%;
            }
        }
    </style>
</head>

<body>
    <h1>Media Query</h1>

    <p id="p1"></p>
    <p id="p2"></p>

</body>

</html>
