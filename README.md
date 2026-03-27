# 💌 Interactive Birthday / Love Letter Website

A cute multi-screen interactive website built with vanilla HTML, CSS, and JavaScript.
Inspired by those adorable "do you wanna see something?" pages — with animated characters,
a running NO button, confetti, and a personal love letter reveal.

## Live Demo
[View it here](https://be-my-valentinee-my.netlify.app/)

## Preview
<!-- Drop a screenshot of your site here after uploading to GitHub -->

## Features
- 7 animated screens with smooth transitions
- NO button that **runs away** from your cursor (and shrinks each time 😤)
- Confetti + star burst explosion on YES
- Personal wish/letter screen
- Heart-shaped photo frame
- Floating hearts background
- Fully mobile responsive

## Built With
- HTML5
- CSS3 (keyframe animations, clip-path, CSS variables)
- Vanilla JavaScript (no frameworks, no libraries)

## Project Structure
```
index.html   ← everything lives here (single file app)
```

## Customisation
| What | Where in the file |
|---|---|
| Wish/letter text | `#screen-wish` section |
| Your photo | Replace the SVG placeholder in `#screen-final` with an `<img>` tag |
| Date | `#dateStamp` (auto-fills today, or hardcode yours) |
| Character emojis | Search for 🐼 and 🐻 and swap them |
| Colors | CSS variables at the top of `<style>` |

## What I Learned
- CSS keyframe animations and transitions
- DOM manipulation with vanilla JavaScript
- Multi-screen navigation without a router
- Deploying a static site with Netlify

---
*Made with 💕 as a personal project*
