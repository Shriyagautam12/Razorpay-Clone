# RAZORPAY CLONE

## Introduction

This README file provides an overview and instructions for setting up and using a Tailwind project. Tailwind is a utility-first CSS framework that allows you to rapidly build user interfaces by composing small utility classes.


It is a clone of the famous Razorpay clone website.
Technology used are:- HTML, TAILWIND , JAVASCRIPT

## Project Structure

index.html: The main HTML file for your project.
styles.css: The CSS file where you can define custom styles and use Tailwind utility classes.
tailwind.config.js: The Tailwind configuration file where you can customize the framework's settings.
package.json: The NPM package configuration file that includes project dependencies and scripts.


## Getting Started
To get started with the Tailwind project, follow these steps:

1. Clone the project repository or create a new directory for your project.

2. Navigate to the project directory using the command line.

3. Run npm init to initialize a new package.json file, or if you have an existing package.json file, skip this step.

4. Install Tailwind CSS by running npm install tailwindcss.

5. Create a new styles.css file or open an existing one in your project directory.

6. In the styles.css file, import Tailwind CSS by adding the following line at the beginning:

```bash
@import 'tailwindcss/base';  
```

```bash
@import 'tailwindcss/components';
```

```bash
@import 'tailwindcss/utilities';

```
7. Create a new tailwind.config.js file in your project directory. You can generate a basic configuration file by running npx tailwindcss init.

8. Customize the configuration file (tailwind.config.js) based on your project requirements. You can modify colors, fonts, breakpoints, and more.

9. In the command line, run npx tailwindcss build styles.css -o output.css to compile your CSS file with Tailwind utility classes. This command will generate a new output.css file.

10. Link the output.css file to your HTML file using a <link> tag.

11. Start building your user interface by applying Tailwind utility classes to your HTML elements.


## Scripts

The following scripts are available in the package.json file:

```bash
npm run build 
```

Compiles the styles.css file with Tailwind utility classes and generates the output.css file.

```bash
npm run watch
```

Watches for changes in the styles.css file and automatically recompiles it whenever changes are made.

You can run these scripts using npm run <script-name>.

## Live Link 

https://shriya-razorpayclone-17.netlify.app/