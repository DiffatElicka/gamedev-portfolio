<template>
  <div style="margin-bottom: 80px;">
    <h1>Portfolio</h1>

    <div class="paragraph">
      <div>
        I'm <strong>Chenyu Wang</strong>, a Master's student at Northwestern University.<br/>
      </div>

      <div style="margin-top: 40px;">I'm currently seeking a PhD to study game AI.</div>
    </div>

    <div class="photo">
      <img src="img/avatar.jpg" alt="My Avatar" />
    </div>

    <div style="clear:both"></div>

    <div>
      <h1>Projects</h1>

      <!-- EaWCN Project -->
      <div class="project">
        <h2>Equestria at War CN (EaWCN) 2018-2021</h2>
        <img src="img/EaWCN.jpg" alt="EaWCN Project" />
        <p>
          A localization project for the popular Hearts of Iron IV mod <em>Equestria at War</em>. 
          Led a team of over 60 members, managed community moderation, and created a dedicated wiki with 65 articles and 2,440 edits. 
          Released on Steam Workshop, achieving over 28,000 subscriptions and a 98% positive rating from 865 reviews.
        </p>
        <a href="https://steamcommunity.com/sharedfiles/filedetails/?id=1728628604" target="_blank">View Project on Steam Workshop</a>
      </div>

      <!-- Remnant of Stars Project -->
      <div class="project">
        <h2>Remnant of Stars</h2>
        <img src="img/ros.png" alt="Remnant of Stars Project" />
        <p>
          A Civilization-like turn-based strategy game developed in Unity. Designed core systems including combat, economy, building, and research, 
          along with a dynamic difficulty scaling AI. Created a hexagonal map framework, including fog of war, A* pathfinding, and a map editor. 
          Conducted weekly playtests and wrote over 5,000 words of in-game lore and texts.
        </p>
        <a href="https://youtu.be/eW0p0vyBmQg" target="_blank">Watch Demo Video</a>
      </div>

      <!-- <div style="margin-top: 50px;">
        <h1>Resume</h1>
        <a href="Chenyu_Wang_Resume.pdf" target="_blank">Download My Resume</a>
      </div> -->
    </div>
  </div>
</template>

<style scoped>
.paragraph {
  max-width: 700px;
  margin-bottom: 20px;
}

.photo {
  margin-top: 50px;
  text-align: center;
}

.photo img {
  width: 300px; /* Set the width, height adjusts automatically */
  height: auto; /* Ensures the aspect ratio is maintained */
}

.project {
  margin-top: 40px;
}

.project img {
  width: 100%;
  max-width: 400px;
  margin: 20px 0;
}

.project p {
  max-width: 700px;
}

@media only screen and (min-width: 620px){
  .paragraph {
    float: left;
  }

  .photo {
    float: left;
    padding: 10px;
    padding-left: 80px;
  }
}
</style>
