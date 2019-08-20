# SR-with-tinyface
Super resolution with tinyface.This repository only provides test code.

## Usage
Cited in https://github.com/xujinchang/Face-hallucination-with-tiny-images/blob/master

## Trained models
We provide trained models for testing. You can download it from the https://pan.baidu.com/s/1nYqgM4jYJIdPoTYqD-qbVw   
,the password is "vhou" and put it on ./checkpoints/

## Evaluate
$ python eval.py --model=wgan-gp

## Requirements
* python >=3.5
* tensorflow 1.2
* tqdm
