# Flatacuties - Phase 1 Code Challenge

## Overview
Flatacuties is an interactive web application where users can vote for the cutest animal. This project demonstrates fundamental frontend skills including **DOM manipulation**, **event handling**, and **server communication** using JavaScript.

## Demo
Refer to the provided example GIF to understand how the app should function.

## Setup
1. Clone this repository:
   ```sh
   git clone https://github.com/DedanKIarie/Flatter-Cuttie
   ```
2. Navigate to the project folder:
   ```sh
   cd Flatter-Cuttie
   ```
3. Start the local server:
   ```sh
   json-server --watch db.json
   ```
4. Open the following URL in your browser to test the API:
   ```
   http://localhost:3000/characters
   ```
5. Open `index.html` in your browser to run the application.

## Features
- Display a list of characters in the **Character Bar**
- Click a character to view details
- Vote for characters and update vote count dynamically
- Add new characters via a form
- Reset votes for any character
- Persist votes and new characters using `fetch` requests

## Deliverables
### **Core Features**
- Display all character names inside `#character-bar` by fetching from:
  ```sh
  GET /characters
  ```
- Clicking a character shows its details in `#detailed-info`:
  ```sh
  GET /characters/:id
  ```
- Submit votes via `#votes-form` to increase the vote count (no persistence required).

### **Bonus Features**
- Reset votes using the "Reset Votes" button.
- Add new characters dynamically via `#character-form`.

### **Extra Bonus**
- Persist vote updates on the server:
  ```sh
  PATCH /characters/:id
  ```
- Persist new characters on the server:
  ```sh
  POST /characters
  ```

## License
This project is licensed under the **MIT License**. See the `LICENSE` file for details.

---

# LICENSE

MIT License

Copyright (c) 2025

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
