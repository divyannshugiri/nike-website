# React + Vite

# Nike Website

This is a React-based Nike website project built with Vite. Follow the instructions below to run it locally.

---

## Steps to Run Locally

1. **Download the Project**
   - Download the ZIP folder from the repository.
   - Unzip it and rename the folder to `nike-website`.

2. **Navigate to the Project Folder**
```bash
cd nike-website
```

3. **Install Dependencies**
```bash
npm install
```
> **Note:** This reads the `package.json` file and installs all dependencies listed under `"dependencies"` and `"devDependencies"`. You must run this on any new PC or after cloning/unzipping the project because the `node_modules` folder is not included in the ZIP/repository.

4. **Run the Development Server**
```bash
npm run dev
```
> **Note:** This uses the `dev` script defined in your `package.json` to start the Vite development server.

5. **Open in Browser**
- Once the server starts, open the URL displayed in the terminal, usually:
```
http://localhost:5173
```

---

## Important Files

- **`package.json`** – Contains project metadata, scripts, and dependencies.  
- **`vite.config.js`** – Vite configuration file for React project setup.  
- **`node_modules/`** – Folder where all installed dependencies are stored (created automatically after running `npm install`).  

---

## Available Scripts (from `package.json`)

- `npm run dev` – Run the project in development mode.  
- `npm run build` – Build the project for production.  
- `npm run preview` – Preview the production build locally.  
- `npm run lint` – Run ESLint to check for code issues.

---

## Notes

- Make sure you have **Node.js installed** (preferably LTS version).  
- Folder name **must** be `nike-website` as per instructions.  
- Vite is already installed in this project as a dev dependency.  or install using  npm install vite --save-dev
- Always run `npm install` on a new machine before starting the project.

## Quick Steps

- cd nike-project
- npm install vite --save-dev
- npm run dev

