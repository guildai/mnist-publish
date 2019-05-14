
[Published runs](../README.md)




# mnist-intro:train



| ID                | Operation         | Started           | Duration                     | Status           | Label           |
| --                | ---------         | ---------         | --------                     | ------           | -----           |
| eae22cfe | mnist-intro:train | 2019-05-14 16:47:49 | 0:00:08 | completed |  |



## Flags

| Name | Value |
| ---- | ----- |
| batch-size | 100 |
| epochs | 5 |
| lr | 0.5 |





## Scalars

| Key | Step | Value |
| --- | ---- | ----- |
| train#acc | 2700 | 0.980000019073 |
| train#biases/max_1 | 2700 | 1.93821966648 |
| train#biases/mean_1 | 2700 | -4.76837158203e-07 |
| train#biases/min_1 | 2700 | -1.97039663792 |
| train#biases/stddev | 2700 | 0.977700591087 |
| train#loss | 2700 | 0.096349209547 |
| train#sys/gpu0/mem_free | 0 | 1238368256.0 |
| train#sys/gpu0/mem_total | 0 | 2101346304.0 |
| train#sys/gpu0/mem_used | 0 | 862978048.0 |
| train#sys/gpu0/mem_util | 0 | 0.219999998808 |
| train#sys/gpu0/pstate | 0 | 0.0 |
| train#sys/gpu0/temp | 0 | 42.0 |
| train#sys/gpu0/util | 0 | 0.270000010729 |
| train#sys/mem_free | 0 | 16172990464.0 |
| train#sys/mem_total | 0 | 33596555264.0 |
| train#sys/mem_used | 0 | 7087120384.0 |
| train#sys/mem_util | 0 | 0.232999995351 |
| train#sys/swap_free | 0 | 34218176512.0 |
| train#sys/swap_total | 0 | 34218176512.0 |
| train#sys/swap_used | 0 | 0.0 |
| train#sys/swap_util | 0 | 0.0 |
| train#weights/max_1 | 2700 | 1.07689404488 |
| train#weights/mean_1 | 2700 | 1.93410993887e-08 |
| train#weights/min_1 | 2700 | -0.89697510004 |
| train#weights/stddev | 2700 | 0.158874541521 |
| validate#acc | 2700 | 0.923200011253 |
| validate#biases/max_1 | 2700 | 1.93821966648 |
| validate#biases/mean_1 | 2700 | -4.76837158203e-07 |
| validate#biases/min_1 | 2700 | -1.97039663792 |
| validate#biases/stddev | 2700 | 0.977700591087 |
| validate#loss | 2700 | 0.273282289505 |
| validate#sys/gpu0/mem_free | 0 | 1238368256.0 |
| validate#sys/gpu0/mem_total | 0 | 2101346304.0 |
| validate#sys/gpu0/mem_used | 0 | 862978048.0 |
| validate#sys/gpu0/mem_util | 0 | 0.219999998808 |
| validate#sys/gpu0/pstate | 0 | 0.0 |
| validate#sys/gpu0/temp | 0 | 42.0 |
| validate#sys/gpu0/util | 0 | 0.270000010729 |
| validate#sys/mem_free | 0 | 16172990464.0 |
| validate#sys/mem_total | 0 | 33596555264.0 |
| validate#sys/mem_used | 0 | 7087120384.0 |
| validate#sys/mem_util | 0 | 0.232999995351 |
| validate#sys/swap_free | 0 | 34218176512.0 |
| validate#sys/swap_total | 0 | 34218176512.0 |
| validate#sys/swap_used | 0 | 0.0 |
| validate#sys/swap_util | 0 | 0.0 |
| validate#weights/max_1 | 2700 | 1.07689404488 |
| validate#weights/mean_1 | 2700 | 1.93410993887e-08 |
| validate#weights/min_1 | 2700 | -0.89697510004 |
| validate#weights/stddev | 2700 | 0.158874541521 |





## Files

| File | Size | Modified |
| ---- | ---- | -------- |
| [data/t10k-images-idx3-ubyte.gz](./data/t10k-images-idx3-ubyte.gz) | link | 2018-03-17 00:06:55 UTC |
| [data/t10k-labels-idx1-ubyte.gz](./data/t10k-labels-idx1-ubyte.gz) | link | 2018-03-17 00:06:55 UTC |
| [data/train-images-idx3-ubyte.gz](./data/train-images-idx3-ubyte.gz) | link | 2018-03-17 00:06:22 UTC |
| [data/train-labels-idx1-ubyte.gz](./data/train-labels-idx1-ubyte.gz) | link | 2018-11-09 09:49:30 UTC |
| [model/checkpoint](./model/checkpoint) | 69 | 2019-05-14 21:47:57 UTC |
| [model/export.data-00000-of-00001](./model/export.data-00000-of-00001) | 30.7K | 2019-05-14 21:47:57 UTC |
| [model/export.index](./model/export.index) | 159 | 2019-05-14 21:47:57 UTC |
| [model/export.meta](./model/export.meta) | 32.9K | 2019-05-14 21:47:57 UTC |
| [train/events.out.tfevents.1557870473.omaha](./train/events.out.tfevents.1557870473.omaha) | 296.2K | 2019-05-14 21:47:57 UTC |
| [validate/events.out.tfevents.1557870473.omaha](./validate/events.out.tfevents.1557870473.omaha) | 248.9K | 2019-05-14 21:47:57 UTC |





## Images

There are no images for this run.



## Source

| File | Size | Modified |
| ---- | ---- | -------- |
| [.gitignore](.guild/source/.gitignore) | 6 | 2019-05-14 21:47:49 UTC |
| [expert.py](.guild/source/expert.py) | 6.0K | 2019-05-14 21:47:49 UTC |
| [guild.yml](.guild/source/guild.yml) | 2.2K | 2019-05-14 21:47:49 UTC |
| [intro.py](.guild/source/intro.py) | 5.3K | 2019-05-14 21:47:49 UTC |





## Attributes

| Name        | Value                 |
| -           | -                     |
| ID          | eae22cfe769111e9950fc85b764bbf34          |
| Model       | mnist-intro       |
| Operation   | train     |
| Status      | completed      |
| Marked      | no      |
| Started     | 2019-05-14 16:47:49     |
| Stopped     | 2019-05-14 16:47:58     |
| Label       |        |
| Exit Status | 0 |





