## Getting Started

### Setting Up the Project

1. **Clone the Repository**
   
   ```bash
   git clone https://github.com/aakash-cr7/react-slack-clone
   cd react-slack-clone
   npm install
   npm start
   ```

2. **Configure Firebase**
   
   - Head over to the Firebase Console.
   - Create a new Firebase project.
   - Set up a "Web" app within your project to obtain your Firebase configuration.
   - Add your Firebase configuration details to `src/firebase.js`.

### Deploying the Project on Firebase

#### First-Time Setup

1. **Build the Project**
   
   ```bash
   npm run build
   ```

2. **Install Firebase CLI Tools**

   ```bash
   npm install -g firebase-tools
   firebase login
   ```

3. **Deploy to Firebase**

   ```bash
   firebase deploy
   ```

#### Subsequent Deployments

1. **Build and Deploy**

   ```bash
   npm run build
   firebase deploy
   ```

Now you're all set to get your project up and running on Firebase! If you have any questions or run into any issues, feel free to reach out.
