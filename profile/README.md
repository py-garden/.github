# 🪴 py-garden

A collection of Python utilities that extend and build upon the standard library.

## Usage

1. **Add `py-garden` to your project**

   You can include it by cloning, downloading, or adding it as a Git submodule:

   ```bash
   git submodule add git@github.com:py-garden/REPO_NAME_HERE.git
   ```   

   Example project structure:

   ```
   your_project/
   ├── main.py
   │   ├── fs_utils/
   │   ├── string_utils/
   │   └── ...
   ```

2. **Import and use modules**

   You can import directly from any submodule. For example:

   ```python
   from py_garden.fs_utils.main import *
   ```

   or import specific functions:

   ```python
   from py_garden.fs_utils.main import find_new_files, copy_directory
   ```
