---
layout: mangroves-home
title: Mangroves Pilot Fellows
year: 2022/2023
permalink: /fellows-TEST/
---

<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width">
    <link rel="stylesheet" type="text/css" href="../css/styles.css" />
</head>

<body>
    <div id="wrapper">

        <div class="intro">
            <div class="right-border-box">
                <div class="intro-text">
                    <p><span>Mangroves</span>: a do-think tank. We are small, but <i>dreaming</i> - though never alone. We are concerned with <i>l o n g</i> planetary lifewebs and how they might resprout. As a collaboratory, we stage coworking in-house with staff and annual Fellows, with folks all over, and non-human <i>coactants</i> - always.</p>
                </div>
            </div>
        </div>


        <div class="info-block" id="think-section">
            <div class="right-border-box">
                <div class="section-title" id="think-section-title">
                    <h3>Think</h3>
                </div>
                {% for item in site.data.think %}
                    <div class="think-item">
                        <div class="think-title">
                            <h3>{{ item.title }}</h3>
                        </div>
                        <div class="think-info">
                            <p>{{ item.copy }}</p>
                            <!-- <a href="../think/index.html"><h4>Read more |</h4></a> -->
                        </div>
                    </div>
                {% endfor %}
                <div class="think-info" id="think-link">
                    <a href="../think/index.html"><h4>Read more |</h4></a>
                </div>
            </div>
        </div>
        


        <div class="info-block" id="do-section">
            <div class="right-border-box">
                <div class="section-title" id="do-section-title">
                    <h3>Do</h3>
                    <h4>Going</h4>
                </div>
                {% for item in site.data.do %}
                    <div class="do-item">
                        <div class="do-title-home">
                            <h3>{{ item.title }}</h3>
                        </div>
                        <div class="do-info">
                            <p>{{ item.copy }}</p>
                            <a href="{{ item.url }}"><h4>Read more |</h4></a>
                        </div>
                    </div>
                {% endfor %}
            </div>
        </div>



        <div class="info-block" id="stretching-forth">
            <div class="right-border-box">
                {% for item in site.data.stretching-forth %}
                <div class="do-item" id="stretching-forth-text">
                        <h3>{{ item.title }}</h3>
                        <p>{{ item.copy }}</p>
                </div>
                {% endfor %}
                 <div id="blue-flower-contact">
                </div>
            </div>
        </div>

        <div class="info-block" id="meet-section">
            <div class="right-border-box" id="meet-border-box">
                <div class="intro" id="meet-text">
                    {% for item in site.data.meet %}
                    <div class="section-title" id="meet-item-title">
                        <h3>{{ item.title }}</h3>
                    </div>
                    <div class="do-item" id="meet-item-inside">
                        <div class="do-info">
                            <p>{{ item.copy }}</p>
                            <a href="{{ item.url }}"><h4>Read more |</h4></a>
                        </div>
                    </div>
                {% endfor %}
                </div>
            </div>
        </div>

        <div class="info-block" id="give-section">
            <div class="right-border-box" id="give-border-box">
                <div class="intro" id="give-text">
                    {% for item in site.data.give %}
                    <div class="section-title" id="give-item-title">
                        <h3>{{ item.title }}</h3>
                    </div>
                    <div class="do-item" id="give-item-inside">
                        <div class="do-info">
                            <p>{{ item.copy }}</p>
                            <a href="{{ item.url }}"><h4>Give |</h4></a>
                        </div>
                    </div>
                {% endfor %}
                </div>
            </div>
        </div>


            <div class="info-block" id="reach-section">
            <div class="right-border-box" id="reach-border-box">
                <div class="intro" id="reach-text">
                    {% for item in site.data.reach %}
                    <div class="section-title" id="reach-item-title">
                        <h3>{{ item.title }}</h3>
                    </div>
                    <div class="do-item" id="reach-item-inside">
                        <div class="do-info">
                            <p>{{ item.copy }}</p>
                            <a href="{{ item.url }}"><h4>Read more |</h4></a>
                        </div>
                    </div>
                {% endfor %}
                </div>
            </div>
        </div>






        <div class="info-block" id="contact-section">
            <div class="right-border-box" id="contact-border-box">
                <div id="contact-wrapper">
                    <div id="contact-us">
                        <div id="mailbox">
                            <div class="corner-art" id="curly-mailbox-top-left">
                                <img src="../design/img/dec-border.svg" alt="curlicue-mailbox-top-left">
                            </div>
                            <div class="corner-art" id="curly-mailbox-top-right">
                                <img src="../design/img/dec-border.svg" alt="curlicue-top-right">
                            </div>
                            <div class="corner-art" id="curly-mailbox-bottom-left">
                                <img src="../design/img/dec-border.svg" alt="curlicue-top-right">
                            </div>
                                <div class="corner-art" id="curly-mailbox-bottom-right">
                                <img src="../design/img/dec-border.svg" alt="curlicue-top-right">
                            </div>
                            <div id="contact-info">
                                <h4>contact us at:</h4>
                                <h3>tidings@mangroves.life</h3>
                            </div>
                        </div>
                    </div>

                    <div id="social-media">
                        <div class="social-icon" id="linkedin"></div>
                        <div class="social-icon" id="twitter"></div>
                        <div class="social-icon" id="mastodon"></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</body>