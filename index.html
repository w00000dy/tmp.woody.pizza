<!DOCTYPE html>
<html lang="en">

<head>
    <link rel="icon" type="image/svg+xml" href="favicon.svg">
    <link rel="stylesheet" type="text/css" href="style.css">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>woody.pizza</title>
</head>

<body>
    <div class="main">
        <div id="welcome"></div>
    </div>

    <script>
        const ua = navigator.userAgent;
        const isFirefox = /Firefox/i.test(ua);
        const isMobile = /Mobi|Android|iPhone|iPad|iPod|Opera Mini|IEMobile/i.test(ua);

        let chars = ["W", "e", "l", "c", "o", "m", "e", " ", "t", "o", "<br>", "w", "o", "o", "d", "y", ".", "p", "i", "z", "z", "a", "<span class=\"blink\">_</span>"];

        const rainbowPrefix = (!isMobile && !isFirefox) ? '🌈-' : (!isMobile && isFirefox) ? '🌈 ' : '';
        const separator = (isMobile || !isFirefox) ? '-' : ' ';

        let chars_navbar = [rainbowPrefix + "W", "e", "l", "c", "o", "m", "e", separator, "t", "o", separator, "w", "o", "o", "d", "y", ".", "p", "i", "z", "z", "a", "!"];

        let index = 0;
        let x = 0;
        let navbarText = "";
        let titleText = "";

        const addText = isMobile ? "-" : "➖";

        function getRndInteger(min, max) {
            return Math.floor(Math.random() * (max - min + 1)) + min;
        }

        function type() {
            if (index < chars.length) {
                const element = chars[index];
                const element_navbar = chars_navbar[index];
                let oldText = document.getElementById("welcome").innerHTML;
                navbarText = navbarText + element_navbar;
                let text = oldText + element;
                document.getElementById("welcome").innerHTML = text;
                history.pushState(0, 0, navbarText);
                index++;
                setTimeout(type, getRndInteger(100, 200));
            } else {
                index = 0;
                animatedNavbar();
            }
        }

        type();

        function animatedNavbar() {
            if (index < 30) {
                navbarText = addText + navbarText + addText;
            } else if (index < 60) {
                navbarText = navbarText.substr(addText.length, navbarText.lenght);
                navbarText = navbarText.substring(navbarText.length - addText.length, 0);
            } else {
                index = -1;
            }

            index++;
            history.pushState(0, 0, navbarText);
            setTimeout(animatedNavbar, 100);
        }


        function animatedTitle() {
            if (document.title === "➡️ woody.pizza ⬅️") {
                document.title = "➡️woody.pizza⬅️";
            } else {
                document.title = "➡️ woody.pizza ⬅️"
            }
            setTimeout(animatedTitle, 75);
        }
        animatedTitle();
    </script>

</body>

</html>
