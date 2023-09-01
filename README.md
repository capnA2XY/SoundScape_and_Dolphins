# SoundScape_and_Dolphins
SoundScape and Dolphins AI Machine Learning model for classification, detector

To avoid Python version chaos:
//////////////////////////////////////////////////////
conda create -n tf-gpu python=3.9.15

conda activate tf-gpu

pip install librosa=0.9.2
pip install pandas=1.4.2
pip install matplotlib=3.5.3
pip install tensorflow=2.6.0
#etc.....

/////////////////////////////////////////////////////
(tf-gpu) PS C:\Users\user> python --version
Python 3.9.15




(tf-gpu) PS C:\Users\user> pip list
Package                 Version
----------------------- --------------
absl-py                 1.3.0
aiohttp                 3.8.3
aiosignal               1.2.0
anyio                   3.5.0
appdirs                 1.4.4
argon2-cffi             21.3.0
argon2-cffi-bindings    21.2.0
astor                   0.8.1
asttokens               2.0.5
astunparse              1.6.3
async-timeout           4.0.2
attrs                   22.1.0
audioread               3.0.0
Babel                   2.9.1
backcall                0.2.0
beautifulsoup4          4.11.1
bleach                  4.1.0
blinker                 1.4
Bottleneck              1.3.4
brotlipy                0.7.0
cachetools              4.2.2
certifi                 2022.12.7
cffi                    1.15.1
charset-normalizer      2.0.4
clang                   5.0
click                   8.0.4
cloudpickle             2.0.0
colorama                0.4.5
cryptography            38.0.1
cycler                  0.11.0
cytoolz                 0.12.0
dask                    2022.7.0
debugpy                 1.5.1
decorator               5.1.1
defusedxml              0.7.1
entrypoints             0.4
exceptiongroup          1.0.4
executing               0.8.3
fastjsonschema          2.16.2
filelock                3.8.2
flatbuffers             20210226132247
flit_core               3.6.0
fonttools               4.25.0
frozenlist              1.3.3
fsspec                  2022.11.0
future                  0.18.2
gast                    0.4.0
gdown                   4.6.0
google-auth             2.6.0
google-auth-oauthlib    0.4.1
google-pasta            0.2.0
grpcio                  1.42.0
h5py                    3.7.0
hampel                  0.0.5
huggingface-hub         0.10.1
idna                    3.4
imagecodecs             2021.8.26
imageio                 2.19.3
importlib-metadata      4.11.3
iniconfig               1.1.1
ipykernel               6.15.2
ipython                 8.6.0
ipython-genutils        0.2.0
jedi                    0.18.1
Jinja2                  3.1.2
joblib                  1.2.0
json5                   0.9.6
jsonschema              4.16.0
jupyter_client          7.4.7
jupyter_core            4.11.2
jupyter-server          1.18.1
jupyterlab              3.5.0
jupyterlab-pygments     0.1.2
jupyterlab_server       2.16.3
keras                   2.6.0
Keras-Preprocessing     1.1.2
kiwisolver              1.4.4
librosa                 0.9.2
littleutils             0.2.2
llvmlite                0.39.1
locket                  1.0.0
lxml                    4.9.1
Markdown                3.3.4
MarkupSafe              2.1.1
matplotlib              3.5.3
matplotlib-inline       0.1.6
mistune                 0.8.4
mkl-fft                 1.3.1
mkl-random              1.2.2
mkl-service             2.4.0
multidict               6.0.2
munkres                 1.1.4
nbclassic               0.4.8
nbclient                0.5.13
nbconvert               6.5.4
nbformat                5.7.0
nest-asyncio            1.5.5
networkx                2.8.4
notebook                6.5.2
notebook_shim           0.2.2
numba                   0.56.4
numexpr                 2.8.1
numpy                   1.23.4
nvidia-smi              0.1.3
oauthlib                3.2.1
opt-einsum              3.3.0
packaging               21.3
pandas                  1.4.2
pandocfilters           1.5.0
parso                   0.8.3
partd                   1.2.0
pickleshare             0.7.5
Pillow                  9.2.0
pip                     22.3.1
pluggy                  1.0.0
pooch                   1.6.0
prometheus-client       0.14.1
prompt-toolkit          3.0.20
protobuf                3.20.3
psutil                  5.9.0
pure-eval               0.2.2
pyasn1                  0.4.8
pyasn1-modules          0.2.8
pycparser               2.21
Pygments                2.11.2
PyJWT                   2.4.0
pyOpenSSL               22.0.0
pyparsing               3.0.9
pyrsistent              0.18.0
PySocks                 1.7.1
pytest                  7.2.0
python-dateutil         2.8.2
pytz                    2022.1
PyWavelets              1.3.0
pywin32                 305.1
pywinpty                2.0.2
PyYAML                  6.0
pyzmq                   23.2.0
regex                   2022.7.9
requests                2.28.1
requests-oauthlib       1.3.0
resampy                 0.4.2
rfc3986                 1.5.0
rsa                     4.7.2
scikit-image            0.19.3
scikit-learn            1.1.3
scipy                   1.7.3
seaborn                 0.12.1
Send2Trash              1.8.0
setuptools              65.5.0
sgmllib3k               1.0.0
six                     1.16.0
sniffio                 1.2.0
sorcery                 0.2.2
soundfile               0.11.0
soupsieve               2.3.2.post1
stack-data              0.2.0
tensorboard             2.6.0
tensorboard-data-server 0.6.0
tensorboard-plugin-wit  1.8.1
tensorflow              2.6.0
tensorflow-estimator    2.6.0
termcolor               2.1.0
terminado               0.13.1
threadpoolctl           3.1.0
tifffile                2021.7.2
tinycss2                1.2.1
tokenizers              0.11.4
tomli                   2.0.1
toolz                   0.12.0
torch                   1.12.1
tornado                 6.2
tqdm                    4.64.1
traitlets               5.1.1
transformers            4.24.0
transforms              0.1
typing_extensions       4.4.0
urllib3                 1.26.13
wcwidth                 0.2.5
webencodings            0.5.1
websocket-client        0.58.0
Werkzeug                2.0.3
wheel                   0.35.1
win-inet-pton           1.1.0
wincertstore            0.2
wrapt                   1.14.1
yarl                    1.8.1
zipp                    3.8.0
(tf-gpu) PS C:\Users\user>
