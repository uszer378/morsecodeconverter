Morse Code Converter Bash Script

This is a simple bash script that converts plain text into International Morse Code. It supports various input methods, making it flexible for different use cases.
Features

    Command-line Argument: Convert a string directly from the command line.

    Standard Input (stdin): Convert text piped from other commands or redirected from a file.

Installation

    Save the script:
    Create a file named ctmc and paste the script's content into it.

    Make it executable:
    Open your terminal and navigate to the directory where you saved ctmc. Then run:

    chmod +x ctmc



Usage
1. Convert text from command-line argument

Enclose your text in quotes if it contains spaces.

./ctmc "Hello World"
# Output: .... . .-.. .-.. --- / .-- --- .-. .-.. -..

./ctmc "SOS"
# Output: ... --- ...



2. Convert text from standard input (piping or redirection)

Using a pipe (|):

echo "Piping example" | ./ctmc
# Output: .--. .. .--. .. -. --. / . -..- .- -- .--. .-.. .



Using input redirection (<):

# Assuming you have a file named input.txt
# echo "Text from input file." > input.txt

./ctmc < input.txt
# Output: - . -..- - / ..-. .-. --- -- / .. -. .--. ..- - / ..-. .. .-.. . .-.-.-



License

This project is licensed under the MIT License - see the LICENSE file for details (if you choose to add one to your repository).
