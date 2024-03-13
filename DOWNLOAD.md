Dataset **KITTI MOTS** can be downloaded in [Supervisely format](https://developer.supervisely.com/api-references/supervisely-annotation-json-format):

 [Download](https://assets.supervisely.com/supervisely-supervisely-assets-public/teams_storage/x/M/mB/YpDEQ6WNTMWXXQjg2oLU0quIumOOSDMl78LwaB0K6bdwj1T6UEaD7UBLicQFtw8a3BMvBHWIEFd0Da2mSKaUPZOKkMnhrExmOBZ9mEtw725TPecWF2E7j4vb2D5M.tar)

As an alternative, it can be downloaded with *dataset-tools* package:
``` bash
pip install --upgrade dataset-tools
```

... using following python code:
``` python
import dataset_tools as dtools

dtools.download(dataset='KITTI MOTS', dst_dir='~/dataset-ninja/')
```
Make sure not to overlook the [python code example](https://developer.supervisely.com/getting-started/python-sdk-tutorials/iterate-over-a-local-project) available on the Supervisely Developer Portal. It will give you a clear idea of how to effortlessly work with the downloaded dataset.

The data in original format can be downloaded here:

- [Images](http://www.cvlibs.net/download.php?file=data_tracking_image_2.zip)
- [Annotations in png format (train+val)](https://www.vision.rwth-aachen.de/media/resource_files/instances.zip)
- [Annotations in txt format (train+val)](https://www.vision.rwth-aachen.de/media/resource_files/instances_txt.zip)
