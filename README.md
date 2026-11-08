# Meme Generator 🎭

A modern React application that allows users to dynamically customize memes by editing top and bottom text fields and fetching random meme templates from the [Imgflip API](https://api.imgflip.com/get_memes).

---

## Features

* **Live Text Editing:** Real-time synchronization between input fields and the generated meme preview.
* **API Integration:** Asynchronously fetches a comprehensive list of popular meme templates using `useEffect` and `fetch`.
* **Randomized Generation:** Randomly selects and displays a fresh meme template from the fetched dataset every time the generator button is clicked.
* **React State Management:** Built using React Hooks (`useState`, `useEffect`) to efficiently manage user inputs, fetched template arrays, and current meme states.

---

## Tech Stack

* **React** (v19)
* **JavaScript** (ES6+)
* **CSS3**
* **Imgflip API**

---

## Getting Started

### Prerequisites

Make sure you have [Node.js](https://nodejs.org/) installed on your machine.

### Installation & Running Locally

1. Clone the repository:
   ```bash
   git clone <repository-url>
