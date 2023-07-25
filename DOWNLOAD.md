Dataset **Wind Turbine Detection (by Saurabh Shahane)** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/e/7/in/J6oIiWOtf540k5x058KQW6AWhNyADtgIclRC7FKy1SusaTALVPSMtUf9ITjKRIvTtOj6tLradlgf1UnpneiIXzLgVfBfH2RhFHgYDREdTIjthHzxW2dRKoaDELSO.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Wind Turbine Detection (by Saurabh Shahane)', dst_path='~/dtools/datasets/Wind Turbine Detection (by Saurabh Shahane).tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/saurabhshahane/wind-turbine-obj-detection/download?datasetVersionNumber=1)