# ComfyUI Setup on AMD Windows

- Clone the ComfyUI repository from https://github.com/comfyanonymous/ComfyUI
- If you already have a venv used for stable diffusion, you could reuse it
  - Open the cloned ComfyUI repo in a terminal
  - Activate the virtual environment by running the activate.bat command in the exising env. Example
    ```
    PS C:\Users\<myusername>\projects\ai\ComfyUI> C:\Users\<myusername>\projects\ai\stable-diffusion\venv\Scripts\activate
    ```
  - Install `torch-directmy` by running `py -m pip install torch-directml` in ther terminal
  - Install all the other dependencies for ComfyUI by running `py -m pip install -r .\requirements.txt` at the root of the ComyUI repository
  - Launch ComfUI by running `python main.py --directml `
