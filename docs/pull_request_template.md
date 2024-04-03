# Pull Request Template

## Base Code
```html <html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/css/<!--Your css page file-->.css">
    <link rel="stylesheet" href="assets/css/all.min.css">
    <script src="assets/js/all.min.js"></script>
    <title>Dayside</title>
</head>
<body>
    <!--Navbar-->
    <header>
        <nav class="navbar container flex">
            <a href="index.html"><img class="logo" src="assets/img/dsidelogo.png"></a>

            <input type="checkbox" id="menu-toggle"/>
            <label for="menu-toggle" id="hamburger-menu">
                <i class="fa-solid fa-bars"></i>
            </label>

            <ul class="navbarbtns flex">
            <!--Add the button to the page you are making-->
            </ul>
        </nav>
    </header>


    <!--Your code-->
    





    <!--Footer-->
    <footer class="footer">
        <div class="container">
            <span> &copy; DavidModPhone 2024 ,Google Daydream is the trademarks of Google Inc. No Copyright Infringement intended nor commercial intended</span>
    </section>
</html>
```

```css
/* Navbar Code */

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: "Roboto", sans-serif;
}

.logo {
    width: 120px;
    margin: 5 10px;
    cursor: pointer;
}

body {
    background: #f2f2f2;
}

header {
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background: rgb(55, 56, 56);
    z-index: 100;
}

.flex {
    display: flex;
    align-items: center;
}

.container {
    max-width: 1200px;
    width: 100%;
    margin: 0 auto;
    padding: 0 20px;
}

.navbar {
    justify-content: space-between;
}

.navbar a {
    color: white;
    padding: 20px 0;
    display: inline-block;
    text-decoration: none;
    transition: 0.3s;
}

.navbarbtns {
    gap: 20px;  
    list-style: none;
}

.navbar a:hover {
    color: gray;
}

/* Footer */
.footer {
    background: #333;
    padding: 20px 0;
}

.footer span {
    color: white;
}

#menu-toggle, #hamburger-menu {
    display: none;
}

/* Responsive Style Code */
@media (width < 860px) {
    .navbar .navbarbtns {
        position: fixed;
        top: 65px;
        left: 0;
        height: 100%;
        display: block;
        background: #373838;
        width: 300px;
        padding-left: 20px;
        padding-top: 30px;
        left: -100%;
        transition: all 0.3s ease;
    }

    #menu-toggle:checked ~ .navbarbtns {
        left: 0;
    }
    
    .navbarbtns li {
        font-size: 18px;
    }
    
    #hamburger-menu {
        display: block;
        color: white;
        font-size: 22px;
        cursor: pointer;
    }
    
}

@media (width < 560px) {
    
}
```

You can copy these codes on your **Dayside** Page HTML File and implementing your code on your workspace



## Type of change: 

Check the option for a new pull request

- [ ] Typo or Bug fix
- [ ] New page

# Checklist:

- [ ] I have performed a self-review of my code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] Any dependent changes have been merged and published

