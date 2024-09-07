# Taskeight
This repository contains a Python script that generates an HTML registration form and saves it as a file. The form is static and does not process the submitted data, making it ideal for front-end examples or quick demonstrations.

## Overview

The Python script `script.py` generates a simple HTML registration form and writes it to a file named `registration.html`. This form includes fields for a user’s name, course selection, gender, phone number, address, email, and password.

### Features of the HTML Form:
- Input fields for first, middle, and last names.
- Dropdown menu to select a course (BCA, BBA, B.Tech, MBA, MCA, M.Tech).
- Radio buttons for gender selection.
- Text input for phone number and email.
- Text area for address.
- Password and confirm password input fields.

## Files in This Repository

- **script.py**: The Python script that generates the HTML registration form.
- **registration.html**: The generated HTML file containing the registration form.
- **index.html**: The original unmodified HTML file.

## Repository Structure

```
├── script.py                # The Python script that generates the HTML registration form
├── registration.html        # The generated HTML registration form
├── index.html               # The original unmodified HTML form
```


## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/AbhiramT21/Taskeight.git
    ```

2. Navigate to the repository's directory:

    ```bash
    cd Taskeight
    ```

3. Open `script.py` in a code editor (e.g., VSCodium).

4. Add a shebang to the first line of the script to allow it to be executed directly:

    ```python
    #!/usr/bin/env python
    ```

5. To make the script executable, grant execute permissions:

    ```bash
    chmod +x script.py
    ```

6. Execute the script without using the `python` command:

    ```bash
    ./script.py
    ```

    This will generate the `registration.html` file containing the registration form.

7. Open `registration.html` in a web browser to view the generated form.

## Shebang Explanation

A shebang (`#!/usr/bin/env python`) is added to the script to specify the path to the Python interpreter. This allows the script to be executed as a standalone program without explicitly calling `python`.

