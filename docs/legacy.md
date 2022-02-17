# Legacy JupyterHub 

The Legacy CUAHSI JupyterHub web application has been in service since 2014 and will be decommissioned on June 30th, 2020. It has been replaced by a scalable, fault tolerant, and more customizable platform hosted on the Google Cloud Platform.

To ensure no data loss, users must download all files prior to June 30th, 2020.  Below are several methods for downloading data from the legacy JupyterHub system (https://jupyter.cuahsi.org)

Download via the tree view interface by selecting the file of interest and clicking the “Download” button.

For downloading many files (or directories), first compress them, then download the compressed archive using method 1 (above).

Syncing data to your HydroShare iRODs space. First, make sure that your iRODs account has been activated (see documentation). Next, open a terminal inside the CUAHSI JupyterHub and initialize your iRODs connection as shown below.

Use the “ils” command to list files that exist in your HydroShare iRODs account.

Use “irsync” to move data from the CUAHSI JupyterHub into your HydroShare iRODs account.
