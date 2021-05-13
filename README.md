<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- displays site properly based on user's device -->

    <link rel="icon" type="image/png" sizes="32x32" href="./images/favicon-32x32.png">
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
    <title>Frontend Mentor | Fylo landing page with two column layout</title>
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Raleway:wght@400;500&display=swap" rel="stylesheet">

    <!-- Feel free to remove these styles or customise in your own stylesheet 👍 -->
    <style>
        .attribution {
            font-size: 11px;
            text-align: center;
        }
        
        .attribution a {
            color: hsl(228, 45%, 44%);
        }
        
        body {
            background-color: #fff;
        }
        
        .container {
            max-width: 80%;
            margin-top: 20px;
        }
        
        .nav-link {
            font-family: 'Raleway', sans-serif;
            margin-right: 2em;
        }
        
        .nav-link {
            float: right;
        }
        
        .navbar {
            border-radius: 15px;
            background: #fff;
        }
        
        .row {
            padding-top: 20px;
        }
        
        .c2 {
            background-color: #F9F8FE;
            clip-path: ellipse(70% 100% at 50% 100%);
            padding-top: 150px;
        }
        
        .underline::after {
            position: absolute;
            height: 2px;
            width: 24%;
            top: 43%;
            left: 0;
            right: 0;
            margin-top: 2px;
            background-color: #3DA08F;
        }
        
        .card {
            margin-top: 2em;
            background-color: var(--white-color);
            border: 1px solid transparent;
            border-radius: 15px;
            box-shadow: 3px 3px 3px 3px rgb(0, 0, 0, 0.2);
            padding: 2em;
            max-width: 80%;
        }
        
        .c3 {
            background-color: #585989;
        }
        
        .footer {
            background-color: #070439;
        }
        
        .logo {
            filter: invert(98%) sepia(0%) saturate(0%) hue-rotate(0deg) brightness(108%) contrast(101%);
            display: inline-block;
        }
        
        .logo_2 {
            max-width: 40%;
            margin-bottom: 1.5em;
        }
    </style>
</head>

