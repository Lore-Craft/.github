# About

LoreCraft is an innovative app that leverages the power of AI imaging to provide users with a seamless experience in creating unique characters and their backstories instantly. Crafted with React.js, it integrates various components to streamline the process of character creation, letting users delve deeper into the realm of creativity.

It comprises of a backend api and a frontend (React) component.
Backend Repo: <a href="https://github.com/Lore-Craft/lorecraft-api">https://github.com/Lore-Craft/lorecraft-api</a>
Frontend Repo: <a href="https://github.com/Lore-Craft/lorecraft-frontend">https://github.com/Lore-Craft/lorecraft-frontend</a>

## Live Demo
View the live deployment here: <a href="https://lorecraft.netlify.app/">lorecraft.netlify.app</a>


### Version
Current version: v1.0


## Screenshots
<img style="width:400px;" src="https://i.ibb.co/TLVWTFT/image.png">


## Features

### Instant Character Creation
Harness the power of AI to instantly generate characters with rich backstories and visuals.

### Intuitive UI
Experience a user-friendly interface designed to facilitate creativity and imagination.

### Secure Authentication
Utilize the secure Auth0 authentication system to protect your data and creations.


## Installation

To get started with LoreCraft, follow these steps:

1. Clone the repository (both the front-end and back-end)

> `git clone https://github.com/Lore-Craft/lorecraft-api.git`

> `git clone https://github.com/Lore-Craft/lorecraft-frontend.git`

2. Navigate to the project directory

> `cd lorecraft-api`

> `cd lorecraft-frontend`

3. Install the necessary packages

> `npm install`

4. Run the app

> `npm start`


## Technology Stack

- **React.js**: The frontend is developed using the robust and popular React.js library.
- **Auth0**: Integrated for secure user authentication and data protection.
- **ChatGPT**: Utilized for generating character backstories using natural language processing.
- **AI Imaging**: Employed to create visual representations of the generated characters.


## App Structure

Here is a brief overview of the main components of the app:

- **About**: A component displaying detailed information about LoreCraft.
- **CreateNew**: The core component where users can create new characters and backstories.
- **Creations**: A section where users can view and manage their created characters.
- **LoggedinComponent**: A component that handles functionalities available to logged-in users.
- **App.css**: The stylesheet containing styles for the app.
- **React Router**: Used to manage the routing of the app, facilitating smooth navigation between components.


## Usage

Navigate through the app using the following routes:

- `/about`: Learn more about LoreCraft.
- `/createnew`: Dive into the creation process and start crafting your characters.
- `/creations`: View and manage your repository of created characters.


## Data Required
- Character name: charName: { type: String, required: true }
- Character vlass: classType: { type: String, required: true },
- Character alignment: { type: String, required: true },
- Character race: {type: String, required: true},
- Character's gender: { type: String, required: true },
- URL of image (AI generated): imageURL: { type: String, required: true },
- Character backstory (AI generated): { type: String, required: true },
- Your email (same as your login details): userEmail: { type: String, required: true}


## Contributing

We welcome contributions to LoreCraft. Before contributing, please read through our contributing guidelines (link to the guidelines).


## License

Released under MIT License.


## Contact

- [Ekaterina](https://www.linkedin.com/in/ekaterina-khoroshilova)
- [Nika](https://www.linkedin.com/in/nicholas-skeba)
- [Paul](https://www.linkedin.com/in/tallpaulbrown/)

