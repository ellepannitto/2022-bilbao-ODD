## Exercise 2: Editable Installation

#### Goal

See advantages of using brewing package as an editable installation.

#### Tasks

1. Check which packages are installed currently
   `> pip freeze`

2. install the brewing package as an editable installation
   `> pip install -e <path-to-repository>` 
   
       or go into the folder above `brewing` and call
   
   `> pip install -e .` 

3. check which packages are installed now
   `> pip freeze`
   What changed?

4. try running the `example_usage_X.py` files. Do they run without errors and if no, can you make them all work simultaneously?
   
   1. `example_usage_outside_package.py`
   2. `scripts/example_usage_different_folder.py`
   3. `brewing/example_usage_within_package.py`
