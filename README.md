[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/DwH5pKU3)
# Installation and Run Instructions

1. Clone this repository to your local machine.
   1. Look for a green "Code" button on the repository page.
   2. Click it and copy the URL.
   3. Open your terminal and run `git clone <URL>` replacing `<URL>` with the URL you copied.
2. Navigate into the cloned repository folder with `cd` (do `ls` if you can't find the folder).
3. Install `uv` - this depends on your operating system.
    1. For Mac OS:
        1. Install Homebrew: https://brew.sh/
        2. Run `brew install uv` in your terminal
    2. For Windows:
        1. Set up WSL and follow the Linux instructions: https://learn.microsoft.com/en-us/windows/wsl/install
    3. For Linux:
        1. Run `curl -LsSf https://astral.sh/uv/install.sh | sh`
4. Run `uv run --with jupyter jupyter lab` in the terminal to start Jupyter Lab.
5. Open `priority_queue` notebook and begin working on the assignment. There are two other notebooks as well for tutorials.
   1. Actual priority queue implementation is in the priority_queue/prioritiy_queue.py file. The notebook is used for testing.
6. To run tests, in your terminal, run `uv run pytest`, or run them in the notebook. If you failed any tests, you can look at the test to see what it is doing.
7. When done, commit your changes and push them to GitHub.
   1. `git add .`
   2. `git commit -m "your commit message"`
   3. `git push`
   4. Check the Actions tab in your repository to see if the tests passed. If they didn't, you can click on the tests to see what you failed. There are no hidden tests. 