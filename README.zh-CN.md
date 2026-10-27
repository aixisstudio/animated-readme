# Animated Readme

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | **中文** | [日本語](README.ja.md) | [Русский](README.ru.md)

让你的 GitHub 个人主页动起来的动画组件

_详细内容（列表、链接、描述）以英文维护 — 以下章节为你指引。_

## ✨ Make your profile move — animated README widgets

## ⌨️ Typing effect

```markdown
[![Typing](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=58A6FF&width=435&lines=Building+things+that+matter;Open+source+forever)](https://git.io/typing-svg)
```

## 🐍 Contribution snake

```yaml
# .github/workflows/snake.yml — generates an SVG snake eating your graph
- uses: Platane/snk@v3
  with:
    github_user_name: ${{ github.repository_owner }}
    outputs: dist/github-contribution-grid-snake.svg
```

```markdown
![snake](https://raw.githubusercontent.com/USER/USER/output/github-contribution-grid-snake.svg)
```

## 📊 Live stats cards

```markdown
![stats](https://github-readme-stats.vercel.app/api?username=USER&show_icons=true&theme=tokyonight)
![streak](https://streak-stats.demolab.com/?user=USER&theme=tokyonight)
![trophy](https://github-profile-trophy.vercel.app/?username=USER&theme=tokyonight)
```

## 📈 Advanced dashboards

| Service | What it draws |
|---|---|
| [lowlighter/metrics](https://github.com/lowlighter/metrics) | Full infographics — 50+ widgets |
| [git-city](https://github.com/srizzon/git-city) | Your profile as 3D pixel building |
| [waka-readme](https://github.com/athul/waka-readme) | Coding-time stats (needs WakaTime) |
| [github-readme-activity-graph](https://github.com/Ashutosh00710/github-readme-activity-graph) | Contribution line graph |

## 🎵 Fun extras

| Widget | Embed |
|---|---|
| Spotify now-playing | `spotify-github-profile.vercel.app` |
| Random dev quote | `quotes-github-readme.vercel.app` |
| Visitor counter | `komarev.com/ghpvc/?username=USER` |
| Meme of the day | `random-memer.herokuapp.com` |

> Tip: animated widgets make profiles memorable — but don't stack more than 2-3 or it becomes a slot machine.

---
## 贡献

欢迎提交 Pull Request，我们会审查并合并。由 [aixisstudio](https://github.com/aixisstudio) 维护，他也是开源应用防火墙 [Snitch](https://github.com/aixisstudio/Snitch) 的作者。

## 许可证: MIT
