<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Portfolio</title>
    <!-- <link rel="stylesheet" href="styleList.css"> -->
    <style>
    .Name{
        background-color: rgb(255, 255, 255);
        font-family: 'Courier New', Courier, monospace;
        font-size: 90px;
        color:black;
        padding-left: 20px;
    }
    
    #about {
        background-color: rgba(251, 255, 218, 0.322);
        color: black;
        padding: 10px;
        text-align: center;
      }
    
    .subtitle{
        color: black;
        text-align: center;
        font-size: 70px;
        font-family: 'Brush Script MT', cursive;
    }
    
    .Guad{
        color:black;
        font-size: 30px;
        text-align: center;
    
    }
    
    .image-row {
            display: flex;
            justify-content: center;
        }
        .image-row img {
            width:100px;
            height:100px;
            margin-right: 5px;
            text-align: center;
        }

    #projects{
        background-color: rgb(255, 233, 253);
        color: black;
        padding: 10px;
        /*text-align: center;*/
    }
    
    .project{
        text-align: center;
        font-size:30px;
        font-family: Arial, Helvetica, sans-serif;
    }
    
    .gameName{
        font-family: Fan;
        font-size: 30px;
    }
    

    #gameImage{
            display: block;
            margin-left: auto;
            margin-right: auto;
    }
    
    #Activityjoin{
        background-color: rgb(255, 243, 230);
        color: black;
        padding: 10px;
        /*text-align: center;*/
    }
    
    .Actjoin{
        text-align: center;
        font-size:30px;
        font-family: Arial, Helvetica, sans-serif;
    }
    
    
    .Option {
                background-color: #f2f2f2;
                padding: 10px;
                text-align: center;
            }
    
            nav ul {
                list-style-type: none;
                margin: 0;
                padding: 0;
            }
    
            nav li {
                display: inline-block;
                margin-right: 10px;
            }
    
            nav a {
                text-decoration: none;
                color: #333;
            }
    
            nav li:not(:last-child) {
                margin-right: 100px;
            }
            

    
    </style>
    <script src="script.js"></script>
