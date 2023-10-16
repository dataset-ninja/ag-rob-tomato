Dataset **AgRobTomato** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/l/8/UQ/gcWzb9d1Z32lxp30PfVTuwyxetJsEvQ9CcClvlNndofQUvS5PqhbO22RNM7INlFCba13cESh4KbgHL4L7V5ZmksW43xtd2SQyGEEk51y77JeE0jAcLbI52CSvUuX.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='AgRobTomato', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://zenodo.org/record/5596799/files/Dataset-Greenhouse_Tomato_AgRob.zip?download=1).