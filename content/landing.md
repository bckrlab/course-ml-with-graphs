# Machine Learning with Graphs

## Course Materials

Slides, exercise solutions and optional readings are uploaded to ILIAS weekly.

You can download/run the exercise notebooks in the following pages.


## Python Environment

If you prefer running the notebooks locally, you can set up a `Python` environment with either `uv` or `conda`.

### Option A: `uv`

1. Install `uv` by following [these](https://docs.astral.sh/uv/getting-started/installation/) instructions.

2. Download the `pyproject.toml` file [here](assets/pyproject.toml) and put it in the folder where you keep the notebooks.

3. In that folder, create the environment. Pick **one** of the two commands:
    ```
    uv sync --extra cpu      # no GPU (Linux, macOS, Windows)
    uv sync --extra cu130    # NVIDIA GPU with CUDA 13 drivers (Linux, Windows)
    ```
    `uv` downloads a suitable `Python` version automatically if you do not have one.

4. Start Jupyter inside the environment:
    ```
    uv run jupyter lab
    ```
    Alternatively, activate the environment with `source .venv/bin/activate` (Linux/macOS) or `.venv\Scripts\activate` (Windows) and select the kernel from `.venv` in your editor.

### Option B: `conda`

1. Download the `env.yml` file [here](assets/env.yml).

2. Create a `conda` environment. You can refer to [this](https://docs.conda.io/projects/conda/en/stable/user-guide/install/index.html) link for installation instructions for `conda`.
    ```
    conda env create -f env.yml -n mlwg
    ```

3. After the packages are installed, activate the environment by:
    ```
    conda activate mlwg
    ```
