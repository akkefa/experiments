# experiments
Deep learning experiments

## Project Setup
- conda create -n graph python=3.11
- conda activate graph
- conda install -y clang_osx-arm64 clangxx_osx-arm64 gfortran_osx-arm64
- MACOSX_DEPLOYMENT_TARGET=13.4 CC=clang CXX=clang++ python -m pip --no-cache-dir install torch torchvision
- MACOSX_DEPLOYMENT_TARGET=13.4 CC=clang CXX=clang++ python -m pip --no-cache-dir  install  torch-scatter torch-sparse torch-cluster  -f https://data.pyg.org/whl/torch-2.0.1+$\{cpu\}.html
- MACOSX_DEPLOYMENT_TARGET=13.4 CC=clang CXX=clang++ python -m pip --no-cache-dir  install  torch-geometric
