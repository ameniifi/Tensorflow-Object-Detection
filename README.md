# Tensorflow-Object-Detection

## Steps
<br />
<b>Step 1.</b> Clone this repository
<br/><br/>
<b>Step 2.</b> Create a new virtual environment 
<pre>
python -m venv tfod
</pre> 
<br/>
<b>Step 3.</b> Activate your virtual environment
<pre>
source tfod/bin/activate # Linux
.\tfod\Scripts\activate # Windows 
</pre>
<br/>
<b>Step 4.</b> Install dependencies and add virtual environment to the Python Kernel
<pre>
python -m pip install --upgrade pip
pip install ipykernel
python -m ipykernel install --user --name=tfodj
</pre>
<br/>
<b>Step 5.</b> Collect images using the NotebookImage Collection.ipynb- ensure you change the kernel to the virtual environment as shown below
<br/>
<b>Step 6.</b> Manually divide collected images into two folders train and test. So now all folders and annotations should be split between the following two folders.
<b>Step 7.</b> Begin training process: Training and Detection.ipynb
<b>Step 8.</b> During this process the Notebook will install Tensorflow Object Detection. You should ideally receive a notification indicating that the API has installed successfully at Step 8 with the last line stating OK.  
<b>Step 9.</b>Train the model
<br />
evaluate with tensorboard optional
