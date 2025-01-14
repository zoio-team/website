# Project Setup and Usage with Yarn

## Prerequisites
Ensure the following tools are installed on your system:
- **Node.js**: Download from [Node.js Official Website](https://nodejs.org/).
- **npm**: Comes bundled with Node.js.

---

## Installing Yarn
To install Yarn globally, run the following command using `npm`:

```bash
npm install -g yarn
```

### Verifying Yarn Installation
To check if Yarn is installed and view its version, run:

```bash
yarn --version
```

---

## Project Setup

### Step 1: Navigate to the Project Directory
Use the terminal to navigate to the root directory of your project:

```bash
cd /path/to/your/project
```

### Step 2: Install Dependencies
Run the following command to install all dependencies listed in the `package.json` file:

```bash
yarn install
```

This will create a `node_modules` folder containing all necessary packages.

---

## Running the Development Server
After setting up the dependencies, start the development server by running:

```bash
yarn run dev
```

This will execute the `dev` script defined in the `package.json` file. The project should now be running locally, and you can access it through the URL provided in the terminal (commonly `http://localhost:3000`).

---

## Additional Commands and Tips

### Check Yarn Version
To check the installed version of Yarn at any time:

```bash
yarn --version
```

### Run Other Scripts
You can run other scripts defined in `package.json` by replacing `dev` with the script name:

```bash
yarn run <script-name>
```

### Upgrade Yarn
To upgrade Yarn to the latest version:

```bash
npm install -g yarn@latest
```

---

## License
This project is licensed under [Your License].

---

By following this guide, you can successfully set up and run your project using Yarn. If you encounter any issues, feel free to open an issue or refer to the official [Yarn Documentation](https://yarnpkg.com/).


