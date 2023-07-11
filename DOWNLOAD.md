Dataset **Accurate drone shapes** can be downloaded in Supervisely format:

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/H/K/Jp/szwgRdnTdU1pRmIkXYPT2f02InNyps71Q2CHzxDH3BcuL9ktz8j1pq8e6PN7K7e3J3pFbFyOCbRfhR2A1LCTxZWdyEpUMgcvbLhLbO3DAR6lvdSe0r6KPiu9vCOM.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Accurate drone shapes', dst_path='~/dtools/datasets/Accurate drone shapes.tar')
```
The data in original format can be 🔗[downloaded here](https://www.kaggle.com/datasets/metavision/accurate-drone-shapessegmentation/download?datasetVersionNumber=2)