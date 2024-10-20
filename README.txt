
# To Run:

0. Have python (version 3.9.13 recommended). Python >= 3.6 should be fine.
1. Do `pip install virtualenv`
2. Create a new virtual environment using `virtualenv <name of virtualenv>`
3. Activate the virutal environment once done by changing the directory to `Scripts` with `cd Scripts` and then running the appropriate script file for your shell.
4. Do `pip install -r requirements.txt` in the project root.
6. Setup client_id and client_secret for spotipy.
5. Run `python final.py`.
6. Let the webcam interface pop up and then capture the output by pressing `q` on the keyboard. 


# Project Contents.

`final.py` is the main entrypoint file of the project.

`Emotion_Detection.ipynb` is the file used for training the model, standard jupyter notebook file.
