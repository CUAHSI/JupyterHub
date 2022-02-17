# Installing Software

The CUAHSI JupyterHub supports persistent virtual environments using the Anaconda package manager. This new feature allows you to create custom environments that capture software dependencies of unique use cases that will persist between sessions. The following steps demonstrate how to create a persistent virtual environment.

Launch a terminal within your JupyterHub instance. Create a new Anaconda virtual environment using the command below, making sure to install the “ipykernel” library.

Once successfully created, you should see instructions for activating and deactivating the environment:

This new environment is saved in `data/conda-envs` and will persist between JupyterHub sessions. This means that next time you come back, your Anaconda environment will exist. To use this environment you may need to click the refresh button in the JupyterLab toolbar. You should be able to create new notebooks with this custom environment from the Launcher panel, e.g. clicking on the icon showing “conda env:test-env”.

Alternatively, you can activate this virtual environment in existing notebooks via the kernel selection dialog.




