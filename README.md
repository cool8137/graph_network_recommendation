# graph_network_recommendation
Using Graph Networks to Recommend Books to Customers

## Folder structure
* `datasets`: contains the required input data.
* `notebooks`: the notebooks with the codes for this projects.
* `outputs`: outputs generated by the notebooks.

## Steps to run notebooks

* Install:
  * On mac run `make install-mac` to install required programs.
  * On Linux run `make install-linux`. Note: linus installation has not been tested.
* Build virtual environment:
  * Run `make build` to build the virtual environment.
* Activate virtul environment:
  * Run `source .venv/bin/activate` to activate the virtual environment.
* Use this virtual environment to run the notebooks.
  * To open notebooks on browser, run `jupyter notebook`
  * To run on IDE, or use the `.venv/bin/python` kernel.
