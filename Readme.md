<p align="center">
  <img src=".github/Logo-svg.svg" alt="Happy" />
</p>

<p align="center">
  <b>Connect people to orphanages and bring good news to the childrens</b>
</p>

<br />


## 📕 About

<b>Happy</b> is a web and mobile application to people can find nearest orphanages and make a visit to <b>bring good news</b>.
Application structure was made in <b>Next Level Week</b> event distributed by RocketSeat.


## 🛣 Routes

Server side of the <b>Happy</b> application using MVC architecture containing the following routes:


- **`POST /orphanages`**: Must receive `name`, `latitude`, `longitude`, `about`, `instructions`,
`opening_hours`,`open_on_weekends` and `images` inside <b>request body</b>, Example: 

```json
{
  "name": "Orfanato das mocinhas",
  "latitude": "-23.7664971",
  "longitude":"-53.291757",
  "about":"Novo orfanato",
  "instructions": "Venha visitar",
  "opening_hours": "Das 8h até 18h",
  "open_on_weekends": "true",
  "images": "orafanato-image.jpg",
}
```

- **`GET /orphanages`**: Return all orphanages in array.

- **`GET /orphanages/:id`**: Return orphanage of request params.


## 💻 Installation & play 

```sh

$ npm install
$ npm dev

```

## ⚡ Techs

* [Node.js] - evented I/O for the backend
* [Express] - fast node.js network app framework
* [Typescript] - typed superset of JavaScript that compiles to plain JavaScript.
* [TypeORM] - an ORM that can run in Nodej, browser, Cordova, PhoneGap, Ionic, React Native, NativeScript, Expo, and Electron platforms and can be used with TypeScript and JavaScript


[node.js]: <http://nodejs.org>
[express]: <http://expressjs.com>
[typescript]: <https://www.typescriptlang.org/>
[typeORM]: <https://typeorm.io/#/>