</head>
<body>
    <header class="Option">
        <nav>
            <ul>
                <li><a href="#Home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#Activityjoin">Activity</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <header class="Name">
        <section id ="Home"><div>
            Lam 
            Chung
            Bun
        </div></section>
    </header>
        <section id="about" >
            <div class="subtitle">About</div>
            <p style="font-size:20px;">Welcome to my portfolio! I am a passionate game programmer with expertise in Unity and C#. </p>
            <p style="font-size:20px;">Guaduated in </p>
            <div class="Guad"> Higher Diploma in Games and Animation, IVE</div> 
            <p> Sep 2020 — Jul 2022</p>

            <div class="Guad"> Digital Media - BSc(Hons), University of the West of England Bristol</div> 
            <p> Sep 2022 — Jul 2023</p>

            <p style="font-size:25px;"><b>Technical skills</b></p>
            <div class="image-row">
                <img src="data:image/png;base64,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" alt="C#">
                <img src="https://cdn.discordapp.com/attachments/1149304864342544456/1150710151217692682/Python.png" alt="Python">
                <img src="https://cdn.discordapp.com/attachments/1149304864342544456/1150710151666487336/html.png" alt="HTML">
                <img src="https://cdn.discordapp.com/attachments/1149304864342544456/1150710151439986798/CSS.png" alt="CSS">
                <img src="https://cdn.discordapp.com/attachments/1149304864342544456/1150710152148824175/unity.png" alt="Unity">
                <img src="https://user-images.githubusercontent.com/48419040/76123305-4c826a00-5fc6-11ea-8c65-4eee21fd386f.png" alt="Maya">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/f/fb/Adobe_Illustrator_CC_icon.svg/1200px-Adobe_Illustrator_CC_icon.svg.png" alt="Adobe Illustor">
                <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/af/Adobe_Photoshop_CC_icon.svg/1200px-Adobe_Photoshop_CC_icon.svg.png" alt="Adobe Photoshop">
            </div>
            
        </section>

        <section id="projects">
            <div class="subtitle">Projects</div> 
            <div class="project">

                <img style="width: 50%; height: auto;" src="https://cdn.discordapp.com/attachments/1149304864342544456/1149304939194109952/B_title.png" alt="BattleDroid Title" width="490px" height="37px" id="gameImage">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/zRp_Cz2Muw8?si=4pnChjdKGPxYnTDU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                <!-- <video src="https://www.youtube.com/watch?v=zRp_Cz2Muw8&ab_channel=%E6%AA%B8%E6%AA%AC" autoplay controls width="1280px" height="720px"></video> -->
                <p style="font-size: 20px;">The game is designed specifically for immersive LED dome displays, equipped with a motion platform, fans, and speaker system, providing players with a realistic 4D gaming experience. Players can take on the role of a pilot, controlling an armored suit from the cockpit and experiencing feedback such as walking, firing, and more. You will find yourself in a diverse universe, using mechanical suits created by scientists to eliminate AI armies and protect the last remnants of humanity.</p>
            </div>
            <div class="project">
                <h3>VR Kung-Fu</h3>
                <iframe width="560" height="315" src="https://www.youtube.com/embed/wY_JvRcWK_s?si=Swd0x0lFzXdCWLH0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                <!--<video src="https://www.youtube.com/watch?v=wY_JvRcWK_s&ab_channel=%E6%AA%B8%E6%AA%AC" autoplay controls width="1280px" height="720px"></video> -->
                <p style="font-size: 20px;">There are many forms of kung fu, such as Shaolin Kung Fu, Wing Chun, Tai Chi, etc., and they are practiced all over the world. Each
                    form of kung fu has its own principles and techniques, but is best known for its trickery and quickness, which is where the world kung fu
                    is derived. References to the concepts and use of Chinese martial arts can be found in popular culture. Historically, the influence of
                    Chinese martial arts can be found in books, performance arts, movies, television and digital games that targets a much wider audience.
                    This is a cross-over between A.I. aided kung fu learning game and VR technology gameplay experience.
                    </p>
            </div>
            <div class="project">
                <img style="width: 50%; height: auto;" src="https://cdn.discordapp.com/attachments/1149304864342544456/1149304938900504576/name.png" alt="AirWing Title" width="1440px" height="330px" id="gameImage">
                <iframe width="560" height="315" src="https://www.youtube.com/embed/T-w9UDAT9S0?si=jevyT-6DVwqn53yC" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
                <!-- <video src="https://www.youtube.com/watch?v=T-w9UDAT9S0&ab_channel=%E6%AA%B8%E6%AA%AC" autoplay controls width="1280px" height="720px"></video> -->
                <p style="font-size: 20px;">Air Wing is a game that combines space fighter gameplay with
                    NFTs to create a unique and engaging gaming experience. By incorporating
                    NFTaircraft into the game, Air Wing provides players with a game world that is
                    more valuable and investment-worthy, thereby enhancing the attractiveness
                    and participation of the game.
                    </p>
            </div>
        </section>
        <section id="Activityjoin">
            <div class="subtitle">Activity</div>
            <div class="Actjoin"> 
                <img style="width: 50%; height: auto;" src="https://static.wixstatic.com/media/ab1367_a2645ab4ef7f47ec89a08136804f39bd~mv2.png/v1/fill/w_626,h_153,al_c,lg_1,q_85,enc_auto/ab1367_a2645ab4ef7f47ec89a08136804f39bd~mv2.png">
                <p style="font-size: 20px;">HKGD Game Competition & Expo 2023 HKGD 遊戲比賽展覽 2023</p>
                <img style="width: 50%; height: auto;" src="https://cdn.discordapp.com/attachments/1149304864342544456/1149307034945196052/Activity.jpg">
            </div>
           
        </section>
        <section id="contact">
            <h2>Contact</h2>
            <p>Feel free to reach out to me for any inquiries or collaboration opportunities.</p>
            <ul>
                <li>Email: lamlam.chungbun@gmail.com</li>
                <li>Phone: 9602 5223</li>
                
                <!-- <li>LinkedIn: <a href="https://www.linkedin.com/">Your LinkedIn Profile</a></li> -->
            </ul>
        </section>

        <footer>
            <p>&copy; 2023 Lam Chung Bun. All rights reserved.</p>
        </footer>

        <script src="script.js"></script>
    </body>
</html>
