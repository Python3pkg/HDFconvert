# HDFconvert
To convert HDF files to Image files with Python

# H5toImage.py
Currently, only this function is supported.
    load_path: directory path to load
    save_path: directory path to save
    target: target name in hdf file. It must be array.
    
You may use it as follows:


<code>pip install HDFconvert</code>

<code>import H5toImage</code>

<code>H5toimage.makeDataset(load_path, save_path, target)</code>
