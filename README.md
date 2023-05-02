<h1 align="center">Hi 👋, I'm Trideep kumar</h1>
<h3 align="center">Self taught MERN developer ...</h3>



<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://getbootstrap.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/bootstrap/bootstrap-plain-wordmark.svg" alt="bootstrap" width="40" height="40"/> </a> <a href="https://www.w3schools.com/css/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a> <a href="https://expressjs.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/express/express-original-wordmark.svg" alt="express" width="40" height="40"/> </a> <a href="https://www.figma.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/figma/figma-icon.svg" alt="figma" width="40" height="40"/> </a> <a href="https://firebase.google.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/firebase/firebase-icon.svg" alt="firebase" width="40" height="40"/> </a> <a href="https://git-scm.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/git-scm/git-scm-icon.svg" alt="git" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> <a href="https://www.mongodb.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mongodb/mongodb-original-wordmark.svg" alt="mongodb" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.nginx.com" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nginx/nginx-original.svg" alt="nginx" width="40" height="40"/> </a> <a href="https://nodejs.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original-wordmark.svg" alt="nodejs" width="40" height="40"/> </a> <a href="https://www.photoshop.com/en" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/photoshop/photoshop-line.svg" alt="photoshop" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://reactjs.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original-wordmark.svg" alt="react" width="40" height="40"/> </a> </p>

var icons = [
  {
    icon: "fa fa-bootstrap fa-4x",
    title: "Bootstrap",
    color: "black"
  },
  {
    icon: "fa fa-css3 fa-4x",
    title: "CSS3",
    color: "black"
  },
  {
    icon: "fa fa-express fa-4x",
    title: "Express",
    color: "white"
  },
  {
    icon: "fa fa-figma fa-4x",
    title: "Figma",
    color: "black"
  },
  {
    icon: "fa fa-firebase fa-4x",
    title: "Firebase",
    color: "black"
  },
  {
    icon: "fa fa-git fa-4x",
    title: "Git",
    color: "black"
  },
  {
    icon: "fa fa-html5 fa-4x",
    title: "HTML5",
    color: "black"
  },
  {
    icon: "fa fa-js fa-4x",
    title: "JavaScript",
    color: "black"
  },
  {
    icon: "fa fa-mongodb fa-4x",
    title: "MongoDB",
    color: "black"
  },
  {
    icon: "fa fa-mysql fa-4x",
    title: "MySQL",
    color: "black"
  },
  {
    icon: "fa fa-nginx fa-4x",
    title: "Nginx",
    color: "black"
  },
  {
    icon: "fa fa-nodejs fa-4x",
    title: "Node.js",
    color: "black"
  },
  {
    icon: "fa fa-photoshop fa-4x",
    title: "Photoshop",
    color: "black"
  },
  {
    icon: "fa fa-postgresql fa-4x",
    title: "PostgreSQL",
    color: "black"
  },
  {
    icon: "fa fa-react fa-4x",
    title: "React",
    color: "black"
  }
];

for (var i = 0; i < icons.length; i++) {
  if (icons[i].title === "Express") {
    icons[i].color = "white";
  }
}

// Render the icons
var iconList = document.getElementById("icon-list");
for (var i = 0; i < icons.length; i++) {
  var icon = document.createElement("i");
  icon.className = "fa " + icons[i].icon;
  icon.title = icons[i].title;
  icon.style.color = icons[i].color;
  iconList.appendChild(icon);
}```


