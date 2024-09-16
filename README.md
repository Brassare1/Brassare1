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
          github_user_name: Brassare1
          svg_out_path: dist/github-contribution-grid-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}


<img width=100% src="https://capsule-render.vercel.app/api?type=waving&color=1E90FF&height=120&section=header"/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com/?color=1E90FF&size=35&center=true&vCenter=true&width=1000&lines=HELLO,+My+name+is+Rafael+Brassare;I'm+27+years+old;I'm+from+Brazil;Student+of+Data+Scientist+in+EBAC;Be+Welcome!+:%29)](https://git.io/typing-svg)


### Main skills: ![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)&nbsp; ![SQL](https://img.shields.io/badge/-SQL-0D1117?style=for-the-badge&logo=sql&labelColor=0D1117)&nbsp;


&nbsp;<div align="center">
  [![Spotify](https://novatorem.vercel.app/api/spotify?background_color=0d1117&border_color=ffffff)](https://open.spotify.com/intl-pt/track/4J8JsvGToawvjyVL482UqH?si=a62b05e34ee64d26)
</div>
