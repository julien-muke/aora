<div align="center">
  <br />
    <a href="https://youtu.be/R8CIO1DZ2b8" target="_blank">
      <img src="https://github.com/julien-muke/aora/assets/110755734/91924a24-c84a-4fb4-8b08-cad8635599b1" alt="Project Banner">
    </a>

  <br />

  <div>
    <img src="https://img.shields.io/badge/-React_Native-black?style=for-the-badge&logoColor=white&logo=react&color=61DAFB" alt="react.js" />
    <img src="https://img.shields.io/badge/-Appwrite-black?style=for-the-badge&logoColor=white&logo=appwrite&color=FD366E" alt="appwrite" />
    <img src="https://img.shields.io/badge/NativeWind-black?style=for-the-badge&logoColor=white&logo=tailwindcss&color=06B6D4" alt="nativewind" />
  </div>

  <h3 align="center">Video Sharing App</h3>
</div>

## <a name="introduction">🤖 Introduction</a>

Built with React Native for seamless user experiences, Animatable for captivating animations, and integrated with the dependable backend systems of Appwrite, 
this app showcases impressive design and functionality, enabling seamless sharing of AI videos within the community.


## <a name="tech-stack">⚙️ Tech Stack</a>

- React Native
- Expo
- Nativewind
- Animatable
- Appwrite

## <a name="features">🔋 Features</a>

👉 **Onboarding Screen**: Engaging graphics and clear instructions welcome users to the app.

👉 **Robust Authentication & Authorization System**: Secure email login safeguards user accounts.

👉 **Dynamic Home Screen with Animated Flat List**: Smoothly animated flat list showcases the latest videos for seamless browsing.

👉 **Pull-to-Refresh Functionality**: Users can refresh content with a simple pull gesture for up-to-date information.

👉 **Full-Text Search Capability**: Efficiently search through videos with real-time suggestions and instant results.

👉 **Tab Navigation**: Navigate between sections like Home, Search, and Profile with ease using tab navigation.

👉 **Post Creation Screen for Uploading Media**: Upload video and image posts directly from the app with integrated media selection.

👉 **Profile Screen with Detailed Insights**: View account details and activity, including uploaded videos and follower count, for a personalized experience.

👉 **Responsiveness**: Smooth performance and adaptability across various devices and screen sizes for a consistent user experience.

👉 **Animations**: Dynamic animations using the Animatable library to enhance user interaction and engagement throughout the app's UI.

and many more, including code architecture and reusability.

## <a name="quick-start">🤸 Quick Start</a>

Follow these steps to set up the project locally on your machine.

**Prerequisites**

Make sure you have the following installed on your machine:

- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/en)
- [npm](https://www.npmjs.com/) (Node Package Manager)

**Cloning the Repository**

```bash
git clone https://github.com/adrianhajdin/aora.git
cd aora
```
**Installation**

Install the project dependencies using npm:

```bash
npm install
```

**Running the Project**

```bash
npm start
```

**Expo Go**

Download the [Expo Go](https://expo.dev/go) app onto your device, then use it to scan the QR code from Terminal and run.

## <a name="snippets">🕸️ Snippets</a>

<details>
<summary><code>app/globals.css</code></summary>

```css
@tailwind base;
@tailwind components;
@tailwind utilities;

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

/* ======== stream css overrides ======== */
.str-video__call-stats {
  max-width: 500px;
  position: relative;
}

.str-video__speaker-layout__wrapper {
  max-height: 700px;
}

.str-video__participant-details {
  color: white;
}

.str-video__menu-container {
  color: white;
}

.str-video__notification {
  color: white;
}

.str-video__participant-list {
  background-color: #1c1f2e;
  padding: 10px;
  border-radius: 10px;
  color: white;
  height: 100%;
}

.str-video__call-controls__button {
  height: 40px;
}

.glassmorphism {
  background: rgba(255, 255, 255, 0.25);
  backdrop-filter: blur(4px);
  -webkit-backdrop-filter: blur(4px);
}
.glassmorphism2 {
  background: rgba(18, 17, 17, 0.25);
  backdrop-filter: blur(8px);
  -webkit-backdrop-filter: blur(8px);
}

/* ==== clerk class override ===== */

.cl-userButtonPopoverActionButtonIcon {
  color: white;
}

.cl-logoBox {
  height: 40px;
}
.cl-dividerLine {
  background: #252a41;
  height: 2px;
}

.cl-socialButtonsIconButton {
  border: 3px solid #565761;
}

.cl-internal-wkkub3 {
  color: white;
}
.cl-userButtonPopoverActionButton {
  color: white;
}

/* =============================== */

@layer utilities {
  .flex-center {
    @apply flex justify-center items-center;
  }

  .flex-between {
    @apply flex justify-between items-center;
  }
}

/* animation */

.show-block {
  width: 100%;
  max-width: 350px;
  display: block;
  animation: show 0.7s forwards linear;
}

@keyframes show {
  0% {
    animation-timing-function: ease-in;
    width: 0%;
  }

  100% {
    animation-timing-function: ease-in;
    width: 100%;
  }
}
```

</details>