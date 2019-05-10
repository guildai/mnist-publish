# mnist-intro:train on 2019-05-10 15:28:45

## Attributes

| Name      | Value             |
| -         | -                 |
| ID        | 35cd003c736211e9926ee4a471939b0d      |
| Model     | mnist-intro   |
| Operation | train |
| Status    | completed  |
| Marked    | no  |
| Started   | 2019-05-10 15:28:45 |
| Stopped   | 2019-05-10 15:28:54 |


## Process Info

| Name      | Value             |
| -         | -                 |
| Command     | /usr/bin/python -um guild.op_main intro --datadir data --rundir . --batch-size 100 --epochs 5 --lr 0.5     |
| Exit Status | 0 |


## Files

| File | Size |
| ---- | ---- |
| [data/t10k-images-idx3-ubyte.gz](./data/t10k-images-idx3-ubyte.gz) | 1.6M |
| [data/t10k-labels-idx1-ubyte.gz](./data/t10k-labels-idx1-ubyte.gz) | 4.4K |
| [data/train-images-idx3-ubyte.gz](./data/train-images-idx3-ubyte.gz) | 9.5M |
| [data/train-labels-idx1-ubyte.gz](./data/train-labels-idx1-ubyte.gz) | 28.2K |
| [model/checkpoint](./model/checkpoint) | 69 |
| [model/export.data-00000-of-00001](./model/export.data-00000-of-00001) | 30.7K |
| [model/export.index](./model/export.index) | 159 |
| [model/export.meta](./model/export.meta) | 32.9K |
| [train/events.out.tfevents.1557520128.omaha](./train/events.out.tfevents.1557520128.omaha) | 294.3K |
| [validate/events.out.tfevents.1557520129.omaha](./validate/events.out.tfevents.1557520129.omaha) | 249.2K |


## Source

| File | Size |
| ---- | ---- |
| [.gitignore](.guild/source/.gitignore) | 6 |
| [expert.py](.guild/source/expert.py) | 6.0K |
| [guild.yml](.guild/source/guild.yml) | 2.2K |
| [intro.py](.guild/source/intro.py) | 5.3K |
