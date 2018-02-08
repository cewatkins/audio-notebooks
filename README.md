# Digital Audio Coding Notebooks

Context: [Digital Audio Coding course][audio]

[audio]: https://eul.ink/audio

To get started: [![Launch Binder][binder-badge]][audio-binder]

[binder-badge]: https://img.shields.io/badge/Launch-Binder-blue.svg?style=flat-square
[audio-binder]: https://mybinder.org/v2/gh/boisgera/audio-notebooks/master

[Binder] turns this GitHub repository into a collection of interactive notebooks.
With Binder:


  - **You can't break anything (no matter how hard you try).**  
    Each Binder session starts with a fresh copy of the files in this repository.  
    

  - **You must download your notebooks to save your work.**  
    Open the `File` menu then select `Download as` and  `Notebook (.ipynb)`
    (you cannot also download any file -- not merely notebooks -- 
    from the "filesystem view"; you can also upload files in this view).

    This is necessary since all your changes are lost when you close your browser.
    Also, the "disk" button -- `Save and Checkpoint` -- won't work
    (well, it kinda does but only to save your notebook
    in a [Linux container] hosted "somewhere in the cloud" and 
    that will be destroyed shortly.)

If you want to work without Binder and you have a Linux computer 
with [conda] available, download this project and execute:

    $ conda env create -f environment.yml # create the 'audio' environment
    $ source activate audio               # activate 'audio'
    (audio) $ jupyter notebook            # start the jupyter server


[Binder]: https://mybinder.org/
[Linux container]: https://en.wikipedia.org/wiki/Linux_containers
[conda]: https://conda.io/docs/
