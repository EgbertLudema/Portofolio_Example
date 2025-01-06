

# Portfolio Example

I forked this repository as this is a great example for on scroll animations.

## Tech Stack Used:
- ReactJS
- Tailwind CSS
- AOS
- Firebase
- Framer Motion
- Lucide
- Material UI
- SweetAlert2

---

# Tutorial to Run the Project  

Here is a simple guide to running this project.

## Preparation  

Make sure you have installed:

- **Node.js**

## Steps to Run the Project  

1. **Download this project:**  
   ```bash
   git clone https://github.com/EkiZR/Portofolio_V5.git
   ```

2. **Install all dependencies:**  
   ```bash
   npm install
   ```  
   or alternatively:  
   ```bash
   npm install --legacy-peer-deps
   ```

3. **Run the project:**  
   ```bash
   npm run dev
   ```

4. **Open in the browser:**  
   Access the application through the link displayed in the terminal.

---

## Creating a Production Build  

To create a production-ready version:

1. Run the build command:  
   ```bash
   npm run build
   ```

2. The build files will be saved in the `dist` folder. You can upload this folder to your hosting server.

---

## Notes  

If you encounter issues running the project, ensure:

- Node.js is installed correctly.
- You are in the correct project folder.
- All dependencies are installed without errors.

---

## Firebase Configuration  

To configure Firebase in this project, follow these steps:

1. **Add Firebase to the Project:**  
   - Go to the [Firebase Console](https://console.firebase.google.com/).  
   - Create a new project or use an existing one.

2. **Select Firestore Database:**  
   - Create a database.

3. **Go to Project Settings:**  
   - Click the relevant section (see screenshot below).  
   - Copy the Firebase configuration content (as shown in the second screenshot).

4. **Update Rules:**  
   - Set the rules to `true`.

5. **Adjust the Collection Structure:**  
   - Follow the structure shown in the screenshots provided.

6. **Edit `firebase.js` and `firebase-comment.js` Files:**  
   - Replace the `firebaseConfig` content with your Firebase configuration.
