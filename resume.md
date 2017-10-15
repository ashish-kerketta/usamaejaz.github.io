<!doctype html>
<html>

<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, user-scalable=no, minimal-ui">
    <title>Usama Ejaz</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/twitter-bootstrap/3.2.0/css/bootstrap.min.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/octicons/2.0.2/octicons.min.css">
    <style type="text/css">
        @import url(https://fonts.googleapis.com/css?family=Lato:400,700);
        body {
            background: #fff;
            font-family: Lato, sans-serif;
            margin: 0 0 80px;
        }

        a {
            color: #2ecc71;
        }

        a:focus,
        a:hover {
            color: #f1c40f;
            text-decoration: none;
        }

        p {
            line-height: 1.5;
            margin: 0;
        }

        p+p {
            margin-top: 10px;
        }

        h1,
        h2,
        h3,
        h4 {
            margin-top: 0
        }

        section {
            margin-top: 30px;
        }

        li {
            line-height: 1.8;
            list-style: none;
        }

        li:before {
            content: "\f052";
            float: left;
            font: 13px Octicons;
            margin-top: 6px;
            margin-left: -20px;
            opacity: .1;
            position: absolute;
        }

        blockquote {
            border-left: 5px solid #e7e9ec;
            font-size: 14px;
        }

        em {
            color: #95a5a6;
            font-weight: normal;
            font-style: normal;
        }

        h4 span:first-child {
            color: #000;
            font-weight: bold;
        }

        .container {
            max-width: 750px;
            padding: 0 30px;
        }

        .col-sm-6 {
            margin-bottom: 10px;
        }

        .col-sm-12 h4 {
            margin-top: 12px;
        }

        .col-sm-12+.col-sm-12 {
            margin-top: 30px;
        }

        #header {
            background: #f4f6f6;
            padding: 50px 0;
            margin-bottom: 30px;
        }

        #header h2 {
            color: #95a5a6;
            font-size: 24px;
        }

        #content h3 {
            color: #f1c40f;
            font-size: 26px;
            margin-top: -4px;
        }

        #content aside {
            text-align: right;
            padding-right: 30px;
        }

        #profiles .network {
            text-transform: capitalize;
        }

        #work .position,
        #volunteer .position {
            font-weight: bold;
            margin-bottom: 8px;
        }

        #education .area {
            font-weight: bold;
        }

        #education .area:before {
            content: "\f0d7";
            font: 16px Octicons;
            margin-right: 6px;
        }

        #education .studyType {
            margin-left: 25px;
        }

        #awards .summary,
        #publications .summary {
            margin-top: 8px;
        }

        #publications .website a:before {
            content: attr(href);
        }

        @media (min-width: 480px) {
            .strike-through {
                border-top: 1px solid #f4f6f6;
                height: 20px;
                margin-top: 12px;
                margin-bottom: -2px;
                position: relative;
            }
            .strike-through span,
            .strike-through a {
                background: #fff;
                position: absolute;
            }
            .strike-through span:first-child {
                padding-right: 20px;
                margin-top: -12px;
            }
            .strike-through span+span {
                font-size: 14px;
                margin-top: -10px;
                padding-left: 20px;
                right: 0;
            }
        }

        @media (max-width: 768px) {
            .col-sm-6:last-child {
                margin-bottom: 0px;
            }
            #content aside {
                margin-bottom: 20px;
                padding-right: 0;
                text-align: left;
            }
            #publications .website a:before {
                content: "View publication";
            }
        }

        @media (max-width: 480px) {
            h1 {
                font-size: 26px;
            }
            .date {
                font-size: 14px;
                margin-bottom: 5px;
            }
            .strike-through span:first-child {
                margin-bottom: 7px;
            }
            .strike-through span {
                display: block;
            }
            #header {
                margin-bottom: 10px;
                padding: 40px 0;
            }
            #actions {
                display: none;
            }
        }
    </style>
</head>

