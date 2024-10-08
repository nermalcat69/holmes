![header](https://i.imgur.com/3EIbYcO.png)

<div align="center">

<img src="https://img.shields.io/badge/go-%2300ADD8.svg?style=for-the-badge&logo=go&logoColor=white"> <img src="https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white"> <img src="https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white"> <img src="https://img.shields.io/badge/DigitalOcean-%230167ff.svg?style=for-the-badge&logo=digitalOcean&logoColor=white"> <img src="/zerops-shield.svg"> <img src="/zerops-big.svg"> <img src="/zerops-new.svg">

</div>

### Holmes
A simplistic powerful template / starter kit for making your own cryptic / scavenger hunts written completely in Golang and [templ](https://github.com/a-h/templ)

### Features
- No javascript *
- Very easy to extend
- Built in admin panel to manage users, questions and hints
- Adding images, videos and audios to questions
- Built in authentication system
- Built in rate limiting
- Built in leaderboard
- Easy to add custom routes

\* (Except for the tailwind stuff and toggling the navbar)


### Run Locally

- Clone the project

```bash
  git clone https://github.com/namishh/holmes
```

- Go to the project directory

```bash
  cd holmes
```

- Install go dependencies

```bash
  # air for live reload
  go install github.com/air-verse/air@latest
  # templ
  go install github.com/a-h/templ/cmd/templ@latest
```

- Install npm dependencies for tailwind

```bash
  npm i
```

- Start the server

```bash
  ## start templ
  make templ

  ## start tailwind watcher
  make css

  ## run the server
  make dev
```

- To build the project
```bash
  make build
```

### Demo

- User Perspective

https://github.com/user-attachments/assets/c227512b-88e7-42fb-ba78-a426bc996ccf

- Admin Perspective
  
https://github.com/user-attachments/assets/a4ef2dcd-e13e-410f-9f50-e6fe6fd2bd27



### Screenshots

- Home Page 

<img src="https://i.imgur.com/0IE0zAi.png">

- Auth Pages

<img src="https://i.imgur.com/tbKPDpP.png">
<img src="https://i.imgur.com/TSMiuCG.png">
<img src="https://i.imgur.com/uoidEFB.png">

- Admin Panel

<img src="https://i.imgur.com/48Vrz7j.png">

- All the questions

<img src="https://i.imgur.com/r4oROL4.png">

- Questions

<img src="https://i.imgur.com/08huRR2.png">
<img src="https://i.imgur.com/AQRfR9a.png">

- Hints

<img src="https://i.imgur.com/fWM2z3y.png">
<img src="https://i.imgur.com/QL5eEmC.png">

- Single Question

<img src="https://i.imgur.com/BXVcmQ1.png">
<img src="https://i.imgur.com/qShZuKT.png">

- Opened Hint 

<img src="https://i.imgur.com/mJoiwCZ.png">

- Leaderboard

<img src="https://i.imgur.com/z1awEXU.png">

- Error Pages

<img src="https://i.imgur.com/hGTiQWn.png">
<img src="blob:https://imgur.com/6d1faf60-631a-43c5-87ca-733338f6ef76">

### Todo
- [x] Setup the project
- [x] Auth
  - [x] Login and Register
  - [x] Logout
- [x] Admin
  - [x] Delete User
  - [x] Add Question
  - [x] Delete Question
  - [x] Edit Question
    - [x] Edit Details
    - [x] Edit Media
  - [x] Hints
    - [x] Add hint
    - [x] Delete hint
- [x] Game flow
  - [x] Get all questions
  - [x] Get Question
  - [x] Submit Answer
  - [x] Update Score
  - [x] Get Hint
  - [x] End Game
- [x] Leaderboard
- [x] Error Pages
- [x] Rate limiting

### Future
- [ ] Host on digital ocean

### Acknowledgements

-  [emarifer/go-echo-templ-htmx](https://github.com/emarifer/go-echo-templ-htmx)
