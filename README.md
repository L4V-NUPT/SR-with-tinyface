# SR-with-tinyface
Super resolution with tinyface/n
This repository only provides test code.

Usage
cited in https://github.com/xujinchang/Face-hallucination-with-tiny-images/blob/master

Trained models
We provide trained models for testing,You can download it from the HTTP, and put it on ./checkpoints/

Evaluate
$ python eval.py --help
usage: eval.py [-h] --model MODEL [--name NAME]

optional arguments:
  -h, --help     show this help message and exit
  --model MODEL  DCGAN / LSGAN / WGAN / WGAN-GP / EBGAN / BEGAN / DRAGAN
  --name NAME    default: name=model
  
