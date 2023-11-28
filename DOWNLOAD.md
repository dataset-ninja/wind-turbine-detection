Dataset **Wind Turbine Detection (by Saurabh Shahane)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://www.dropbox.com/scl/fi/79ekf7gmmmj0en4nskm3v/wind-turbine-detection-by-saurabh-shahane-DatasetNinja.tar?rlkey=5z36cexzj9z6jxn9ys2wl86yd&dl=1)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbine Detection (by Saurabh Shahane)', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/saurabhshahane/wind-turbine-obj-detection/download?datasetVersionNumber=1).