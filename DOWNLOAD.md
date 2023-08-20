Dataset **Accurate Drone Shapes** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/A/q/4W/eoSej7LGBz0uPDFtgaceDpyWoYNDohVAgpzJv07nBS4ScI1MPiVTdCqDHDGUqpwnJRo6P1jai5M9SoRoGFBOQQgbdtDn0zDqSm3D4oTf9WBk4V5DaSTEY6KpKKXD.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='Accurate Drone Shapes', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be [downloaded here](https://www.kaggle.com/datasets/metavision/accurate-drone-shapessegmentation/download?datasetVersionNumber=2).