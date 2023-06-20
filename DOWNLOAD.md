Dataset **Wind Turbines 5** can be downloaded in Supervisely format:

 [Download](https://assets.supervise.ly/supervisely-supervisely-assets-public/teams_storage/o/z/vU/yDH6R00TXWq2JVlvKMcPdDlvkZYv6oUlHZ00Eapw1E6akF6gmStAcRRUxbGm2rKW3kOGDIV3NxAy6KjoIlZSUDU8tbbhwh8bkxCBNW7z2ENiE2UtRU9vTxnQCRz9.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbines 5', dst_path='~/dtools/datasets/Wind Turbines 5.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/saurabhshahane/wind-turbine-obj-detection/download?datasetVersionNumber=1)