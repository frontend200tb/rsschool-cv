***

# Ivan Kashirin
***

## Junior Frontend Developer
***

## Contacts
***

* Location: **Voronezh, Russia**
* Tel: **+7(951)560-29-52**
* E-mail: **frontend200tb@gmail.com**
* **[WhatsApp](https://wa.me/79507658158)**
* **[VK](https://vk.com/benchpress250)**
* **[Telegram](https://t.me/Frontend200tb)**
* **[Instagram](https://www.instagram.com/frontend200tb/)**
* **[GitHub](https://github.com/frontend200tb)**
* **[Facebook](https://www.facebook.com/frontend200tb)**
* **[Twitter](https://twitter.com/frontend200tb)**

## Summary
***

I am Junior Frontend Developer. My goal is Junior -> Middle -> Senior. Every day I am engaged in self-education. I study frontend tools and technologies that are not yet familiar to me. My hobby is the practice of foreign languages and sports. I like doing powerlifting in the gym. My best benchpress is 155kg. I have five children and I love spending time with them and watch them grow up.

## Skills
***

+ HTML
+ CSS
+ JavaScript
+ Pug
+ Sass

## Code example
***

**HTML**
```
<section class="content">
  <h1>Online radio Serbia</h1>
  <hr>
  <article class="player">
    <audio id="av-tag" src="https://mastermedia.shoutca.st/proxy/prviradions?mp=/stream" controls></audio>
    <button class="play-btn" id="play-btn"><img class="play" id="play-img" src="img/player/play.svg" alt=""></button>
```

**CSS**
```
html {
  font-size: 15px; /* 1rem */
  font-family: Arial, sans-serif;
}

@media (max-width: 576px) {
  html {
    font-size: 0.8rem;
  }
}
```

**JavaScript**
```
playBtn.addEventListener("click", (a)=> {
  if(av.classList.contains("isPlaying")) {
    av.pause();
    av.classList.remove("isPlaying");
    playImg.src = "img/player/play.svg";
  }
  else {
    playRadio()
  }
});

```

**Pug**
```
extends extends/base.pug

block main
  aside
    include includes/aside-radio.pug
    +aside-radio('Online Radio')

  section.content
    h1 Online radio Serbia
    hr
    article.player
      include includes/player/player.pug
```

## Education
***

Voronezh State Technical University

Faculty of Radio Engineering and Electronics

## Projects
***

## Courses
***

## Languages
***

- English B1
- Russian native
- Serbian native
- Bulgarian B1
- Czech B1
- ... and some more
