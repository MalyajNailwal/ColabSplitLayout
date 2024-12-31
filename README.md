# **ColabSplitLayout**

**ColabSplitLayout** is a browser extension designed to enhance the Google Colab interface by splitting the screen into two equal sections: one for writing code and the other for displaying outputs. This extension helps organize your workspace, improving productivity and making it easier to work with Colab notebooks.

---

## **Features**

- **50/50 Layout**: Split the screen into two equal parts—code on the left and output on the right.
- **Improved Workflow**: View your code and outputs simultaneously for better multitasking.
- **Easy to Use**: A simple extension that integrates seamlessly into the Google Colab interface.

---

## **Files Included**

- **`manifest.json`**: The configuration file that defines the extension’s settings and permissions.
- **`content_script.js`**: JavaScript responsible for manipulating the Google Colab DOM and splitting the layout.
- **`flex.css`**: CSS file to style the layout and ensure the 50/50 split is visually appealing and responsive.

---

## **Installation**

### **Step 1**: Clone the repository or download the extension files.

### **Step 2**: Load the extension into Chrome

1. Open Chrome and navigate to `chrome://extensions/`.
2. Enable **Developer Mode** by toggling the switch in the top-right corner.
3. Click **Load unpacked** and select the folder where the extension files (`manifest.json`, `content_script.js`, `flex.css`) are stored.
4. The extension will now be installed and ready to use.

---

## **Usage**

Once the extension is installed, simply open **Google Colab** (https://colab.research.google.com/), and the layout will automatically split into two sections:
- **Left side**: Displays your code cells.
- **Right side**: Displays the output from code execution.

---

## **Contributing**

Feel free to fork the repository and submit pull requests if you'd like to contribute. You can also open issues for bug reports or feature requests.

---

## **License**

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
