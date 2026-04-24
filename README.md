# IP Camera Shop

A simple web application for managing IP cameras.
Users can create, edit, delete, search, and sort camera items stored in the browser.

## Features

* Add new cameras with custom parameters
* Edit existing camera information
* Delete cameras
* Search by name, FPS, or resolution
* Sort cameras by FPS
* Data persistence using browser `localStorage`
* Image preview before saving


## Technologies Used

* HTML5
* CSS3
* JavaScript (Vanilla JS)
* LocalStorage API

## How It Works

The application uses `localStorage` as a simple database.
Each camera is stored as a JSON object with the following structure:

```js
{
  name: "Camera Name",
  fps: "60",
  video: "1920x1080",
  image: "image.jpg"
}
```

* On page load, all cameras are retrieved and rendered
* UI interactions update `localStorage`
* The interface reflects changes dynamically

---

## 📸 Screenshots

*(Add screenshots here if you want — it will make your project look more professional)*

---

## Known Limitations

* Uses `localStorage` instead of a real backend
* Page reloads are used after some actions (will be improved)
* Inline event handlers are present (planned refactor)

---

## Future Improvements

* Remove `location.reload()` and implement dynamic rendering
* Replace inline event handlers with `addEventListener`
* Introduce application state management
* Refactor code into ES6 modules
* Improve UI/UX and responsiveness
* Connect to a real backend (API)

---

## Author

Created as a learning project to practice JavaScript and DOM manipulation.
Currently being improved and refactored for better architecture and scalability.

---
