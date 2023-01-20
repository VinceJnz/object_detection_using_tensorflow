# Notes

## running ??? - Tensorflow has no attribute gfile


https://www.datasciencelearner.com/attributeerror-module-tensorflow-has-no-attribute-gfile-solved/#:~:text=Attributeerror%20module%20TensorFlow%20has%20no%20attribute%20gfile%20error%20occurs%20because,using%20a%20new%20package%20structure.


## Protocol Buffers

<https://developers.google.com/protocol-buffers/>



## opencv-python-headless

pip install opencv-python-headless==3.4.18.65



## running set up

(tf2_gpu) D:\Users\Vince\Documents\GitHub\object_detection_using_tensorflow\Tensorflow\models\research>python -m pip install .

ERROR: pip's dependency resolver does not currently take into account all the packages that are installed. This behaviour is the source of the following dependency conflicts.
tensorflow-intel 2.11.0 requires keras<2.12,>=2.11.0, but you have keras 2.10.0 which is incompatible.
tensorflow-intel 2.11.0 requires tensorboard<2.12,>=2.11, but you have tensorboard 2.10.1 which is incompatible.
tensorflow-intel 2.11.0 requires tensorflow-estimator<2.12,>=2.11.0, but you have tensorflow-estimator 2.10.0 which is incompatible.


### Shouldn't have run this in the standard cmd line

```cmd
D:\Users\Vince\Documents\GitHub\object_detection_using_tensorflow\Tensorflow\models\research>python -m pip install .
Looking in indexes: https://pypi.org/simple, https://pypi.ngc.nvidia.com
Processing d:\users\vince\documents\github\object_detection_using_tensorflow\tensorflow\models\research
  Preparing metadata (setup.py) ... done
Collecting avro-python3
  Downloading avro-python3-1.10.2.tar.gz (38 kB)
  Preparing metadata (setup.py) ... done
Collecting apache-beam
  Downloading apache_beam-2.44.0-cp310-cp310-win_amd64.whl (4.6 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 4.6/4.6 MB 10.8 MB/s eta 0:00:00
Collecting pillow
  Downloading Pillow-9.4.0-cp310-cp310-win_amd64.whl (2.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.5/2.5 MB 11.3 MB/s eta 0:00:00
Collecting lxml
  Downloading lxml-4.9.2-cp310-cp310-win_amd64.whl (3.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 3.8/3.8 MB 11.5 MB/s eta 0:00:00
Collecting matplotlib
  Downloading matplotlib-3.6.3-cp310-cp310-win_amd64.whl (7.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 7.2/7.2 MB 11.8 MB/s eta 0:00:00
Collecting Cython
  Downloading Cython-0.29.33-py2.py3-none-any.whl (987 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 987.3/987.3 kB 12.5 MB/s eta 0:00:00
Collecting contextlib2
  Downloading contextlib2-21.6.0-py2.py3-none-any.whl (13 kB)
Collecting tf-slim
  Downloading tf_slim-1.1.0-py2.py3-none-any.whl (352 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 352.1/352.1 kB 22.8 MB/s eta 0:00:00
Collecting six
  Downloading six-1.16.0-py2.py3-none-any.whl (11 kB)
Collecting pycocotools
  Downloading pycocotools-2.0.6.tar.gz (24 kB)
  Installing build dependencies ... done
  Getting requirements to build wheel ... done
  Preparing metadata (pyproject.toml) ... done
Collecting lvis
  Downloading lvis-0.5.3-py3-none-any.whl (14 kB)
Collecting scipy
  Downloading scipy-1.10.0-cp310-cp310-win_amd64.whl (42.5 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 42.5/42.5 MB 11.5 MB/s eta 0:00:00
Collecting pandas
  Downloading pandas-1.5.3-cp310-cp310-win_amd64.whl (10.4 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.4/10.4 MB 11.5 MB/s eta 0:00:00
Collecting tf-models-official>=2.5.1
  Downloading tf_models_official-2.11.3-py2.py3-none-any.whl (2.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 1.2 MB/s eta 0:00:00
Collecting tensorflow_io
  Downloading tensorflow_io-0.29.0-cp310-cp310-win_amd64.whl (22.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 22.9/22.9 MB 9.8 MB/s eta 0:00:00
Collecting keras
  Downloading keras-2.11.0-py2.py3-none-any.whl (1.7 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 1.7/1.7 MB 12.0 MB/s eta 0:00:00
Collecting pyparsing==2.4.7
  Downloading pyparsing-2.4.7-py2.py3-none-any.whl (67 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 67.8/67.8 kB ? eta 0:00:00
Collecting sacrebleu<=2.2.0
  Downloading sacrebleu-2.2.0-py3-none-any.whl (116 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 116.6/116.6 kB 7.1 MB/s eta 0:00:00
Collecting numpy>=1.17
  Downloading numpy-1.24.1-cp310-cp310-win_amd64.whl (14.8 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 14.8/14.8 MB 11.7 MB/s eta 0:00:00
Collecting portalocker
  Downloading portalocker-2.7.0-py2.py3-none-any.whl (15 kB)
Collecting tabulate>=0.8.9
  Downloading tabulate-0.9.0-py3-none-any.whl (35 kB)
Collecting colorama
  Downloading colorama-0.4.6-py2.py3-none-any.whl (25 kB)
Collecting regex
  Downloading regex-2022.10.31-cp310-cp310-win_amd64.whl (267 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 267.7/267.7 kB 16.1 MB/s eta 0:00:00
Collecting tensorflow~=2.11.0
  Downloading tensorflow-2.11.0-cp310-cp310-win_amd64.whl (1.9 kB)
Collecting opencv-python-headless
  Downloading opencv_python_headless-4.7.0.68-cp37-abi3-win_amd64.whl (38.1 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 38.1/38.1 MB 11.7 MB/s eta 0:00:00
Collecting py-cpuinfo>=3.3.0
  Downloading py_cpuinfo-9.0.0-py3-none-any.whl (22 kB)
Collecting oauth2client
  Downloading oauth2client-4.1.3-py2.py3-none-any.whl (98 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 98.2/98.2 kB ? eta 0:00:00
Collecting immutabledict
  Downloading immutabledict-2.2.3-py3-none-any.whl (4.0 kB)
Collecting tensorflow-hub>=0.6.0
  Downloading tensorflow_hub-0.12.0-py2.py3-none-any.whl (108 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 108.8/108.8 kB ? eta 0:00:00
Collecting google-api-python-client>=1.6.7
  Downloading google_api_python_client-2.73.0-py2.py3-none-any.whl (10.9 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 10.9/10.9 MB 11.5 MB/s eta 0:00:00
Collecting psutil>=5.4.3
  Downloading psutil-5.9.4-cp36-abi3-win_amd64.whl (252 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 252.5/252.5 kB 15.1 MB/s eta 0:00:00
Collecting seqeval
  Downloading seqeval-1.2.2.tar.gz (43 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 43.6/43.6 kB ? eta 0:00:00
  Preparing metadata (setup.py) ... done
Collecting tensorflow-addons
  Downloading tensorflow_addons-0.19.0-cp310-cp310-win_amd64.whl (732 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 732.4/732.4 kB 11.6 MB/s eta 0:00:00
Collecting tensorflow-model-optimization>=0.4.1
  Downloading tensorflow_model_optimization-0.7.3-py2.py3-none-any.whl (238 kB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 238.9/238.9 kB 15.2 MB/s eta 0:00:00
Collecting tensorflow-datasets
  Downloading tensorflow_datasets-4.8.2-py3-none-any.whl (5.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 5.3/5.3 MB 11.8 MB/s eta 0:00:00
Collecting tf-models-official>=2.5.1
  Downloading tf_models_official-2.11.2-py2.py3-none-any.whl (2.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 11.4 MB/s eta 0:00:00
  Downloading tf_models_official-2.11.0-py2.py3-none-any.whl (2.3 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.3/2.3 MB 12.4 MB/s eta 0:00:00
  Downloading tf_models_official-2.10.1-py2.py3-none-any.whl (2.2 MB)
     ━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 2.2/2.2 MB 11.6 MB/s eta 0:00:00
Collecting tensorflow~=2.10.0
  Downloading tensorflow-2.10.1-cp310-cp310-win_amd64.whl (455.9 MB)
     ━━━━━━╺━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━ 70.0/455.9 MB 8.7 MB/s eta 0:00:45
ERROR: Operation cancelled by user

D:\Users\Vince\Documents\GitHub\object_detection_using_tensorflow\Tensorflow\models\research>python -m pip uninstall .
WARNING: Invalid requirement: '.' ignored - the uninstall command expects named requirements.
ERROR: You must give at least one requirement to uninstall (see "pip help uninstall")

D:\Users\Vince\Documents\GitHub\object_detection_using_tensorflow\Tensorflow\models\research>python -m pip uninstall .
```






