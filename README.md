# InvokeAndGo

* This Notebook installs and runs a temporary instance of [InvokeAI](https://github.com/invoke-ai/InvokeAI) with a single click.

* It is publically accessable through a [Localtunnel](https://theboroer.github.io/localtunnel-www/). At the end of the installation the console shows the link and password. After InvokeAI prints out the localhost HTTP address you can open the link to the tunnel and access the installation.

* You need a runtime with [GPU support](https://cloud.google.com/compute/docs/gpus). As of now the installation even runs on the free-of-charge Google Colab T4 runtime!

* If you want to use a specific version of InvokeAI or a different set of models, just edit the configuration section at the beginning of the code. Since Google Colab does [not allow multiline inputs](https://colab.research.google.com/notebooks/forms.ipynb) (for a list of various models) I chose to keep it in pure code.
  * If you want to speed the installation up you can remove the IP-Adapter and ControlNet models and load them as needed using the [model manager page](https://invoke-ai.github.io/InvokeAI/installation/050_INSTALLING_MODELS/#installation-via-the-web-gui) of InvokeAI's UI later.
