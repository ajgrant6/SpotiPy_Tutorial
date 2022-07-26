# Welcome to your SpotiPy crash course!

The SpotiPy Library gives developers access to music data and controls with easy to use tools. In this tutorial, we will be using the SpotiPy Library to view and control our music playback.

---

## Starting the tutorial

To start this tutorial, simply download the contents of the repo and open SpotPy_Tutorial.ipynb.

This tutorial makes use of the SpotiPy Library. You can read about the API here: https://spotipy.readthedocs.io/en/master/

To install the library, type the following command into your terminal:

> pip install spotipy --upgrade

Alternatively, you can get the source here https://github.com/plamere/spotipy

---

## Common issues and how to fix them
>[Errno 48] Address already in use

This error occurs if the authentication process is interrupted. This causes this Python notebook to continue running it's authentication proccess when it really shouldn't. The fix is to simpy restart the notebook.