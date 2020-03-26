## Local Runtimes in colab

Colab also supports local runtimes, so that you colab will use your local system resources.

You need to have jupter already installed, if not install it by

for conda:
```
conda install -c conda-forge notebook
pip install jupyter_http_over_ws
```
else:
```
pip3 install notebook
pip3 install jupyter_http_over_ws
```
---
Now run a jupyter notebook like usual, though you will need to set a flag to explicitly trust WebSocket connections from the Colaboratory frontend. 
```
jupyter notebook \
  --NotebookApp.allow_origin='https://colab.research.google.com' \
  --port=8888 \
  --NotebookApp.port_retries=0
```

 Once the server has started, it will print a message with the initial backend URL used for authentication. Make a copy of this URL as you'll need to provide this in the next step.
Step 4: Connect to the local runtime

In Colaboratory, click the "Connect" button and select "Connect to local runtime...". Enter the URL from the previous step in the dialog that appears and click the "Connect" button. After this, you should now be connected to your local runtime. 

