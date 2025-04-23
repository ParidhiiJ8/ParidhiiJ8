<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
    .split-container{
        display: flex;
       overflow:hidden;
        justify-content: center;
        align-items: center;
        margin: 0;
        vertical-align: baseline;
        gap: 5px;
    }

    .text-left, .text-right{
        display: inline-block;
        position: relative;
        transform: translateX(0);
        animation-duration: 2s;
        animation-timing-function: ease-out;
        animation-fill-mode: forwards;
        vertical-align: baseline;
        margin: 0;
    }

    .text-left{
        transform: translateX(-200%);
        color: white;
        animation-name: slide-in-left;
    }
    .text-right{
        text-transform: uppercase;
        transform: translateX(200%);
        animation-name: slide-in-right,glow;
        font-size: 3.5rem;
        font-weight: bold;
        color: #00ffff; /* Electric Cyan */
text-shadow:
    0 0 5px #80ffff,
    0 0 10px #80ffff,
    0 0 20px #b3ffff,
    0 0 40px #ccffff,
    0 0 80px #e6ffff;

        animation-duration: 2s,1.5s;
        animation-timing-function: ease-out,ease-in-out;
        animation-fill-mode: forwards,alternate;
        animation-iteration-count: 1,infinite;
    }

    @keyframes glow {
  0% {
    text-shadow:
      0 0 5px #87cefa,
      0 0 10px #7ec8f8,
      0 0 20px #6ebff5,
      0 0 40px #5eb5f2,
      0 0 80px #4eabef;
  }
  100% {
    text-shadow:
      0 0 10px #add8e6,
      0 0 20px #9cd2e4,
      0 0 40px #8acce1,
      0 0 80px #79c6df,
      0 0 160px #68c0dc;
  }
}



    @keyframes slide-in-left{
        0%{
            transform: translateX(-200%);
            }
        100%{
            transform: translateX(0);
        }
    }

    @keyframes slide-in-right{
        0%{
            transform: translateX(200%);
            }
        100%{
            transform: translateX(0);
        }
    }
    
    </style>
</head>
<body >
    <div class="split-container">
    <h1 align="center"  class="text-left">Hi 👋, I'm </h1>
   
    <h1 align="center"  class="text-right"> Paridhi Jain</h1>
</div>
<h3 align="center">Passionate about problem-solving, eager to learn and grow!</h3>
<img align="right" alt="passion" width="400" src="https://cdn.dribbble.com/users/1364029/screenshots/16093268/media/68e82a7fb4904614a9066d6b540c14b2.gif"> 

<p align="left"> <img src="https://komarev.com/ghpvc/?username=paridhiij8&label=Profile%20views&color=0e75b6&style=flat" alt="paridhiij8" /> </p>

- 🌱 I’m currently learning **C++, Python, DSA, and JavaScript**



<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/paridhi jain" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="paridhi jain" height="30" width="40" /></a>

<a href="https://instagram.com/pari.dhi_25" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/instagram.svg" alt="pari.dhi_25" height="30" width="40" /></a>

  <a href="https://www.facebook.com/share/16DGpGB7mD/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/facebook.svg" alt="Paridhi Jain" height="30" width="40" /></a>

</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left">
 <a href="https://www.cprogramming.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" alt="c" width="40" height="40"/> </a> <a href="https://www.w3schools.com/cpp/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/cplusplus/cplusplus-original.svg" alt="cplusplus" width="40" height="40"/></a>
  <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a>
 <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a>
 <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
</p>

<p>
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs?username=paridhiij8&show_icons=true&locale=en&layout=compact" alt="paridhiij8" /></p>

<p>&nbsp;<img align="center" src="https://github-readme-stats.vercel.app/api?username=paridhiij8&show_icons=true&locale=en" alt="paridhiij8" /></p>

<p><img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=paridhiij8&" alt="paridhiij8" /></p>
</body>
</html>
