# html-
example html program
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link rel="stylesheet" href="DAY5i.css">
</head>

<body>
    <header>
        <div class="header" id="home">
            <h5 style="color: rgb(0, 0, 0);">Name</h5>
            <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#aboutme">About me</a></li>
                <li><a href="#achievement">Achievements</a></li>
                <li><a href="#skill">Skills</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
            </nav>
        </div>
    </header>
    <section>
        <div class="one">
            <h2><br><s>Practice Makes Perfect</s></h2>
            <h2>Perfect Practice Makes Perfect</h2>
        </div>
        <div class="name" id="aboutme">
            <h1>Name</h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quaerat alias dolorum natus laudantium, dignissimos numquam amet quam deserunt in odio explicabo at debitis officia voluptatem<br>vel blanditiis voluptatum nesciunt officiis.</p>
        </div>
        <div class="achievement" id="achievement">
            <h1>Achievements</h1>
            <h3>Some of my best projects so far</h3>
            <div class="line"></div> <br>
            <div class="boxcontainer">
                <div class="box1">
                    <h4> . </h4>
                    <h3>School cricket team Captain</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                    
                </div>
                <div class="box2">
                    <h4>. </h4>
                    <h3>School First</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                
                </div>
                <div class="box3">
                    <h4>.</h4>
                    <h3>Youtuber</h3>
                    <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit.</p>
                
                </div>
            </div>
        </div>
        <div class="skill" id="skill">
            <h1 id="a">Skills</h1>
            <div class="abc">
            <h3>Technical skills</h3>
            <h3>Language skills</h3>
            </div>
            <div class="rating">
                <div class="left">
                    <h3>HTML</h3>
                    <div class="pc">
                    <div class="parenta"></div>
                    <div class="childa"></div>
                    </div>
                    <h3>CSS</h3>
                    <div class="pc">
                    <div class="parentb"></div>
                    <div class="childb"></div>
                    </div>
                    <h3>JavaScript</h3>
                    <div class="pc">
                    <div class="parentc"></div>
                    <div class="childc"></div>
                    </div>
                    <h3>C++</h3>
                    <div class="pc">
                    <div class="parentd"></div>
                    <div class="childd"></div>
                    </div>
                    <h3>Java</h3>
                    <div class="pc">
                    <div class="parente"></div>
                    <div class="childe"></div>
                    </div>
                </div>
                <div class="right">
                    <h3>English</h3>
                    <div class="pc">
                    <div class="aparent"></div>
                    <div class="achild"></div>
                    </div>
                    <h3>Tamil</h3>
                    <div class="pc">
                    <div class="bparent"></div>
                    <div class="bchild"></div>
                    </div>
                    <h3>Hindi</h3>
                    <div class="pc">
                    <div class="cparent"></div>
                    <div class="cchild"></div>
                    </div>
                    <h3>Telugu</h3>
                    <div class="pc">
                    <div class="dparent"></div>
                    <div class="dchild"></div>
                    </div>
                    <h3>Malayalam</h3>
                    <div class="pc">
                    <div class="eparent"></div>
                    <div class="echild"></div>
                    </div>
                </div>
            </div>
        </div>   
        <div class="contact" id="contact">
            <h1>Contact</h1>
            <div>
            <input type="text" placeholder="ENTER YOUR NAME"/>
            </div><br>
            <div>
            <input type="email"  placeholder="ENTER YOUR EMAIL"/>
            </div><br>
            <div>
            <input type="text"  placeholder="ENTER YOUR MESSAGE"/>
            </div><br>
            <div>
            <button type="submit" value="submit">SEND MESSAGE</button>
            </div>
        </div>
    </section>
</body>
</html>
