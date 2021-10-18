# An elementary introduction to qiskit. 


## [Install Qiskit][install] 

1. Install [Anaconda][anaconda]




**After Anaconda Installation**

For windows user, do the following with Anaconda Prompt.

For macos and Linux, do the following with your shell.

<img width="460" alt="截屏2021-10-14 下午3 11 49" src="https://user-images.githubusercontent.com/28384350/137269205-066bc52f-7bc7-402c-a915-ed2cc4fae4b8.png">




2. Create python 3 environment with name  ENV_NAME (replace by anyname you like)
```console
conda create -n ENV_NAME python=3
```

3. Activate your new environment.
```console
conda activate ENV_NAME
```
4. Install the Qiskit package.
```console
pip install qiskit
```
5. Install Jupyter notebook or Jupyterlab
```console
pip install notebook
```
or 
```console
pip install jupyterlab
```
## Start the jupyterlab with Qiskit environment

For mac or linux, use terminal.
For window, use Anaconda rompt.

1.activate your qiskit environment
```console
conda activate ENV_NAME
```
2.start jupyterlab
```console
jupyter lab
```

You should see jupyterlab in your browser.

## For further reading

### [Qiskit-tutorials][tutorial] with jupyter notebook.

### [Textbook][textbook] about quantum computing from ibm team.

### [Documentation][documentation] about qiskit.


[tutorial]:https://github.com/Qiskit/qiskit-tutorials
[anaconda]:https://www.anaconda.com/products/individual
[textbook]:https://qiskit.org/textbook/preface.html 
[documentation]: https://qiskit.org/documentation/
[install]: https://qiskit.org/documentation/getting_started.html
