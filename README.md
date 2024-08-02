# Benchmark Datasets for Graph Layout Algorithms

This paper is under submission to the the [experimental track](https://www.journalovi.org/submit.html#experimental) at JoVI.

Papers for this track are written in [Quarto](https://quarto.org/) which is an open source publishing format that supports inline code, including languages like R, Python, Julia, and JavaScript (via Observable Notebook).

```diff
!  Only edit .qmd files! The other files are generated from this.
```

```diff
!  Commit the HTML version of the paper upon submission for ease of review.
```

## Setup instructions

1. Clone the repo.

   * On Windows, we currently have paths in the data directory that are too long for git to handle. This prevents cloning. To avoid this problem, run `git config --system core.longpaths true` with administrator rights.

2. `CD` to the repo directory. Create and activate a virtual environment for this project. You may need to modify the code you use depending on what Python you have installed and how your machine is configured.
3. Run the setup commands below.

    * On macOS, Linux, or Windows Subsystem for Linux, run these three commands *separately* in case there are errors:

        ```bash
        python3 -m venv env
        ```

        ```bash
        source env/bin/activate
        ```

        ```bash
        which python
        ```

    * On Windows, run these three commands *separately* in case there are errors:

        ```bash
        python -m venv env
        ```

        ```bash
        .\env\Scripts\activate.bat
        ```

        ```bash
        where.exe python
        ```

    Check the path(s) provided by `which python` or `where.exe python`—the first one listed *should* be inside the `env` folder you just created.

4. Install necessary packages.

    ```bash
    python -m pip install -r requirements-simple.txt
    ```

    If you want to install the exact versions used by the authors, run instead

    ```bash
    python -m pip install -r requirements-pinned.txt
    ```

    which containes the pinned package list generated by running `python -m pip freeze > requirements-pinned.txt` in the virtual environment.

    The install may take a few minutes.

## Run instructions

Follow the instructions at <https://quarto.org/docs/get-started/hello/>. If you are using the VSCode Quarto extension and WSL, ensure you start VSCode from the repository directory by running `code .` at the WSL terminal.

For example, to preview the website run

```bash
quarto preview --no-browser --no-watch-inputs
```

and to publish it to GitHub pages use

```bash
quarto publish --no-prompt gh-pages
```