<body>
    <div class="container">
        <nav class="navbar navbar-expand-lg">
            <a href="#" class="navbar-brand">
                <img src="./images/logo.svg" alt="" class="d-inline-block align-top">
            </a>
            <div class="collapse navbar-collapse flex-row-reverse">
                <ul class="navbar-nav">
                    <li class="nav-item active">
                        <a class="nav-link" href="#" style="color:#8182A6;">Features<span class="sr-only">(current)</span></a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#" style="color:#8182A6;">Team</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="#" style="color:#8182A6;">Sign in</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>

    <section class="container">
        <div class="row">
            <div class="col" style="padding-top:80px;">
                <div class="row">
                    <h3 style="font-size:45px; font-weight:bold;font-family: 'Raleway', sans-serif;" class="d-flex justify-content-center align-items-center">
                        All your files in one secure location, accessible anywhere
                    </h3>
                </div>
                <div class="row">
                    <p style="font-size:25px; font-weight:normal" class="d-flex justify-content-center align-items-center">
                        Fylo stores your most important files in one secure location. Access them wherever you need, share and collaborate with friends, family, and co-workers.
                    </p>
                </div>
                <div class="row">
                    <div class="col" style="padding:0; margin:0;">
                        <div class="input-group input-group-lg">
                            <input type="text" class="form-control" placeholder="Enter Your Email..." aria-label="large" aria-describedby="inputGroup-sizing-sm">
                        </div>
                    </div>
                    <div class="col">
                        <button class="btn btn-primary btn-lg" style="padding-right:50px; padding-left:50px;font-weight:normal;">
                            Getting Started
                        </button>
                    </div>
                </div>
            </div>
            <div class="col">
                <img src="./images/illustration-1.svg" alt="illustration-1" width="800" height="600">
            </div>
        </div>
    </section>
    <section class="c2" style="margin-top:100px;padding-bottom:100px">
        <div class="container">
            <div class="row">
                <div class="col" class="underline" style="padding-top:100px">
                    <h3 style="font-size:40px; font-weight:bold;font-family: 'Raleway', sans-serif;">Stay productive, wherever you are</h3>
                    <br>
                    <p style="font-size:20px; font-weight:normal">Never let location be an issue when accessing your files. Fylo has you covered for all of your file storage needs. </p>
                    <p style="font-size:20px; font-weight:normal">Securely share files and folders with friends, family and colleagues for live collaboration. No email attachments required! </p>
                    <a href="#" style="color:#3DA08F; text-decoration:underline; font-size:23px;">See how Fylo works <img src="./images/icon-arrow.svg" width="45" height="45"></a>

                    <div class="card">
                        <div class="card-quote">
                            <img src="./images/icon-quotes.svg" alt="" width="40" height="40">
                        </div>
                        <p style="font-size:1.3rem; font-weight:normal; margin-top:10px;">
                            Fylo has improved our team productivity by an order of magnitude. Since making the switch our team has become a well-oiled collaboration machine.
                        </p>
                        <div class="row">
                            <div class="col-sm-2 col">
                                <img src="./images/avatar-testimonial.jpg" alt="" style="border-radius:50%" width="80" height="80">
                            </div>
                            <div class="col" style="margin-top: 8px;">
                                <div class="row" style="margin:0;padding:0;">
                                    <h4 style="font-family: 'Raleway', sans-serif;font-weight:bolder;padding-left:10px;">Kyle Burton</h4>
                                </div>
                                <div class="row" style="margin:0;padding:0;">
                                    <h5 style="font-family: 'Raleway', sans-serif;padding-left:10px;">Founder & CEO, Huddle</h5>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col" style="padding-top:100px">
                    <img src="./images/illustration-2.svg" alt="illustration-1" width="800" height="600">
                </div>
            </div>
        </div>
    </section>

    <section class="c3">
        <div class="container" style="padding-bottom:60px;margin-top:0;margin-bottom:0;">
            <div class="row">
                <div class="col col-sm-5">
                    <h3 style="font-family: 'Raleway', sans-serif;font-weight:bolder;color:#fff;padding-top:50px;">Get early access today</h3>
                    <p style="font-size:1.2rem; font-weight:normal; margin-top:10px;color:#fff;">
                        It only takes a minute to sign up and our free starter tier is extremely generous. If you have any questions, our support team would be happy to help you.
                    </p>
                </div>
                <div class="col" style="padding-left: 90px;">
                    <div class="form-group" style="padding-top:80px;">
                        <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp" placeholder="Enter your email">
                    </div>
                    <button class="btn btn-primary">
                        Get started for free
                    </button>
                </div>
            </div>
        </div>
    </section>

    <section class="footer">
        <div class="container" style="margin-top:0;margin-bottom:0;padding:50px;">
            <div class="row">
                <div class="col logo_2">
                    <img src="./images/logo.svg" alt="" class="logo row">
                    <div class="row" style="padding-top: 30px;">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#fff" class="bi bi-telephone-plus" viewBox="0 0 16 16">
                            <path d="M3.654 1.328a.678.678 0 0 0-1.015-.063L1.605 2.3c-.483.484-.661 1.169-.45 1.77a17.568 17.568 0 0 0 4.168 6.608 17.569 17.569 0 0 0 6.608 4.168c.601.211 1.286.033 1.77-.45l1.034-1.034a.678.678 0 0 0-.063-1.015l-2.307-1.794a.678.678 0 0 0-.58-.122l-2.19.547a1.745 1.745 0 0 1-1.657-.459L5.482 8.062a1.745 1.745 0 0 1-.46-1.657l.548-2.19a.678.678 0 0 0-.122-.58L3.654 1.328zM1.884.511a1.745 1.745 0 0 1 2.612.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.678.678 0 0 0 .178.643l2.457 2.457a.678.678 0 0 0 .644.178l2.189-.547a1.745 1.745 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.634 18.634 0 0 1-7.01-4.42 18.634 18.634 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877L1.885.511z"/>
                            <path fill-rule="evenodd" d="M12.5 1a.5.5 0 0 1 .5.5V3h1.5a.5.5 0 0 1 0 1H13v1.5a.5.5 0 0 1-1 0V4h-1.5a.5.5 0 0 1 0-1H12V1.5a.5.5 0 0 1 .5-.5z"/>
                        </svg>
                        <p style="color:#fff;margin-left:15px;">Phone: +1-543-123-4567</p>
                    </div>
                    <div class="row" style="padding-top: 0;">
                        <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#fff" class="bi bi-envelope" viewBox="0 0 16 16">
                            <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2V4zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1H2zm13 2.383-4.758 2.855L15 11.114v-5.73zm-.034 6.878L9.271 8.82 8 9.583 6.728 8.82l-5.694 3.44A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.739zM1 11.114l4.758-2.876L1 5.383v5.73z"/>
                        </svg>
                        <p style="color:#fff;margin-left:15px;">example@fylo.com</p>
                    </div>
                </div>
                <div class="col">
                    <div class="row"><a class="nav-link" href="#" style="color:#fff;float:right;">About us</a></div>
                    <div class="row"><a class="nav-link" href="#" style="color:#fff;float:right;">Jobs</a></div>
                    <div class="row">
                        <a class="nav-link" href="#" style="color:#fff;float:right;">Press</a>
                    </div>
                    <div class="row"><a class="nav-link" href="#" style="color:#fff;">Blog</a></div>
                </div>
                <div class="col">
                    <div class="row">
                        <a class="nav-link" href="#" style="color:#fff;float:right;">Contact us</a>
                    </div>
                    <div class="row">
                        <a class="nav-link" href="#" style="color:#fff;float:right;">Teams</a>
                    </div>
                    <div class="row">
                        <a class="nav-link" href="#" style="color:#fff;float:right;">Privacy</a>
                    </div>
                </div>
                <div class="col">
                    <div class="row">
                        <div class="col">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#fff" class="bi bi-facebook" viewBox="0 0 16 16">
                                <path d="M16 8.049c0-4.446-3.582-8.05-8-8.05C3.58 0-.002 3.603-.002 8.05c0 4.017 2.926 7.347 6.75 7.951v-5.625h-2.03V8.05H6.75V6.275c0-2.017 1.195-3.131 3.022-3.131.876 0 1.791.157 1.791.157v1.98h-1.009c-.993 0-1.303.621-1.303 1.258v1.51h2.218l-.354 2.326H9.25V16c3.824-.604 6.75-3.934 6.75-7.951z"/>
                            </svg>
                        </div>
                        <div class="col" style="padding-left:10px">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#fff" class="bi bi-instagram" viewBox="0 0 16 16">
                                <path d="M8 0C5.829 0 5.556.01 4.703.048 3.85.088 3.269.222 2.76.42a3.917 3.917 0 0 0-1.417.923A3.927 3.927 0 0 0 .42 2.76C.222 3.268.087 3.85.048 4.7.01 5.555 0 5.827 0 8.001c0 2.172.01 2.444.048 3.297.04.852.174 1.433.372 1.942.205.526.478.972.923 1.417.444.445.89.719 1.416.923.51.198 1.09.333 1.942.372C5.555 15.99 5.827 16 8 16s2.444-.01 3.298-.048c.851-.04 1.434-.174 1.943-.372a3.916 3.916 0 0 0 1.416-.923c.445-.445.718-.891.923-1.417.197-.509.332-1.09.372-1.942C15.99 10.445 16 10.173 16 8s-.01-2.445-.048-3.299c-.04-.851-.175-1.433-.372-1.941a3.926 3.926 0 0 0-.923-1.417A3.911 3.911 0 0 0 13.24.42c-.51-.198-1.092-.333-1.943-.372C10.443.01 10.172 0 7.998 0h.003zm-.717 1.442h.718c2.136 0 2.389.007 3.232.046.78.035 1.204.166 1.486.275.373.145.64.319.92.599.28.28.453.546.598.92.11.281.24.705.275 1.485.039.843.047 1.096.047 3.231s-.008 2.389-.047 3.232c-.035.78-.166 1.203-.275 1.485a2.47 2.47 0 0 1-.599.919c-.28.28-.546.453-.92.598-.28.11-.704.24-1.485.276-.843.038-1.096.047-3.232.047s-2.39-.009-3.233-.047c-.78-.036-1.203-.166-1.485-.276a2.478 2.478 0 0 1-.92-.598 2.48 2.48 0 0 1-.6-.92c-.109-.281-.24-.705-.275-1.485-.038-.843-.046-1.096-.046-3.233 0-2.136.008-2.388.046-3.231.036-.78.166-1.204.276-1.486.145-.373.319-.64.599-.92.28-.28.546-.453.92-.598.282-.11.705-.24 1.485-.276.738-.034 1.024-.044 2.515-.045v.002zm4.988 1.328a.96.96 0 1 0 0 1.92.96.96 0 0 0 0-1.92zm-4.27 1.122a4.109 4.109 0 1 0 0 8.217 4.109 4.109 0 0 0 0-8.217zm0 1.441a2.667 2.667 0 1 1 0 5.334 2.667 2.667 0 0 1 0-5.334z"/>
                            </svg>
                        </div>
                        <div class="col" style="padding-left:10px">
                            <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="#fff" class="bi bi-twitter" viewBox="0 0 16 16">
                                <path d="M5.026 15c6.038 0 9.341-5.003 9.341-9.334 0-.14 0-.282-.006-.422A6.685 6.685 0 0 0 16 3.542a6.658 6.658 0 0 1-1.889.518 3.301 3.301 0 0 0 1.447-1.817 6.533 6.533 0 0 1-2.087.793A3.286 3.286 0 0 0 7.875 6.03a9.325 9.325 0 0 1-6.767-3.429 3.289 3.289 0 0 0 1.018 4.382A3.323 3.323 0 0 1 .64 6.575v.045a3.288 3.288 0 0 0 2.632 3.218 3.203 3.203 0 0 1-.865.115 3.23 3.23 0 0 1-.614-.057 3.283 3.283 0 0 0 3.067 2.277A6.588 6.588 0 0 1 .78 13.58a6.32 6.32 0 0 1-.78-.045A9.344 9.344 0 0 0 5.026 15z"/>
                            </svg>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </section>
</body>

</html>
