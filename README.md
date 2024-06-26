# Code Context Script

This project is designed to help you generate a comprehensive context of your project's files, making it easier to navigate and understand your codebase and, more importantly, copy into ChatGPT or any AI tool of your choice to get code fixes and improvements! For now, the supported files are Python and Java files, given that they're my most used languages. More to come later.

## About This Project

Inspired by CleverProgrammer's original script for Next.js projects, this script has been adapted to work seamlessly with Java projects. 

### Original Inspiration

A big shoutout to [CleverProgrammer](https://github.com/CleverProgrammer) for the original script that inspired this project. You can find the original script [here](https://gist.github.com/CleverProgrammer/d36ea84aa3311ce722fdf90ce3b740d2).

## How to Use This Script

Follow these simple steps to get the script running on your machine:
### Java Projects

1. **Clone the Repository**
    ```bash
    git clone https://github.com/nanadotam/Get-Code-Context.git
    cd Get-Code-Context.git
    ```

2. **Make the Script Executable**
    ```bash
    chmod +x get_code_context_java.sh
    ```

3. **Run the Script**
    ```bash
    ./get_code_context_java.sh
    ```
The script will create a `code_context.txt` file in the root directory of your project, containing the relative paths and contents of your Java files, excluding specified file types.

### Python Projects

1. **Clone the Repository**
    ```bash
    git clone https://github.com/nanadotam/Get-Code-Context.git
    cd Get-Code-Context.git
    ```

2. **Make the Script Executable**
    ```bash
    chmod +x get_code_context_python.sh
    ```

3. **Run the Script**
    ```bash
    ./get_code_context_python.sh
    ```
The script will create a `code_context.txt` file in the root directory of your project, containing the relative paths and contents of your Python files and Jupyter notebooks, excluding specified file types.

## Future Plans

This repository will continue to evolve with additional scripts and functionalities to support more programming languages and project structures. Stay tuned for updates!

## Contributing

Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request. If you encounter any issues or have suggestions, please open an issue on GitHub.

---

Thank you for checking out this project! We hope it helps you manage and navigate your Java projects more effectively. Happy coding!

