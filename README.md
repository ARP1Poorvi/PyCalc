
# PyCalc
**A simple and intuitive calculator app built with Python and Tkinter.**

---

## About PyCalc
PyCalc is a lightweight and easy-to-use calculator application designed for Linux users. Whether you’re performing basic arithmetic operations or diving into more advanced calculations, PyCalc delivers a clean and efficient experience.

This application is packaged as a `.deb` file for convenient installation on Debian-based Linux distributions like Ubuntu, Linux Mint, and others.

---

## Features
- **Basic Arithmetic**: Add, subtract, multiply, and divide with ease.  
- **Intuitive GUI**: Simple, user-friendly interface powered by Tkinter.  
- **Cross-Platform Development**: Optimized for Linux systems.  
- **Lightweight**: Minimal resource usage, ensuring fast performance.

---

## Installation

### Requirements
- Python 3.9 or higher  
- Debian-based Linux OS (Ubuntu, Linux Mint, etc.)  

### Steps to Install
1. Download the `.deb` file from the [Releases Page](#).  
2. Open a terminal and navigate to the directory containing the `.deb` file.  
3. Install the package using:
   ```bash
   sudo dpkg -i pycalc_<version>.deb
   ```
4. Fix any missing dependencies (if necessary):
   ```bash
   sudo apt-get -f install
   ```
5. Launch PyCalc from the application menu or by typing `pycalc` in the terminal.

---

## Screenshots
![PyCalc Screenshot](#)  
*(Include a screenshot or GIF of the app in action.)*

---

## Usage
Once installed, you can launch PyCalc by:
1. Searching for **PyCalc** in your application menu.  
2. Or, running it directly from the terminal:
   ```bash
   pycalc
   ```

---

## Building the .deb Package
Want to build the `.deb` package yourself? Here’s how:  

1. Clone the repository:
   ```bash
   git clone https://github.com/ARP-Poorvi/PyCalc.git
   cd PyCalc
   ```
2. Install required tools:
   ```bash
   sudo apt-get install dpkg-deb
   ```
3. Build the package:
   ```bash
   ./build.sh
   ```
4. The `.deb` package will be generated in the `dist/` directory.

---

## Contributing
Contributions are welcome! If you’d like to contribute:  
1. Fork the repository.  
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Make your changes and submit a pull request.

---

## Contact
- **Publisher**: ARP.Poorvi  
- **Email**: [arp.poorvi@hotmail.com](mailto:arp.poorvi@hotmail.com)

---

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
