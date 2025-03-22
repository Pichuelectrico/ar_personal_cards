# AR Personal Cards

An augmented reality (AR) web application that displays interactive content when scanning a business card. Built with MindAR.js and A-Frame.

## Technologies Used

- Node.js
- MindAR.js
- A-Frame
- Three.js
- HTML/CSS
- JavaScript
- 3D Models (GLTF/GLB format)

## Prerequisites

Before you begin, ensure you have installed:

Node.js (v14.0.0 or higher)
npm (usually comes with Node.js)
A modern web browser with WebAR support

## Installation

- Clone the repository:

  ```
  git clone https://github.com/Pichuelectrico/ar_personal_cards.git
  cd ar_personal_cards
  ```

- Install dependencies: `npm install`

## Project Structure

```
ar_personal_cards/
├── public/
│ ├── icons/ # Social media and web icons
│ ├── images/ # Static images
│ ├── markers/ # AR markers and target images
│ ├── models/ # 3D models (GLTF)
│ └── index.html # Main application file
├── server.js # Express server configuration
├── node_modules/ # Node modules
├── package.json # Project dependencies
├── package-lock.json # Project dependencies
└── README.md # Project documentation
```

## Running the Project

- Start the server: `node server.js`

- Open your browser and navigate to: http://localhost:3000

## Creating AR Markers

The .mind target file used for AR tracking was created using the MindAR Image Compiler. To create your own markers:

- Visit [MindAR Image Compiler](https://hiukim.github.io/mind-ar-js-doc/tools/compile)
- Upload your target image
- Download the generated .mind file
- Place it in the public/markers directory

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contributing

- Fork the repository
- Create your feature branch (git checkout -b feature/AmazingFeature)
- Commit your changes (git commit -m 'Add some AmazingFeature')
- Push to the branch (git push origin feature/AmazingFeature)
- Open a Pull Request

## Acknowledgments

- MindAR.js for providing the AR framework
- A-Frame for 3D scene creation
- Three.js for 3D rendering capabilities
- Thanks to [Delo](https://sketchfab.com/DevFaisal) for the 3D model
