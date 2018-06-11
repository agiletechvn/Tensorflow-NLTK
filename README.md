## Setup environment

```
# start the deployment
yarn start
# go into bash
yarn bash
# install requirements
python -m pip install -r requirements.txt
# test the installation
python TF_basics.py
>>Tensor("Mul:0", shape=(), dtype=int32)
>>30
# stop the deployment
yarn stop
```

## Build the data model

```
python TF_own_data_model.py
```

## Train the model

```
python TF_train_model.py
```

