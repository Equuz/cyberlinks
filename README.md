# cyberlinks
Website idea for useful cybersecurity links in one page far from done, finished and not sanitized yet.

<!DOCTYPE html>
<html>
<title>Useful Cybersecurity links</title>

<head>
</head>

<body text="#ffffff" style="background-image: url('bg.jpg');">
    <center>
        <style>
            .logo:after {
                padding-left: var(--left-spacing);
                color: white;
                font-weight: bold;
                content: '[Useful Cybersecurity Links]';
                animation: flicker 6s infinite;
                font-size: 40px;
                font-family: Consolas
            }

            @keyframes flicker {
                0%,
                19.999%,
                22%,
                62.999%,
                64%,
                64.999%,
                70%,
                100% {
                    opacity: 0.99;
                    text-shadow: -1px -1px 0 $outline, 1px -1px 0 $outline, -1px 1px 0 $outline, 1px 1px 0 $outline,
                    0 -2px 8px, 0 0 2px, 0 0 5px #ff7e00, 0 0 15px #ff4444, 0 0 2px #ff7e00, 0 2px 3px #000;
                }
                20%,
                21.999%,
                63%,
                63.999%,
                65%,
                69.999% {
                    opacity: 0.4;
                    text-shadow: none;
                }
            }
        </style>

        <span class="logo"></span>
    </center>
    

<table><tbody><tr><th>Website check</th></tr><tr><td>Link1</td></tr><tr><td>Link2</td></tr><tr><td>Link3</td></tr></tbody></table>



</body>

</html>