# convert to TF record format
!python {files['TF_RECORD_SCRIPT']} -x {os.path.join(paths['IMAGE_PATH'], 'train')} -l {files['LABELMAP']} -o {os.path.join(paths['ANNOTATION_PATH'], 'train.record')} 
!python {files['TF_RECORD_SCRIPT']} -x {os.path.join(paths['IMAGE_PATH'], 'test')} -l {files['LABELMAP']} -o {os.path.join(paths['ANNOTATION_PATH'], 'test.record')} 


```python
Traceback (most recent call last):
  File "D:\Users\Vince\Documents\GitHub\object_detection_using_tensorflow\Tensorflow\scripts\generate_tfrecord.py", line 29, in <module>
    from object_detection.utils import dataset_util, label_map_util
  File "C:\Users\Vince\miniconda3\envs\tf2_gpu\lib\site-packages\object_detection\utils\label_map_util.py", line 29, in <module>
    from object_detection.protos import string_int_label_map_pb2
ImportError: cannot import name 'string_int_label_map_pb2' from 'object_detection.protos' (C:\Users\Vince\miniconda3\envs\tf2_gpu\lib\site-packages\object_detection\protos\__init__.py)
Traceback (most recent call last):
  File "D:\Users\Vince\Documents\GitHub\object_detection_using_tensorflow\Tensorflow\scripts\generate_tfrecord.py", line 29, in <module>
    from object_detection.utils import dataset_util, label_map_util
  File "C:\Users\Vince\miniconda3\envs\tf2_gpu\lib\site-packages\object_detection\utils\label_map_util.py", line 29, in <module>
    from object_detection.protos import string_int_label_map_pb2
ImportError: cannot import name 'string_int_label_map_pb2' from 'object_detection.protos' (C:\Users\Vince\miniconda3\envs\tf2_gpu\lib\site-packages\object_detection\protos\__init__.py)
```
