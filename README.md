# ljundt.github.io
<!DOCTYPE html>
<html>
    
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <title>LJ Website</title>
        <meta name="description" content="Work work work">
        <link rel="stylesheet" href="mine.css">
    </head>
    <script type="text/javascript";>
    var picCount=0;
    var picArray=["pond.jpg", "monkey.jpg", "dinosaur.jpeg", "vantage.jpg"]
    function nextPic() {
        picCount= (picCount+1<picArray.length)? picCount+1 : 0;
        var build='<img src="'+picArray[picCount]+'">'; document.getElementById("imgHolder").innerHTML=build;
        setTimeout('nextPic()', 10000)
    }
    </script>
    <style>
        imgHolder{ position:absolute; top:50px; left:100px; text-align:right; }
    </style>
    <body onload="setTimeout('nextPic()',10000)">
        <div class="topnav">
            <nohover>*******</nohover>
            <a href="mine.html">About Me</a>
            <a href="education.html">Education</a>
            <a href="work.html">Work Experience</a>
            <a href="projects.html">Chinese Projects</a>
        </div>
        
        <h1>Lia Jundt</h1>
        <h2>Software Engineer</h2>
        <itemp>
        <div id="imgHolder"><img src="pond.jpg" style="float:right"></div>
        Lia Jundt was born at Stanford Hospital in 1995 and grew up in the heart of Silicon Valley. She graduated from Palo Alto High School and continued her education at Hamilton College in upstate New York. At Hamilton, she began studying computer science and Chinese. Over her years studying and working as a teaching assistant, she gained recognition and her Senior year became the Rusty Smith Head Teaching Assistant of the Computer Science Department. For two summers she worked at Qylur Intelligent Systems as a Software Engineer Intern, producing applications used internationally. 
        </itemp><br>
        <itemp>
        In her free time, Lia enjoys Chinese martial arts, singing, and watching stand up comedy.
        </itemp>
    </body>
</html>
