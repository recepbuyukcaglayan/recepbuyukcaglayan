Hi ![](https://user-images.githubusercontent.com/18350557/176309783-0785949b-9127-417c-8b55-ab5a4333674e.gif)My name is Recep Büyükçağlayan
===========================================================================================================================================

Management İnformation System || AI Engineer
--------------------------------------------

Hello, I'm Recep. I am a senior student at the Department of Management Information Systems. I am developing myself in the field of artificial intelligence and machine learning. I also deal with cyber security and ethical hacking.

* 🌍  I'm based in Turkey
* ✉️  You can contact me at [rbuyukcaglayan@gmail.com](mailto:rbuyukcaglayan@gmail.com)
* 🚀  I'm currently working on [Machine Learning](http://github.com/recepbuyukcaglayan/Machine-Learning)
* 🧠  I'm learning Deep Learning
* ⚡  I'm a relentless cybersecurity expert who stops hackers at night. Just like batman but I'm sitting at the computer. 😅

### Skills
<link href="https://fonts.googleapis.com/css?family=Montserrat:900" rel="stylesheet">

<p class="rock">RECEP</p>
<div class="hand">
  <div class="palm">
    <div class="bone"></div>
    <div class="palm-shadow"></div>
  </div>
  <div class="thumb-base"></div>
  <div class="mobile-shadow"></div>
  <div class="mobile">
    <div class="screensaver"></div>
  </div>
  <div class="finger-5 finger">
    <div class="finger-shadow"></div>
  </div>
  <div class="finger-4 finger">
    <div class="fingernail"></div>
  </div>
  <div class="finger-3 finger">
    <div class="fingernail"></div>
  </div>
  <div class="finger-2 finger">
    <div class="finger-shadow"></div>
  </div>
  <div class="finger-1 finger">
    <div class="fingernail"></div>
  </div>
</div>

$cream: #FEDCCA;

* {
  box-sizing: border-box;
}

body {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  overflow: hidden;
  background: #EB4F5C;
}

// Background text

.rock {
  font-family: 'Montserrat', sans-serif;
  font-size: 200px;
  margin: 0;
  color: #D4304B;
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
}

.hand {
  position: relative;
  width: 100px;
  height: 100px;
  animation: rockit .8s ease infinite alternate;
}

.palm {
  width: 125px;
  height: 140px;
  background: $cream;
  transform: rotate(26deg);
  box-shadow: inset 0 0 50px #E77F7B;
  
  &:after {
    content: '';
    background: #F2ADA1;
    width: 20px;
    height: 30px;
    border-radius: 0 0 0 100% / 50%;
    position: absolute;
    left: -20px;
    bottom: 25px;
    z-index: 5;
  }
  
  &:before {
    content: '';
    background-image: linear-gradient(-180deg, #E56C4C 0, #F68E60 100%);
    width: 100%;
    height: 30px;
    border-radius: 50%;
    position: absolute;
    left: 0;
    bottom: -15px;
  }
}

.mobile {
  width: 260px;
  height: 135px;
  background: #FC617E;
  border: 4px solid #705674;
  border-width: 4px 10px 4px 10px;
  border-radius: 20px;
  position: absolute;
  top: -80px;
  left: 80%;
  transform: rotate(-5deg) translatex(-50%);
  z-index: 1;
  overflow: hidden;
}

.screensaver {
  width: 30px;
  height: 30px;
  background: transparent;
  border-radius: 50%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  box-shadow: 
    0 0 0 30px #eee,
    0 0 0 50px #D36868,
    0 0 0 70px #71D368,
    0 0 0 100px #68CFD3;
  animation: screensaver .5s linear infinite;
}

.mobile-shadow {
  width: 100px;
  height: 50px;
  background: #C7656C;
  position: absolute;
  bottom: 30px;
  left: 50%;
  transform: rotate(-5deg) translatex(-40%);
  filter: blur(10px);
}

.finger {
  position: absolute;
  width: 45px;
  background: $cream;
  border-radius: 22px;
  box-shadow: inset 11px -17px 40px #E77F7B;
}

.finger-shadow {
  width: 35px;
  height: 50px;
  background: #C7656C;
  position: absolute;
  bottom: 5px;
  left: 50%;
  transform: translatex(-50%);
  filter: blur(10px);
}

.finger-5 {
  height: 115px;
  top: -130px;
  left: -15px;
  transform: rotate(2deg);
}

.finger-4 {
  height: 90px;
  top: -100px;
  left: 30px;
  transform: rotate(-8deg);
  z-index: 1;
}

.finger-3 {
  height: 105px;
  top: -105px;
  left: 75px;
  transform: rotate(-8deg);
  z-index: 1;
}

.finger-2 {
  height: 120px;
  top: -165px;
  left: 120px;
  transform: rotate(15deg);
  
  .finger-shadow {
    bottom: -5px;
  }
}

.finger-1 {
  height: 100px;
  top: -10px;
  right: -50px;
  transform: rotate(-65deg);
  z-index: 1;
  
  .fingernail {
    top: 10px;
    bottom: auto;
    transform: translatex(-50%) scale(-1);
  }
}

.thumb-base {
  background-image: linear-gradient(-125deg, #E97E79 42%, #FDD8C7 77%);
  width: 42px;
  height: 85px;
  border-radius: 17px 20px 0 79px;
  position: absolute;
  top: 26px;
  right: -51px;
  transform: rotate(50deg);
}

.bone {
  width: 30px;
  height: 50px;
  border-radius: 50% 50% 0 0 / 20% 20% 0 0;
  background: #F5E5E9;
  position: absolute;
  bottom: -50px;
  left: 50%;
  z-index: 1;
  transform: translatex(-50%);

  // Hand bone bottom circles
  
  &:after,
  &:before {
    content: '';
    width: 40px;
    height: 40px;
    border-radius: 50%;
    background: #F5E5E9;
    box-shadow: inset 0 -5px 5px #ECD6DA;
    position: absolute;
    bottom: -20px;
  }

  &:after {
    left: -20px;
  }

  &:before {
    right: -20px;
  }
}

.fingernail {  
  width: 30px;
  height: 25px;
  background: rgba(#FDFDFD, .3);
  box-shadow: 1px 1px #E5BAA7;
  border-radius: 0 0 50% 50%;
  position: absolute;
  bottom: 10px;
  left: 50%;
  transform: translatex(-50%);
}

.palm-shadow {
  width: 20px;
  height: 70px;
  background: #C7656C;
  position: absolute;
  bottom: 50px;
  left: 50%;
  transform: translatex(-50%);
  filter: blur(10px);
}

@keyframes rockit {
  from { transform: translatey(30px) rotate(-45deg); }
  to { transform: translatey(30px) rotate(10deg); }
}

@keyframes screensaver {
  to {
    box-shadow: 
      0 0 0 80px #eee,
      0 0 0 120px #D36868,
      0 0 0 200px #71D368,
      0 0 0 250px #68CFD3;
  }
}

<p align="left">
<a href="https://docs.microsoft.com/en-us/dotnet/csharp/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/csharp-colored.svg" width="36" height="36" alt="C#" /></a>
<a href="https://docs.microsoft.com/en-us/cpp/?view=msvc-170" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/c-colored.svg" width="36" height="36" alt="C" /></a>
<a href="https://www.oracle.com/java/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/java-colored.svg" width="36" height="36" alt="Java" /></a>
<a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/javascript-colored.svg" width="36" height="36" alt="JavaScript" /></a>
<a href="https://www.php.net/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/php-colored.svg" width="36" height="36" alt="PHP" /></a>
<a href="https://www.python.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/python-colored.svg" width="36" height="36" alt="Python" /></a>
<a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/html5-colored.svg" width="36" height="36" alt="HTML5" /></a>
<a href="https://www.w3.org/TR/CSS/#css" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/css3-colored.svg" width="36" height="36" alt="CSS3" /></a>
<a href="https://nodejs.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/nodejs-colored.svg" width="36" height="36" alt="NodeJS" /></a>
<a href="https://www.oracle.com/uk/index.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/oracle-colored.svg" width="36" height="36" alt="Oracle" /></a>
<a href="https://www.postgresql.org/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/postgresql-colored.svg" width="36" height="36" alt="PostgreSQL" /></a>
<a href="https://dotnet.microsoft.com/en-us/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/dot-net-colored.svg" width="36" height="36" alt=".NET" /></a>
<a href="https://www.adobe.com/uk/products/photoshop.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/photoshop-colored.svg" width="36" height="36" alt="Photoshop" /></a>
<a href="adobe.com/uk/products/illustrator.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/illustrator-colored.svg" width="36" height="36" alt="Illustrator" /></a>
<a href="https://www.adobe.com/uk/products/aftereffects.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/aftereffects-colored.svg" width="36" height="36" alt="After Effects" /></a>
<a href="https://www.adobe.com/uk/products/premiere.html" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/premierepro-colored.svg" width="36" height="36" alt="Premiere Pro" /></a>
<a href="https://www.figma.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/figma-colored.svg" width="36" height="36" alt="Figma" /></a>
<a href="https://www.sketch.com/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/sketch-colored.svg" width="36" height="36" alt="Sketch" /></a>
<a href="https://metamask.io/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/metamask-colored.svg" width="36" height="36" alt="MetaMask" /></a>
<a href="https://chain.link/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/chainlink-colored.svg" width="36" height="36" alt="Chainlink" /></a>
<a href="https://ethereum.org/en/" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/ethereum-colored.svg" width="36" height="36" alt="Ethereum" /></a>
<a href="https://web3js.readthedocs.io/en/v1.7.1/#" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/skills/web3js-colored.svg" width="36" height="36" alt="Web3Js" /></a>
</p>


### Socials

<p align="left"> <a href="https://www.github.com/recepbuyukcaglayan" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" /></a> <a href="https://www.twitter.com/rbuyukcaglayan" target="_blank" rel="noreferrer"><img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/twitter.svg" width="32" height="32" /></a></p>

### Support Me

<a href="https://www.buymeacoffee.com/rbuyukcaglayan"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" width="200" /></a>
