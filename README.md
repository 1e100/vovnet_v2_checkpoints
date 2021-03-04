# VoVNet V2 checkpoints

This repository contains PyTorch checkpoints for VoVNet V2 implementation in my
other repo: <https://github.com/1e100/vovnet_v2>.
Note that this repository may be deleted and re-created if I need to upload
better checkpoints, so forking or cloning it would be counter-productive.

## Available checkpoints:

 * [VoVNet19](vovnet19.pt): top1 72.508%, top5 90.97%

## Training notes

These checkpoints were trained with
[AdaBelief](https://arxiv.org/abs/2010.07468v2) optimizer, and several cycles
of cosine warm-up/decay schedule. Weight decay was applied only to weights, not
to biases or any other non-weight tensors.
