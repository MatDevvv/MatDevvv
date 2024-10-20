<h1 align="center">
<img src="https://readme-typing-svg.herokuapp.com/?font=Righteous&size=35&center=true&vCenter=true&width=500&height=70&duration=4000&lines=olá!+👋;+me+chamo+Mateus!;" />
</h1>

<p align="center">
  <strong>Desenvolvedor Full Stack</strong> <br>
  Especializado em soluções web, criação de APIs, manutenção e monitoramento de sistemas.
</p>

---

### Conecte-se comigo

<p align="center">
  <a href="mailto:matttdev@outlook.com">
    <img src="https://img.shields.io/badge/-Email-E94D5F?style=for-the-badge&logo=microsoft-outlook&logoColor=white" height="35">
  </a>
  <a href="https://www.linkedin.com/in/matttdev/">
    <img src="https://img.shields.io/badge/-LinkedIn-30A3DC?style=for-the-badge&logo=linkedin&logoColor=white" height="35">
  </a>
  <a href="https://discord.com/users/mt_ninja">
    <img src="https://img.shields.io/badge/-Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" height="35">
  </a>
</p>

---

### 🚀 Minhas Habilidades

<p align="left" style="display: flex; flex-wrap: wrap; gap: 10px;">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" height="60" title="JavaScript">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" height="60" title="TypeScript">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" height="60" title="HTML5">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" height="60" title="CSS3">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" height="60" title="React">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" height="60" title="Node.js">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/adonisjs/adonisjs-original.svg" alt="AdonisJS" height="60" title="AdonisJS">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" alt="MySQL" height="60" title="MySQL">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/sass/sass-original.svg" alt="SCSS" height="60" title="SCSS">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tailwindcss/tailwindcss-original.svg" alt="Tailwind CSS" height="60" title="Tailwind CSS">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" height="60" title="Git">
</p>

---

### 📊 Estatísticas do GitHub

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=MatDevvv&theme=transparent&bg_color=000&border_color=30A3DC&show_icons=true&icon_color=30A3DC&title_color=E94D5F&text_color=FFF" alt="GitHub Stats">
  <br>
  <img src="https://github-readme-stats-git-masterrstaa-rickstaa.vercel.app/api/top-langs/?username=MatDevvv&layout=compact&bg_color=000&border_color=30A3DC&title_color=E94D5F&text_color=FFF" alt="Top Langs">
</p>



✨ _"Aprendizado constante é o caminho para a evolução."_ ✨
# Steps represent a sequence of tasks that will be executed as part of the job
steps:

# Checks repo under $GITHUB_WORKSHOP, so your job can access it
  - uses: actions/checkout@v2

# Generates the snake  
  - uses: Platane/snk@master
    id: snake-gif
    with:
      github_user_name: MatDevvv
      # these next 2 lines generate the files on a branch called "output". This keeps the main branch from cluttering up.
      gif_out_path: dist/github-contribution-grid-snake.gif
      svg_out_path: dist/github-contribution-grid-snake.svg

 # show the status of the build. Makes it easier for debugging (if there's any issues).
  - run: git status

  # Push the changes
  - name: Push changes
    uses: ad-m/github-push-action@master
    with:
      github_token: ${{ secrets.GITHUB_TOKEN }}
      branch: master
      force: true

  - uses: crazy-max/ghaction-github-pages@v2.1.3
    with:
      # the output branch we mentioned above
      target_branch: output
      build_dir: dist
    env:
      GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
