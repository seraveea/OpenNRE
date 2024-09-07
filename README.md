This is a fork version of OpenNRE. Complete readme please refer to [original readme](https://github.com/thunlp/OpenNRE/blob/master/README.md)
```bash
git clone https://github.com/seraveea/OpenNRE.git
```
About requirements, it's ok to use torch 2.0 and above.
Then run
```
python setup.py install
```
## Modification
1. To make it compatible with Torch 2.0, change ```cuda()``` to ```to(device)```.
2. Add ```prediction``` function in framework class.
