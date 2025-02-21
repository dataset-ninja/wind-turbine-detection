Dataset **Wind Turbine Detection (by Saurabh Shahane)** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/remote/eyJsaW5rIjogImZzOi8vYXNzZXRzLzExMDZfV2luZCBUdXJiaW5lIERldGVjdGlvbiAoYnkgU2F1cmFiaCBTaGFoYW5lKS93aW5kLXR1cmJpbmUtZGV0ZWN0aW9uLShieS1zYXVyYWJoLXNoYWhhbmUpLURhdGFzZXROaW5qYS50YXIiLCAic2lnIjogIkhtNmI2VC9aYWR6YzBRNTAwQ0p5QTF0Y1lzQ2ljTGo2Z2MwZCtEU0hLbWM9In0=)

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