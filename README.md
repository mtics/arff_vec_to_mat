# README

> This folder contains some tool code.

## Introduction

- To transfer raw formats to `.mat`, please run `data_read.m`.
  - Before run it, you should change the `loadPath` and `savePath` to where you put raw datasets and where you want to store the transferred datasets.
  - The datasets supported:
    - 'corel5k', 'mirflickr', 'pascal07', 'iaprtc12'
      - supported by `vec*.m`.
    - 'emotions', 'yeast'
      - supported by `arff2mat.m`.
- Use `data_load()` to load your dataset.
- Use `data_merge()` to merge the train set and the test set.
- Use `data_split()` to randomly divide the dataset into train set and test set according to a rate.

## License

Distributed under the Apache License. See 'LICENSE' for more information.

## Contact

Zhiwei Li - @mtics- lizhw[dot]cs[at]outlook[dot]com

Project Link: [mtics/arff_vec_to_mat](https://github.com/mtics/arff_vec_to_mat)
