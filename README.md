<html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width,initial-scale=1.0">
        <title>Gaming Website</title>
        <link rel="stylesheet" href="style.css">
        <link rel="stylesheet" href="">
        <link href='https://unpkg.com/boxicons@2.1.1/css/boxicons.min.css' rel='stylesheet'>
        <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" /> 
    </head>
    <body>
        <header>
            <a href="#" class="logo">Webgame</a>
            <ul class="nav">
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#games">Games</a></li>
                <li><a href="#tournaments">Tournaments</a></li>
                <li><a href="watch.html">Watch</a></li>
            </ul>
            <div class="action">
                <div class="searchBx">
                    <a href="search.html"><i class='bx bx-search'></i> 
                    <input type="text" placeholder="Search Games">
                </div></a>
            </div>
            <div class="toggleMenu" onclick="toggleMenu();"></div>
        </header>
        <nav class="navbar">
        <!-- Home Banner -->
        <div class="banner animeX" id="home">
            <div class="bg">
                <div class="content">
                    <h2> Heaven for gamers</h2>
                    <p>Collection of all mobile and pc games</p>
                    <a href="sign.html" class="btn">login</a>
                </div>
                <img src="assassin.png">
            </div>
        </div>
        <!-- About -->
        <div class="about animeX" id="about">
            <div class="contentBx">
                <h2>About Us</h2>
                <p>"Embark on an electrifying gaming journey at our online hub! Dive into a diverse collection of titles, 
                    from adrenaline-pumping action to brain-teasing puzzles, curated to satisfy every gamer's craving. Join a vibrant global community, 
                    forge friendships, and engage in epic battles. Stay updated with the latest releases and exclusive offers through our news section.
                     With seamless gameplay across desktop, mobile, and tablet, enjoy gaming anytime, anywhere. 
                     Our intuitive interface ensures a hassle-free experience for both seasoned players and newcomers. 
                     Join us today and unleash the thrill of gaming like never before!"
                 </p>
                <a href="#">Read more</a>
            </div>
            <img src="videogame.png">
        </div>
        <!-- Games -->
        <div class="games animeX" id="games">
            <h2>Popular Games</h2>
            <ul>
                <li class="list active" data-filter="all">All</li>
                <li class="list" data-filter="poki">Poki games</li>
                <li class="list" data-filter="pc">Pc games</li>
                <li class="list" data-filter="mobile">Mobile games</li>
                <li class="list" data-filter="mobile">Newly Released</li>
            </ul>
            ------------------------------------------------------------------------------------------------------------------------------
            <div class="cardBx">
                <div class="card" data-item="poki">
                    <img src="po1.jpg">
                    <div class="content">
                        <h4>Grand Theft Auto</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="https://poki.com/en/g/subway-surfers">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="poki">
                    <img src="po2.png">
                    <div class="content">
                        <h4>Grand Theft Auto</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="https://poki.com/en/g/temple-run-2">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="poki">
                    <img src="po3.png">
                    <div class="content">
                        <h4>Grand Theft Auto</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="https://poki.com/en/g/we-become-what-we-behold">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="poki">
                    <img src="po4.jpg">
                    <div class="content">
                        <h4>Grand Theft Auto</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="https://poki.com/en/g/hills-of-steel">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="poki">
                    <img src="po5.jpg">
                    <div class="content">
                        <h4>Grand Theft Auto</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="https://poki.com/en/g/stickman-archero-fight">Play Now</a>
                        </div>
                    </div>
                </div>
               -------------------------------------------------------------------------------------------------------------------------------------- 
                <div class="card" data-item="pc">
                    <img src="game1.png">
                    <div class="content">
                        <h4>Grand Theft Auto</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="pc">
                    <img src="game3.jpg">
                    <div class="content">
                        <h4>Batman Arkham City</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="pc">
                    <img src="game4.png">
                    <div class="content">
                        <h4>Assassins Creed Valhalla</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="pc">
                    <img src="game5.jpg">
                    <div class="content">
                        <h4>Spider man</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="pc">
                    <img src="game6.jpg">
                    <div class="content">
                        <h4>God of War</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                -----------------------------------------------------------------------------------------------------------------------------------
                <div class="card" data-item="mobile">
                    <img src="game7.jpg">
                    <div class="content">
                        <h4>Battle Grounds Mobile</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="mobile">
                    <img src="game8.jpg">
                    <div class="content">
                        <h4>Call Of Duty</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="mobile">
                    <img src="game9.jpg">
                    <div class="content">
                        <h4>Free Fire</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
                <div class="card" data-item="mobile">
                    <img src="game10.jpg">
                    <div class="content">
                        <h4>Shadow Fight Arena</h4>
                        <div class="progress-line"><span></span></div>
                        <div class="info">
                            <a href="search.html"> <i class="fa-solid fa-info"></i></a> 
                            <a href="#">Play Now</a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Tournaments -->
        <div class="tournaments animeX" id="tournaments">
            <h2>Live Tournaments</h2>
            <div class="boxBx">
                <div class="box">
                    <img src="tournament1.jpg">
                    <div class="content">
                        <h4><span>50</span> Matches in progress..</h4>
                        <p> Battlegrounds Mobile India(BGMI),a TPP-FPP survival shooter game in which up to 100 players compete in a battle royale, 
                            a type of large-scale last man standing deathmatch in which players compete to be the last one standing.
                       </p>
                       <div class="btn">
                           <a href="#" class="watch">Watch</a>
                           <a href="#" class="join">Join Now</a>
                       </div>
                    </div>
                </div>
                <div class="box">
                    <img src="tournament2.jpg">
                    <div class="content">
                        <h4><span>30</span> Matches in progress..</h4>
                        <p> Shadow Fight is a series of fighting video games developed by Banzai. Games and published by Nekki. Each game is set in the Far East, 
                            involving martial arts action between combatants that are typically silhouettes.
                       </p>
                       <div class="btn">
                           <a href="#" class="watch">Watch</a>
                           <a href="#" class="join">Join Now</a>
                       </div>
                    </div>
                </div>
                <div class="box">
                    <img src="tournament3.jpg">
                    <div class="content">
                        <h4><span>40</span> Matches in progress..</h4>
                        <p>  game focused on the Second World War,
                             but subsequent games have been set in different times and places, including futuristic worlds and outer space.
                       </p>
                       <div class="btn">
                           <a href="#" class="watch">Watch</a>
                           <a href="#" class="join">Join Now</a>
                       </div>
                    </div>
                </div>
                <div class="box">
                    <img src="tournament4.jpg">
                    <div class="content">
                        <h4><span>40</span> Matches in progress..</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda impedit error 
                        eaque non, quasi recusandae eos? Natus, quibusdam distinctio accusantium ipsa aliquid.
                       </p>
                       <div class="btn">
                           <a href="#" class="watch">Watch</a>
                           <a href="#" class="join">Join Now</a>
                       </div>
                    </div>
                </div>
                <div class="box">
                    <img src="tournament5.jpg">
                    <div class="content">
                        <h4><span>20</span> Matches in progress..</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda impedit error 
                        eaque non, quasi recusandae eos? Natus, quibusdam distinctio accusantium ipsa aliquid.
                       </p>
                       <div class="btn">
                           <a href="#" class="watch">Watch</a>
                           <a href="#" class="join">Join Now</a>
                       </div>
                    </div>
                </div>
                <div class="box">
                    <img src="tournament6.jpg">
                    <div class="content">
                        <h4><span>50</span> Matches in progress..</h4>
                        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Assumenda impedit error 
                        eaque non, quasi recusandae eos? Natus, quibusdam distinctio accusantium ipsa aliquid.
                       </p>
                       <div class="btn">
                           <a href="#" class="watch">Watch</a>
                           <a href="#" class="join">Join Now</a>
                       </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- Contact -->
        <div class="contact animeX" id="contact">
            <img src="contact.jpg">
            <div class="form">
                <h1>Contact Us</h1>
                <div class="inputBx">
                    <p>Enter Name</p>
                    <input type="text" placeholder="Full Name">
                </div>
                <div class="inputBx">
                    <p>Enter Email</p>
                    <input type="text" placeholder="Full Name">
                </div>
                <div class="inputBx">
                    <p>Message</p>
                    <textarea placeholder="Type here..."></textarea>
                </div>
                <div class="inputBx">
                    <input type="submit" name="Submit">
                </div>
            </div>
        </div>
        <!-- Footer -->
        <footer>
            <div class="info">
                <a href="#" class="logo">Webgame</a>
                <p><i class='bx bx-copyright' ></i> 2023 All Rights Reserved</p>
                <ul>
                    <li><a href="#"><i class='bx bxl-facebook' ></i></a></li>
                    <li><a href="#"><i class='bx bxl-instagram' ></i></a></li>
                    <li><a href="#"><i class='bx bxl-twitter' ></i></a></li>
                    <li><a href="#"><i class='bx bxl-youtube' ></i></a></li>
                </ul>
            </div>
        </footer>
        <script>
            /* Sticky NavBar */
            window.addEventListener('scroll',function(){
                var header = document.querySelector('header');
                header.classList.toggle('sticky',window.scrollY > 0);
            });
            /* Responsive NavBar */
            function toggleMenu(){
                const toggleMenu = document.querySelector('.toggleMenu');
                const nav = document.querySelector('.nav');
                toggleMenu.classList.toggle('active')
                nav.classList.toggle('active')
            }
            /* Scrolling Animation Effects */
            window.addEventListener('scroll',function(){
                var anime = document.querySelectorAll('.animeX');
                for(var s = 0; s < anime.length; s++){
                    var windowheight = window.innerHeight;
                    var animetop = anime[s].getBoundingClientRect().top;
                    var animepoint = 150;
                    if(animetop < windowheight - animepoint){
                        anime[s].classList.add('active');
                    }
                    else{
                        anime[s].classList.remove('active');
                    }
                }
            })
           /* Filterable Cards */
            let list = document.querySelectorAll('.list');
            let card = document.querySelectorAll('.card'); 
            for(let i = 0; i<list.length; i++){
                list[i].addEventListener('click',function(){
                    for(let j=0; j<list.length; j++){
                        list[j].classList.remove('active');
                    }
                    this.classList.add('active');
                    let dataFilter = this.getAttribute('data-filter');
                    for( let k=0; k<card.length; k++)
                    {
                        card[k].classList.remove('active');
                        card[k].classList.add('hide');
                        if(card[k].getAttribute('data-item') == dataFilter || dataFilter == 'all'){
                            card[k].classList.remove('hide');
                            card[k].classList.add('active');
                        }
                    }
                })
            }
        </script>
    </body>
</html>
