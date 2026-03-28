* {  
    margin: 0;  
    padding: 0;  
    box-sizing: border-box;  
    font-family: Arial, sans-serif;  
}  
  
body {  
    background: #ffffff;  
    color: #1a1a1a;  
}  
  
/* NAVBAR */  
nav {  
    display: flex;  
    justify-content: space-between;  
    padding: 20px 10%;  
    background: white;  
    position: fixed;  
    width: 100%;  
    top: 0;  
}  
  
.logo {  
    color: #0a7f3f;  
}  
  
nav ul {  
    display: flex;  
    gap: 20px;  
    list-style: none;  
}  
  
nav a {  
    text-decoration: none;  
    color: black;  
    transition: 0.3s;  
}  
  
nav a:hover {  
    color: #0a7f3f;  
}  
  
/* HERO */  
.hero {  
    height: 100vh;  
    display: flex;  
    align-items: center;  
    justify-content: center;  
    background: linear-gradient(to right, #0a7f3f, #2ecc71);  
    color: white;  
    text-align: center;  
}  
  
.hero span {  
    color: #d4ffd4;  
}  
  
.btn {  
    display: inline-block;  
    margin-top: 20px;  
    padding: 10px 20px;  
    background: white;  
    color: #0a7f3f;  
    border-radius: 5px;  
    transition: 0.3s;  
}  
  
.btn:hover {  
    transform: scale(1.1);  
}  
  
/* SECTIONS */  
.section {  
    padding: 100px 10%;  
    text-align: center;  
}  
  
/* CARDS */  
.card {  
    margin-top: 20px;  
    padding: 20px;  
    border: 1px solid #ddd;  
    border-radius: 10px;  
    transition: 0.3s;  
}  
  
.card:hover {  
    transform: translateY(-10px);  
    box-shadow: 0px 5px 15px rgba(0,0,0,0.1);  
}  
  
/* SUBTEXT */  
.sub {  
    margin-top: 10px;  
    font-size: 1.1rem;  
    opacity: 0.9;  
}  
  
/* SKILLS */  
.skills-container {  
    display: flex;  
    flex-wrap: wrap;  
    justify-content: center;  
    gap: 15px;  
    margin-top: 20px;  
}  
  
.skill {  
    padding: 10px 15px;  
    border: 2px solid #0a7f3f;  
    border-radius: 20px;  
    transition: 0.3s;  
}  
  
.skill:hover {  
    background: #0a7f3f;  
    color: white;  
    transform: scale(1.1);  
}  
  
/* LISTS IN PROJECTS */  
.card ul {  
    text-align: left;  
    margin-top: 10px;  
}  
