# MNE Workshop 2019

These are the resources for an MNE workshop.

Ensure you are using an up to date, Anaconda-based Python.

- <http://anaconda.com/download/>


## Installing MNE

### Accessing a Notebook

Please open a *Jupyter Notebook* -- i.e., by launching the [Anaconda Navigator](https://docs.anaconda.com/anaconda/navigator/).

### Installing MNE

In the Notebook, install the dev version of MNE by entering the following into a cell and executing the cell:

`!pip install https://api.github.com/repos/mne-tools/mne-python/zipball/master`

### Testing the Installation

When this command has finished, test MNE is working:

`import mne; print(mne.__version__)`

You should be seeing something like:
`0.18.dev0`

### Get example files and scripts

Download the [example file](https://github.com/jona-sassenhagen/mne_workshop_amsterdam/blob/master/oddball_example_small-fif.gz).

Also download the Jupyter Notebooks in this repository to the same location as the example file.

One convenient way for doing this would be, again from a Notebook cell:

`!git clone https://github.com/jona-sassenhagen/mne_workshop_amsterdam.git`
