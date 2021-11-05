<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Dosis:wght@400;600;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/devicons/devicon@v2.14.0/devicon.min.css">

<style type='text/css'>
  :root {
  --font-family: 'Dosis', sans-serif;
  --fw-regular: 400;
  --fw-medium: 600;
  --fw-bold: 700;
  --fs-h1: 2.4rem;
  --fs-h2: 1.8rem;
  --fs-h3: 1.3rem;
  --fs-text: 1rem;

  --title-color: #c2c9d1;
  --text-color: #98a6b4;
  --bk-color: #1d252c;
}

* {
  padding: 0;
  margin: 0;
}

body {
  font-size: var(--fs-text);
  font-family: 'Dosis', sans-serif;
  color: #98a6b4;
}

h1 {
  font-weight: var(--fw-bold);
  font-size: var(--fs-h1);
  text-transform: uppercase;
  text-align: center;
  color: var(--title-color);
}

h2 {
  font-weight: var(--fw-medium);
  font-size: var(--fs-h2);
  margin: 2rem 0;
  color: var(--title-color);
}

h3 {
  font-weight: var(--fw-medium);
  font-size: var(--fs-h3);
  color: var(--title-color);
}

.margin {
  margin: 1rem 0;
}

.cotent {
  background-color: var(--bk-color);
}

.hero {
  padding: 3rem;
  width: 100%;
  height: 20rem;
  display: flex;
  justify-content: center;
  align-items: center;
  background: url(./images//hero.gif) no-repeat left;
}

.container {
  display: flex;
  flex-direction: column;
  gap: 1.2rem;
}

.card {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(7rem, auto));
  gap: 2rem;
  place-content: start;
}

.card__image {
  width: 2.5rem;
  justify-content: start;
  align-self: start;
}

.card__link {
  color: var(--text-color);
}

.img-size {
  height: 3rem;
}

.card .discord {
  max-width: 3.2rem;
}

.status-container {
  display: flex;
  flex-direction: column;
  place-content: start;
  gap: 1rem;
}

.status-container__image {
  max-width: 30rem;
}

</style>


<div class="content">

<div class="hero">
<h1 align="center" class="margin">Hi I'm Joel, a front end developer from Perú </h1>
</div>


<h2>Connect with me:</h2>

<div class="container margin">

  <div class="card">
    <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" alt="linkedin link"/>
    <a class="card__link" href="https://linkedin.com/in/joel-angel-ocaño-ore-9a52b5202" target="blank"><p><strong>Link : </strong>Linkedin</p></a>
  </div>

  <div class="card">
    <img class="card__image discord" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" alt="discord link"/>
    <p><strong>Id : </strong>Ryuse#0525</p>
  </div>

  <div class="card">
    <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/slack/slack-original.svg" alt="slack link"/>
    <a class="card__link" href="#" target="blank">Slack ..</a>
  </div>

</div>

<h2>Tools and Languages</h2>

<h3> Design</h3>

<div class="container margin">

  <div class="card">
    <svg class="card__image img-size" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 48 48" ><path d="M0 0h48v48H0z" fill="#ffd02f"/><path d="M32.708 6.4h-5.124l4.549 7.05-9.617-7.05h-5.124l4.549 9.238L12.324 6.4H7.2l4.474 11.926L7.2 41.6h5.124l9.617-24.955L17.392 41.6h5.124l9.617-27.142-4.549 27.142h5.124L42.4 11.785z" fill="#050038"/></svg>
    <p><strong>Miro :</strong> To make wireframes</p>
  </div>

  <div class="card">
    <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" />
    <p><strong>Figma :</strong> To Design the interfaces</p>
  </div>

  <div class="card">
   <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/photoshop/photoshop-line.svg" />
    <p><strong>Photoshop :</strong>To make adjustments and reduce the weight of the images.</p>
  </div>

</div>

<h3>Front end</h3>

<div class="container margin">

  <div class="card">
    <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-plain.svg" />
   </div>

  <div class="card">
    <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-plain.svg" />
    <img class="card__image"  src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" />
    <img class="card__image img-size" src="./images/styled-components-icon.png">
    <img  class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bootstrap/bootstrap-original.svg" />
  </div>

  <div class="card">
    <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" />
    <img class="card__image" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" />
  </div>
</div>

</div>

<div>
</div>


<div class="status-container margin">

  <img class="status-container__image" src="https://github-readme-stats.anuraghazra1.vercel.app/api?username=Ryusse&show_icons=true&include_all_commits=true&theme=gotham" alt="Ryusse's github stats" />
  <img class="status-container__image" src="https://github-readme-stats.anuraghazra1.vercel.app/api/top-langs/?username=Ryusse&layout=compact&theme=gotham" />

</div>
</div>