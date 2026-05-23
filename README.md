
<h1 align="center">Israel Sousa</h1>

###

<div align="center">
  <img src="https://skillicons.dev/icons?i=godot" height="60" alt="godot logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=ps" height="60" alt="photoshop logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=windows" height="60" alt="windows logo"  />
  <img width="12" />
  <img src="https://skillicons.dev/icons?i=py" height="60" alt="python logo"  />
  <img width="12" />
</div>

###

<div align="center">
<a href="https://steamcommunity.com/id/hayatoisr/" target="_blank" >
  <img alt="Static Badge" src="https://img.shields.io/badge/STEAM---?style=flat-square&logo=steam&color=%23035efc"
 height="30" alt="Steam logo" /></a>
<a href="https://open.spotify.com/user/5r7tgbkjvwlxoq8r3h8pyitmy" target="_blank" >
  <img alt="Static Badge" src="https://img.shields.io/badge/SPOTIFY-title-black?style=flat-square&logo=spotify&color=%23000000"
 height="30" alt="Spotigy logo" /></a>    
</div>
<script>
async function loadSpotify() {
  try {
    const res = await fetch("https://spotify-now-playing-beta-sepia.vercel.app/api/now-playing");
    const data = await res.json();

    if (!data.playing) {
      document.getElementById("title").innerText = "nada tocando";
      document.getElementById("artist").innerText = "";
      return;
    }
    document.getElementById("title").innerText = data.title;
    document.getElementById("artist").innerText = data.artist;
    document.getElementById("cover").src = data.albumImage || "";

    let w = 0;
    setInterval(() => {
      w = (w + 2) % 100;
      document.getElementById("progress").style.width = w + "%";
    }, 300);

  } catch (e) {
    document.getElementById("status").innerText = "[ error ]";
  }
}

loadSpotify();
setInterval(loadSpotify, 10000);
</script>

###





**`Desenvolvedor em Formação`**

Rapaziadinha aqui é eu o Hayato e esse aqui é meu github onde eu faço umas brinks e uns bagulho aleatorio quando to entediado


---

### 🤖 Linguagens e Tecnologias

<img 
    align="left" 
    alt="HTML"
    title="HTML" 
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/html5/html5-original.svg" 
/>
<img 
    align="left" 
    alt="CSS" 
    title="CSS"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/css3/css3-original.svg" 
/>
<img 
    align="left" 
    alt="JavaScript" 
    title="JavaScript"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/javascript/javascript-original.svg" 
/>
<img 
    align="left" 
    alt="Next.js" 
    title="Next.js"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/nextjs/nextjs-original.svg" 
/>
<img 
    align="left" 
    alt="Git" 
    title="Git"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" 
/>
<img 
    align="left" 
    alt="Python" 
    title="Python"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" 
/>
<img
    align="left" 
    alt="MySql" 
    title="MySql"
    width="30px" 
    style="padding-right: 10px;" 
    src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/mysql/mysql-plain-wordmark.svg"
/>

<br clear="left"/>

---
