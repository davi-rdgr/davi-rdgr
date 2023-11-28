Olá, me chamo **Davi Rodeghiero**!

- 👨🏻‍💻 Curso Análise e Desenvolvimento de Sistemas.
- ✏️ Focado em Desenvolvimento Web.

- 🖥️ Experiência com:

<div style="display: inline">
          <img width="40px" height="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" />        
          <img width="40px" height="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" />
          <img width="40px" height="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" />
          <img width="40px" height="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/figma/figma-original.svg" />
          <img width="40px" height="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" />
          <img width="40px" height="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" />
          <img width="40px" height="40px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" />
</div> 
<br>
- 📱 Redes Sociais:
<br>
<br>

<a href="https://www.linkedin.com/in/davi-souza-317496242/">
<img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white"></a>&nbsp;&nbsp;
<a href="https://www.instagram.com/davirodeghiero/">
<img src="https://img.shields.io/badge/Instagram-%23E4405F.svg?style=for-the-badge&logo=Instagram&logoColor=white"></a>&nbsp;

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ https://github.com/davi-rdgr?tab=overview&from=2023-11-01&to=2023-11-28 }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9
