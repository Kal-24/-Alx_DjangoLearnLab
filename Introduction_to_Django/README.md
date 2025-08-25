# LibraryProject

A basic Django project for managing a library. Includes a simple app (`books`) with initial setup and routing.

## Project Structure

import os

file_path = 'LibraryProject/README.md'

if os.path.isfile(file_path) and os.path.getsize(file_path) > 0:
    print("README.md exists and is not empty.")
else:
    print("README.md does not exist or is empty.")
