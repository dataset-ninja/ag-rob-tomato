Dataset **AgRobTomato Dataset** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogInMzOi8vc3VwZXJ2aXNlbHktZGF0YXNldHMvMTMzOF9BZ1JvYlRvbWF0byBEYXRhc2V0L2Fncm9idG9tYXRvLWRhdGFzZXQtRGF0YXNldE5pbmphLnRhciIsICJzaWciOiAiNGhId0NJTDh6Z1dzSmROc0w2R0NFeXM0ZzZDSjZBMTZmajFUekpOTS9Zaz0ifQ==?response-content-disposition=attachment%3B%20filename%3D%22agrobtomato-dataset-DatasetNinja.tar%22)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='AgRobTomato Dataset', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://zenodo.org/record/5596799/files/Dataset-Greenhouse_Tomato_AgRob.zip?download=1).