<body>
    <header id="header">
        <div class="container">
            <div class="row">
                <div class="col-sm-9 col-sm-push-3">
                    <h1>
                        Usama Ejaz
                    </h1>
                    <h2>
                        Full Stack Developer
                    </h2>
                </div>
            </div>
        </div>
    </header>
    <div id="content" class="container">
        <section id="contact" class="row">
            <aside class="col-sm-3">
                <h3>Contact</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-6">
                        <strong>Email</strong>
                        <div class="email">
                            <a href="mailto:me@usamaejaz.com">me@usamaejaz.com</a>
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <strong>Website</strong>
                        <div class="website">
                            <a href="https://usamaejaz.com">https://usamaejaz.com</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="about" class="row">
            <aside class="col-sm-3">
                <h3>About</h3>
            </aside>
            <div class="col-sm-9">
                <p>I&#x27;m a full stack developer. I love working with modern and open source tools. I have had much experience
                    in working on small to large-scale apps and projects.</p>
            </div>
        </section>
        <section id="profiles" class="row">
            <aside class="col-sm-3">
                <h3>Profiles</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-6">
                        <strong class="network">
                            twitter
                        </strong>
                        <div class="username">
                            <div class="url">
                                <a href="https://twitter.com/usamaejaz">usamaejaz</a>
                            </div>
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <strong class="network">
                            github
                        </strong>
                        <div class="username">
                            <div class="url">
                                <a href="https://github.com/usamaejaz">usamaejaz</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="work" class="row">
            <aside class="col-sm-3">
                <h3>Work</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-12">
                        <h4 class="strike-through">
                            <span>Glaxosoft</span>
                            <span class="date">
                                2016 —
                            </span>
                        </h4>
                        <div class="website pull-right">
                            <a href="http://glaxosoft.com">http://glaxosoft.com</a>
                        </div>
                        <div class="position">
                            Founder
                        </div>
                        <div class="summary">
                            <p>Glaxosoft is the next-gen IT solutions and services provider.</p>
                        </div>
                        <h4>Highlights</h4>
                        <ul class="highlights">
                            <li class="bullet">Built large-scale apps</li>
                            <li class="bullet">Contributed towards Government projects</li>
                            <li class="bullet">Open source contributions</li>
                        </ul>
                    </div>
                    <div class="col-sm-12">
                        <h4 class="strike-through">
                            <span>Trakdesk</span>
                            <span class="date">
                                2015 — 2017
                            </span>
                        </h4>
                        <div class="website pull-right">
                            <a href="https://trakdesk.com">https://trakdesk.com</a>
                        </div>
                        <div class="position">
                            Co-Founder
                        </div>
                        <div class="summary">
                            <p>Trakdesk is a fully customizable customer support platform with all the bells and whistles you
                                would need to provide exceptional customer support. I worked on it from scratch.</p>
                        </div>
                        <h4>Highlights</h4>
                        <ul class="highlights">
                            <li class="bullet">One of the best customer support solutions in the market</li>
                            <li class="bullet">Fast, efficient and super-easy to use than competitors</li>
                        </ul>
                    </div>
                    <div class="col-sm-12">
                        <h4 class="strike-through">
                            <span>Noble Care Malaysia</span>
                            <span class="date">
                                2014 —
                            </span>
                        </h4>
                        <div class="website pull-right">
                            <a href="https://www.mynoblecare.com">https://www.mynoblecare.com</a>
                        </div>
                        <div class="position">
                            Web Developer
                        </div>
                        <div class="summary">
                            <p>Noble Care Malaysia is Asia&#x27;s best elderly care and nursing services provider. Operating
                                homes and retirement resorts. </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="education" class="row">
            <aside class="col-sm-3">
                <h3>Education</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-12">
                        <h4 class="strike-through">
                            <span>Information Technology University, Punjab</span>
                            <span class="date">
                                2017 —
                            </span>
                        </h4>
                        <div class="area">
                            Management and Technology
                        </div>
                        <div class="studyType">
                            Bachelors
                        </div>
                    </div>
                    <div class="col-sm-12">
                        <h4 class="strike-through">
                            <span>Government College of Science, Wahdat Road</span>
                            <span class="date">
                                2013 — 2014
                            </span>
                        </h4>
                        <div class="area">
                            Medical Sciences
                        </div>
                        <div class="studyType">
                            F.Sc.
                        </div>
                    </div>
                    <div class="col-sm-12">
                        <h4 class="strike-through">
                            <span>Government Pilot Secondary School, Wahdat Road</span>
                            <span class="date">
                                2011 — 2012
                            </span>
                        </h4>
                        <div class="area">
                            Sciences
                        </div>
                        <div class="studyType">
                            Matriculation
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="awards" class="row">
            <aside class="col-sm-3">
                <h3>Awards</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-12">
                        <h4 class="strike-through">
                            <span>Time Person Of The Year</span>
                        </h4>
                        <div class="date pull-right">
                            <em>Awarded</em>
                            2006-12-25
                        </div>
                        <div class="awarder">
                            <em>by</em>
                            <strong>Time Magazine</strong>
                        </div>
                        <div class="summary">
                            Chosen as the Time Person Of The Year
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="skills" class="row">
            <aside class="col-sm-3">
                <h3>Skills</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-6">
                        <div class="name">
                            <h4>Frontend</h4>
                        </div>
                        <ul class="keywords">
                            <li>HTML</li>
                            <li>CSS</li>
                            <li>Javascript</li>
                            <li>VueJS</li>
                            <li>React</li>
                            <li>jQuery</li>
                        </ul>
                    </div>
                    <div class="col-sm-6">
                        <div class="name">
                            <h4>Backend</h4>
                        </div>
                        <ul class="keywords">
                            <li>NodeJS</li>
                            <li>PHP</li>
                            <li>Laravel</li>
                        </ul>
                    </div>
                    <div class="col-sm-6">
                        <div class="name">
                            <h4>More</h4>
                        </div>
                        <ul class="keywords">
                            <li>Python</li>
                            <li>Java</li>
                            <li>C++</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
        <section id="languages" class="row">
            <aside class="col-sm-3">
                <h3>Languages</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-6">
                        <div class="language">
                            <strong>English</strong>
                        </div>
                        <div class="fluency">
                            Fluent
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <div class="language">
                            <strong>Urdu</strong>
                        </div>
                        <div class="fluency">
                            Native speaker
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <div class="language">
                            <strong>Arabic</strong>
                        </div>
                        <div class="fluency">
                            Learning
                        </div>
                    </div>
                    <div class="col-sm-6">
                        <div class="language">
                            <strong>Persian / Farsi</strong>
                        </div>
                        <div class="fluency">
                            Learning
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="interests" class="row">
            <aside class="col-sm-3">
                <h3>Interests</h3>
            </aside>
            <div class="col-sm-9">
                <div class="row">
                    <div class="col-sm-6">
                        <div class="name">
                            <h4>Literature</h4>
                        </div>
                        <ul class="keywords">
                            <li>Non-fiction</li>
                            <li>Poetry</li>
                        </ul>
                    </div>
                    <div class="col-sm-6">
                        <div class="name">
                            <h4>Sufism</h4>
                        </div>
                        <ul class="keywords">
                            <li>Truth</li>
                            <li>Mysticism</li>
                            <li>Love</li>
                            <li>Knowledge</li>
                        </ul>
                    </div>
                </div>
            </div>
        </section>
    </div>
</body>

</html>