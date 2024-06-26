The "permission denied" error suggests that the script does not have execute permissions. You can resolve this by modifying the file permissions using the `chmod` command. Here are the steps you need to follow:

1. Ensure you are in the directory where the script is located.
2. Run the `chmod` command to add execute permissions to the script.

Here's a quick guide:

1. **Navigate to the directory containing the script:**
   ```bash
   cd /path/to/your/script
   ```

2. **Add execute permissions to the script:**
   ```bash
   chmod +x get_code_context_java.sh
   ```

3. **Run the script:**
   ```bash
   ./get_code_context_java.sh
   ```

### README.md

Update the `README.md` file with these instructions:

```markdown
# Java Project Code Context Script

This repository contains a Bash script designed to gather and compile the code context of a Java project into a single file. This can be particularly useful for code reviews, documentation, or just getting a comprehensive view of your project structure and contents.

## Features

- Recursively scans specified directories for Java source files.
- Ignores specified file types (e.g., `.class`, `.jar`, image files).
- Compiles the relative paths and contents of relevant files into a single output file.

## Getting Started

### Prerequisites

- Unix-based operating system (Linux, macOS) or WSL (Windows Subsystem for Linux).
- Bash shell.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/java-code-context.git
   cd java-code-context
   ```

2. **Make the script executable:**
   ```bash
   chmod +x get_code_context_java.sh
   ```

### Usage

1. **Place the script in the root folder of your Java project.**

2. **Run the script:**
   ```bash
   ./get_code_context_java.sh
   ```

3. **Check the output:**
   - The script will create a file named `code_context.txt` in the root directory of your project.
   - This file contains the paths and contents of all relevant Java source files, formatted for easy reference.

### Example Directory Structure

```
my-java-project/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── com/
│   │   │       └── example/
│   │   │           └── MyClass.java
│   │   └── resources/
│   │       └── application.properties
│   └── test/
│       └── java/
│           └── com/
│               └── example/
│                   └── MyClassTest.java
│
├── lib/
│   └── some-library.jar
│
├── get_code_context_java.sh
└── code_context.txt
```

### Customization

- **Directories:** You can modify the `directories` array in the script to include any other directories you want to scan.
- **Ignore Files:** You can modify the `ignore_files` array to ignore other file types as needed.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License.

## Acknowledgements

- This script is inspired by the need to better understand and document Java projects. Special thanks to all open-source contributors!

---

Feel free to reach out if you have any questions or suggestions!
```

Make sure to replace `https://github.com/yourusername/java-code-context.git` with your actual GitHub repository URL. This `README.md` file now includes instructions for making the script executable, which should help avoid permission issues.
