# Cetin-Utils

<p align="center">
<img src="https://raw.githubusercontent.com/xertxetin/CetinJS/main/docs/media/cetin-utils-logo.png" alt="CetinJS Logo" width="200px">
</p>

<p align="center">
<a href="https://www.linkedin.com/company/me-force/" style="text-decoration: none;">
<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
</a>
<a href="https://www.instagram.com/meforce.technology/" style="text-decoration: none;">
<img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram">
</a>
<a href="https://www.youtube.com/@meforcetechnology/" style="text-decoration: none;">
<img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube">
</a>
<a href="https://www.facebook.com/meforce.tr" style="text-decoration: none;">
<img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" alt="Facebook">
</a>
<a href="https://discord.gg/4xh8GE6CYE" style="text-decoration: none;">
<img src="https://img.shields.io/badge/Discord-7289DA?style=for-the-badge&logo=discord&logoColor=white" alt="Discord">
</a>
</p>

**Cetin-Utils** is a comprehensive helper toolset tailored specifically for the **CetinJS Framework**, streamlining project workflows with efficient build, compression, and management utilities. Designed to work seamlessly with the **CetinJS compiler**, it ensures that your development processes are smooth and hassle-free.

## Features

### Key Functionalities
- **Project Build Automation**: Simplifies and automates the build process for your projects.
- **Code Compression**: Minifies and optimizes your files for better performance.
- **Script Execution**: Provides versatile utilities for running environments like web, mobile (Android), and development setups.

### Compatibility
- Fully integrated with the [**CetinJS Framework**](https://github.com/xertxetin/CetinJS/).
- Can be adapted to other projects following similar structure and conventions.


## Installation

### NPM Installation
Install **Cetin-Utils** via NPM:

```bash
npm install cetin-utils
```

## Usage

Leverage **Cetin-Utils** to simplify common tasks. You can also integrate its commands directly into your `package.json` scripts for seamless execution within your project.

### Example `package.json` Scripts

```json
"scripts": {
  "build": "node node_modules/cetin-utils/build.js",
  "web": "node node_modules/cetin-utils/run-build.js",
  "android": "node node_modules/cetin-utils/run-open-android.js",
  "core-check": "node node_modules/cetin-utils/run-check-cetin-core.js",
  "start": "node node_modules/cetin-utils/run-src.js"
}
```

### Running Commands
1. **Build Projects:**
   ```bash
   npm run build
   ```
2. **Run Web Environment:**
   ```bash
   npm run web
   ```
3. **Open Android Development Setup:**
   ```bash
   npm run android
   ```
4. **Start Development Server:**
   ```bash
   npm run start
   ```

### Cetin-Core Module States

---

> **Important Notice:** 
> 
> The [**`@cetin-utils`**](https://www.npmjs.com/package/cetin-utils) module requires the [**`@cetin-core`**](https://www.npmjs.com/package/cetin-core) module to function properly.
> 
> For building and running **`npm run core-check`**, the [**`@cetin-core`**](https://www.npmjs.com/package/cetin-core) module is required. Please ensure it is included.

---

5. **Check Cetin Core:**
   ```bash
   npm run core-check
   ```

| ![Cetin-Core Available](https://raw.githubusercontent.com/xertxetin/CetinJS/main/docs/media/cetin-utils/available-core.jpg) | ![Cetin-Core Not Available](https://raw.githubusercontent.com/xertxetin/CetinJS/main/docs/media/cetin-utils/not-core.jpg) |
| ---------------------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| **Shows that Cetin-Core is present and up-to-date in your project** | **Shows that Cetin-Core is not present in your project, and the module needs to be installed** |

| ![Cetin-Core Update Install](https://raw.githubusercontent.com/xertxetin/CetinJS/main/docs/media/cetin-utils/update-install-core.jpg) | ![Cetin-Core New Version](https://raw.githubusercontent.com/xertxetin/CetinJS/main/docs/media/cetin-utils/new-version-core.jpg) |
| ---------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------- |
| **Shows that the Cetin-Core module exists, but it is not in your project, and it has been added** | **Shows that the Cetin-Core module is not up-to-date and needs to be updated** |


## Why Use Cetin-Utils?

- **Efficiency**: Automates repetitive tasks, allowing you to focus on development.
- **Seamless Integration**: Built for **CetinJS**, yet versatile enough to fit other compatible project structures.
- **Lightweight**: Designed with minimal overhead, keeping your project clean and fast.
- **Adaptability**: Extend or customize it for projects that share **CetinJS**'s conventions.


## Contributing

We welcome contributions! If you have feature ideas or improvements, feel free to:

- **Open an Issue**: Share your suggestions or bug reports.
- **Submit a Pull Request**: Contribute directly to the [GitHub repository](https://github.com/xertxetin/cetin-utils/pulls).



## License

This project is licensed under the **CC BY-NC-ND 4.0 License**. See the [LICENSE](./LICENSE.md) file for more details.

## Additional Terms
The core components of the CetinJS framework are currently closed-source and encrypted. This means that the fundamental structure and internal workings of the framework are not shared with users. As a result, the core code of CetinJS will not be accessible or modifiable in an open manner.

However, CetinJS provides developers with the ability to create and develop projects. Users can leverage CetinJS to build high-performance and compatible applications for various projects.

You can create applications using the Core software and publish and distribute these applications under your brand name. Simply providing attribution to CetinJS is sufficient. Since the Core software is encrypted (because the project's direction is not yet clear, there are no commercial activities, and future plans are still uncertain), it is prohibited to crack or modify it, and attempting to redistribute it is also forbidden.

---

Developed with ❤️ by [XertXetin](https://www.google.com/search?q=XertXetin) 🚀 [Me Force Technology](https://www.meforcetechnology.com/).

<p align="center">
<a href="https://www.buymeacoffee.com/xertxetin" style="text-decoration:none;"><img src="https://img.buymeacoffee.com/button-api/?text=Buy me a coffee&emoji=&slug=xertxetin&button_colour=BD5FFF&font_colour=ffffff&font_family=Comic&outline_colour=000000&coffee_colour=FFDD00" /></a>
</p>