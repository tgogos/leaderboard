# leaderboard

 - Made with ❤️ for friends who were trying to motivate their classes 🧑‍🏫 during COVID-19 lockdowns.
 - Use it together with `leaderboard-cards` for more competition & fun!
 - Try them both online at:
   - [gogos.me/leaderboard/](https://gogos.me/leaderboard/)
   - [gogos.me/leaderboard-cards/](https://gogos.me/leaderboard-cards/)
   - alternative codepen links: [leaderboard](https://codepen.io/tgogos/full/qBaEJaa) / [leaderboard-cards](https://codepen.io/tgogos/full/jOMrvmg)

![overview](/README/overview.gif)

✔️ create a class leaderboard by adding names / scores in a few seconds  
✔️ change the score by adding or removing points with the appropriate buttons  
✔️ see the live updates as the players compete and level-up  
✔️ changes are stored to your browser's `local storage`  

# leaderboard-cards

![how to use cards](/README/cards.gif)

✔️ add lucky cards that give extra points (or the opposite)  
✔️ they are randomly placed whenever you refresh the page  
✔️ press the button to shuffle them a little bit  
✔️ when you think its needed, ask the user to pick one card  

<br>
<br>
<br>

# Instructions 

## ❔ How to add new names

Use the <kbd>➕</kbd> button and a random animal emoji will be selected, then type the name / score and hit <kbd>OK</kbd>

![how to add new names](/README/add_names.gif)

### 👉 use every emoji you like

There is a predefined list of animals that are randomly chosen whenever you add a new name:

```
🐶 🐱 🐭 🐹 🐰 🦊 🐻 🐼 🐨 🐯 🦁 🐮 🐷 🐽 🐸 🐵 🙈 🙉 🙊 🐒 🐔 🐧 🐦 🐤 🐣 🐥 🦆 🦅 🦉 🦇 🐺 🐗 🐴 🦄 🐝 🐛
🦋 🐌 🐞 🐜 🦟 🦗 🕷 🕸 🦂 🐢 🐍 🦎 🦖 🦕 🐙 🦑 🦐 🦞 🦀 🐡 🐠 🐟 🐬 🐳 🐋 🦈 🐊 🐅 🐆 🦓 🦍 🦧 🐘 🦛 🦏 🐪
🐫 🦒 🦘 🐃 🐂 🐄 🐎 🐖 🐏 🐑 🦙 🐐 🦌 🐕 🐩 🦮 🐕‍🦺 🐈 🐓 🦃 🦚 🦜 🦢 🦩 🐇 🦝 🦨 🦡 🦦 🦥 🐁 🐀 🦔
```

but you can use whatever emoji you prefer by just typing it:

![how to use custom emoji](/README/custom_emoji.gif)



## ❔ How to add many, edit, delete...

Use the <kbd>📋</kbd> button and add, edit or delete lines from the text-area that is poped-up. Make sure that that every line has 3 comma-separated entries of the following format `<emoji>,<nickname>,<score>` for example:

```
🐒,Green Monkey,14
🦎,Orange Iguana,13
🦜,Purple Parrot,12
🐟,Blue Barracuda,10
🐆,Red Jaguar,9
🐍,Silver Snake,8
```

![how to add many names, edit & delete](/README/add-many_edit_delete.gif)


## ❔ How to share

Use the <kbd>🔗</kbd> button, copy the link created and share it. The current state of your leaderboard will be stored in that looooong `url` and at the time a user pastes it to a browser, the data are moved to the local storage and the url becomes short again. Example:

```
https://gogos.me/leaderboard/?q=JTVCJTdCJTIyaWNvbiUyMiUzQSUyMiVGMCU5RiU5MCU5MiUyMiUyQyUyMm5pY2tuYW1lJTIyJTNBJTIyR3JlZW4lMjBNb25rZXklMjIlMkMlMjJzY29yZSUyMiUzQSUyMjE0JTIyJTdEJTJDJTdCJTIyaWNvbiUyMiUzQSUyMiVGMCU5RiVBNiU4RSUyMiUyQyUyMm5pY2tuYW1lJTIyJTNBJTIyT3JhbmdlJTIwSWd1YW5hJTIyJTJDJTIyc2NvcmUlMjIlM0ElMjIxMyUyMiU3RCUyQyU3QiUyMmljb24lMjIlM0ElMjIlRjAlOUYlQTYlOUMlMjIlMkMlMjJuaWNrbmFtZSUyMiUzQSUyMlB1cnBsZSUyMFBhcnJvdCUyMiUyQyUyMnNjb3JlJTIyJTNBJTIyMTIlMjIlN0QlMkMlN0IlMjJpY29uJTIyJTNBJTIyJUYwJTlGJTkwJTlGJTIyJTJDJTIybmlja25hbWUlMjIlM0ElMjJCbHVlJTIwQmFycmFjdWRhJTIyJTJDJTIyc2NvcmUlMjIlM0ElMjIxMCUyMiU3RCUyQyU3QiUyMmljb24lMjIlM0ElMjIlRjAlOUYlOTAlODYlMjIlMkMlMjJuaWNrbmFtZSUyMiUzQSUyMlJlZCUyMEphZ3VhciUyMiUyQyUyMnNjb3JlJTIyJTNBJTIyOSUyMiU3RCUyQyU3QiUyMmljb24lMjIlM0ElMjIlRjAlOUYlOTAlOEQlMjIlMkMlMjJuaWNrbmFtZSUyMiUzQSUyMlNpbHZlciUyMFNuYWtlJTIyJTJDJTIyc2NvcmUlMjIlM0ElMjI4JTIyJTdEJTVE
```

# Libraries used

 - jQuery: [jquery.com](https://jquery.com/)
 - isotope.js: [isotope.metafizzy.co](https://isotope.metafizzy.co/)
