The Seattle Demokit
=======

 The demokit packages up a set of tools for Seattle users and developers that allow you to

* Access VMs on remote machines, for example such assigned to you by the  Seattle Clearinghouse
* Run RepyV2 code on your local machine, using a supplied restrictions file, and thusly
* Develop and debug Repy programs locally. 

To build the demokit,
```
git clone https://github.com/SeattleTestbed/demokit.git
cd demokit
# Create build target folder first
mkdir seattle_demokit
cd scripts
python initialize.py
python build.py ../seattle_demokit

# Now package the build for download
cd ..
zip -r seattle_demokit ./seattle_demokit
```

See [the Seattle wiki](https://seattle.poly.edu/wiki/BuildDemokit) for build details.
