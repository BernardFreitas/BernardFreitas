## 👋 Olá, eu sou o Bernard!

- 🎓 Atualmente estou cursando a faculdade de engenharia de software
  
- 💻 Estudando e praticando com as tecnologias:
- 🐍 Python
- 🛠️ Git/GitHub
- 🧠 SQL
  
- 🚀 Estou focado em:
- Criar pequenos projetos em Python
- Aprofundar conhecimentos em banco de dados
- Melhorar o domínio do Git
  
- 🌱 Curiosidades:
- Tenho interese por análise de dados, IA e machine learning

- <div>

  <a href="https://github.com/BernardFreitas">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=BernardFreitas&show_icons=true&theme=dark&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=BernardFreitas&layout=compact&langs_count=16&theme=dark"/>
  </div>

  <div style="display: inline_block"><br>
  <img align="center" alt="Bernard-Python" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg">  
  <img align="center" alt="Bernard-Python" height="30" width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/azuresqldatabase/azuresqldatabase-original.svg">       
  </div>

  ##

  <div>
     <a href="https://www.linkedin.com/in/bernard-freitas-8324b0378/" target="_blank"><img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white" target="_blank"></a> 
  </div>

![Snake animation](https://github.com/BernardFreitas/BernardFreitas/blob/output/github-contribution-grid-snake.svg)
  
  <div>
 
    name: Generate Datas

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update datas
    runs-on: ubuntu-latest
    steps:
      # Snake Animation
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: rafaballerini
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
        
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
  </div>
  
  
  




