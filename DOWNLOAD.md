Dataset **AgRobTomato** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/t/C/FM/p6Y1aIy2EX2l0YCUSGVoCf2GGIpMvmYnngRl1KqLC3DlKFkXop9kcaH9Xte7cgapWPlT7R9EohCwEflMlTANyIh7sR9Hxj9gVOnV0dOVv2szgfpNoBpPyOSdZYUQ.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='AgRobTomato', dst_path='~/dtools/datasets/AgRobTomato.tar')
```
The data in original format can be 🔗[downloaded here](https://zenodo.org/record/5596799/files/Dataset-Greenhouse_Tomato_AgRob.zip?download=1)