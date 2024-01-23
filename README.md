
# autogen-test
Testing autogen locally


### Setup a virtual environment
#### Option a: venv
You can create a virtual environment with venv as below:

      $ python3 -m venv pyautogen
      $ source pyautogen/bin/activate

The following command will deactivate the current venv environment:

      $ deactivate

#### Option b: conda
Another option is with Conda. You can install it by following this doc, and then create a virtual environment as below:

      $ conda create -n pyautogen python=3.10  # python 3.10 is recommended as it's stable and not too old
      $ conda activate pyautogen


The following command will deactivate the current conda environment:

      $ conda deactivate




### Make a Conda env

      $ conda create -n autogen python=3.11.4

> # To activate this environment, use                                     
> 
>      $ conda activate autogen
> 
>  To deactivate an active environment, use
> 
>      $ conda deactivate

### Next Install autogen

      $ pip install pyautogen


###### Check version

      $ python --version
> Python 3.11.4





## app.py

```
import autogen

CODE
```

