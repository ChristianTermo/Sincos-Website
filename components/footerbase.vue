<template>
    <div style="clear:both">
        <footer class="footer-distributed">

            <div class="footer-left">

                <img src="~/static/assets/sincoshomelogo.png" />
                <p style="color:white" class="footer-company-name">SINCOS GROUP S.r.l. © 2023</p>
            </div>

            <div class="footer-center">
                <span style="color:white">Dove trovarci</span>
                <div>
                    <p>&#9873;</p>
                    <p><span>Via Panciatichi, 38/5</span> 50127 Firenze</p>
                </div>
                <div>
                    <p>&#9742;</p>
                    <p>+39 0550752333</p>
                </div>
                <div>
                    <p>&#9993;</p>
                    <p>info@sincos.it</p>
                </div>
                <div>
                    <a href="#">
                        <svg xmlns="http://www.w3.org/2000/svg" width="16" height="16" fill="currentColor" class="bi bi-linkedin" viewBox="0 0 16 16">
                        <path d="M0 1.146C0 .513.526 0 1.175 0h13.65C15.474 0 16 .513 16 1.146v13.708c0 .633-.526 1.146-1.175 1.146H1.175C.526 16 0 15.487 0 14.854V1.146zm4.943 12.248V6.169H2.542v7.225h2.401zm-1.2-8.212c.837 0 1.358-.554 1.358-1.248-.015-.709-.52-1.248-1.342-1.248-.822 0-1.359.54-1.359 1.248 0 .694.521 1.248 1.327 1.248h.016zm4.908 8.212V9.359c0-.216.016-.432.08-.586.173-.431.568-.878 1.232-.878.869 0 1.216.662 1.216 1.634v3.865h2.401V9.25c0-2.22-1.184-3.252-2.764-3.252-1.274 0-1.845.7-2.165 1.193v.025h-.016a5.54 5.54 0 0 1 .016-.025V6.169h-2.4c.03.678 0 7.225 0 7.225h2.4z"/>
                        </svg>
                        <p>Linkedin</p>
                    </a>
                </div>


            </div>

            <div class="footer-right">
                <p class="footer-company-about">
                    <span>About the company</span>
                    Dal 1988 creiamo software.
                </p>
            </div>
        </footer>
    </div>

</template>



<style>
@import url(https://fonts.googleapis.com/css?family=Open+Sans:400,500,300,700);

* {
    font-family: Open Sans;
}


.footer-distributed {
    background: #0C004C;
    box-shadow: 0 1px 1px 0 rgba(0, 0, 0, 0.12);
    box-sizing: border-box;
    width: 100%;
    text-align: left;
    font: bold 16px sans-serif;
    padding-top: 3%;
    padding-left: 3%;
    padding-right: 3%;
    padding-bottom: 1%;
}

.footer-distributed .footer-left,
.footer-distributed .footer-center,
.footer-distributed .footer-right {
    display: inline-block;
    vertical-align: top;
}

/* Footer left */

.footer-distributed .footer-left {
    width: 40%;
}

/* The company logo */

.footer-distributed h3 {
    color: #ffffff;
    font: normal 36px 'Open Sans', cursive;
    margin: 0;
}

.footer-distributed h3 span {
    color: lightseagreen;
}

/* Footer links */

.footer-distributed .footer-links {
    color: #ffffff;
    margin: 20px 0 12px;
    padding: 0;
}

.footer-distributed .footer-links a {
    display: inline-block;
    line-height: 1.8;
    font-weight: 400;
    text-decoration: none;
    color: inherit;
}

.footer-distributed .footer-company-name {
    color: #222;
    font-size: 14px;
    font-weight: normal;
    margin: 0;
}

/* Footer Center */

.footer-distributed .footer-center {
    width: 35%;
}

.footer-distributed .footer-center i {
    background-color: #33383b;
    color: #ffffff;
    font-size: 25px;
    width: 38px;
    height: 38px;
    border-radius: 50%;
    text-align: center;
    line-height: 42px;
    margin: 10px 15px;
    vertical-align: middle;
}

.footer-distributed .footer-center i.fa-envelope {
    font-size: 17px;
    line-height: 38px;
}

.footer-distributed .footer-center p {
    display: inline-block;
    color: #ffffff;
    font-weight: 400;
    vertical-align: middle;
    margin: 0;
}

.footer-distributed .footer-center p span {
    display: block;
    font-weight: normal;
    font-size: 14px;
    line-height: 2;
}

.footer-distributed .footer-center p a {
    color: lightseagreen;
    text-decoration: none;
    ;
}

.footer-distributed .footer-links a:before {
    content: "|";
    font-weight: 300;
    font-size: 20px;
    left: 0;
    color: #fff;
    display: inline-block;
    padding-right: 5px;
}

.footer-distributed .footer-links .link-1:before {
    content: none;
}

/* Footer Right */

.footer-distributed .footer-right {
    width: 20%;
}

.footer-distributed .footer-company-about {
    line-height: 20px;
    color: #92999f;
    font-size: 13px;
    font-weight: normal;
    margin: 0;
}

.footer-distributed .footer-company-about span {
    display: block;
    color: #ffffff;
    font-size: 14px;
    font-weight: bold;
    margin-bottom: 20px;
}

.footer-distributed .footer-icons {
    margin-top: 25px;
}

.footer-distributed .footer-icons a {
    display: inline-block;
    width: 35px;
    height: 35px;
    cursor: pointer;
    background-color: #33383b;
    border-radius: 2px;

    font-size: 20px;
    color: #ffffff;
    text-align: center;
    line-height: 35px;

    margin-right: 3px;
    margin-bottom: 5px;
}

/* If you don't want the footer to be responsive, remove these media queries */

@media (max-width: 880px) {

    .footer-distributed {
        font: bold 14px sans-serif;
    }

    .footer-distributed .footer-left,
    .footer-distributed .footer-center,
    .footer-distributed .footer-right {
        display: block;
        width: 100%;
        text-align: center;
    }

    .footer-distributed .footer-center i {
        margin-left: 0;
    }

}
</style>
