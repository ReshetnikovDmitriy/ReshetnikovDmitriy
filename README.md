# Привет, меня зовут Дмитрий!

---

### :man_technologist: Обо мне:

Я начинающий веб разработчик<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30px">. Мой путь в it начался со школы Frontendblok, где я прошел курсы по HTML | CSS базовый и продвинутый. После, в этой же школе решил продолжить обучение по JS! В настоящий момент мое обучение продолжается. 

- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.ReshetnikovDmitriy }}

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

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}

- :telescope: Создал 4 учебных сайта на учебной платформе Frontendblok.

- :seedling: Завершил курсы по продвинутой вёрстке на учебной платформе Frontendblok!

- :zap: В ближайшей перспективе изучение JS и React!

- :mailbox: Как связаться со мной: [![Telegram Badge](https://img.shields.io/badge/-filimonovalexey-blue?style=flat&logo=Telegram&logoColor=white)](https://t.me/f1llzzz) [![Gmail Badge](https://img.shields.io/badge/-Gmail-red?style=flat&logo=Gmail&logoColor=white)](mailto:alexeyf08@gmail.com)
