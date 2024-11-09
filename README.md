# Anonymous
aaai 2025 anonymous code

This repo is an anonymous repository for an AAAI 2025 paper.

## TODO
Since the code is quite messy, we are still organizing it and will gradually open source the code.

## Dataset
We used the [PATS](https://chahuja.com/pats/download.html) dataset; for detailed steps, refer to the data processing of [S2G-MDDiffusion](https://github.com/thuhcsi/S2G-MDDiffusion/tree/master?tab=readme-ov-file#-data-preparation
). 
## Comparison with sota
[comparison1.mp4](https://raw.githubusercontent.com/Anonymous-AAAi-2025/Anonymous/main/src/comparisons1.mp4)


[comparison2.mp4](https://raw.githubusercontent.com/Anonymous-AAAi-2025/Anonymous/main/src/comparisons2.mp4)


### drive image with different people
[cosplay.mp4](https://raw.githubusercontent.com/Anonymous-AAAi-2025/Anonymous/main/src/cosplay.mp4)


## ablation study
[ablation.mp4](https://raw.githubusercontent.com/Anonymous-AAAi-2025/Anonymous/main/src/ablation.mp4)


## Code

Train code:

Coming soon...

### Checkpoints
[ckpts](https://drive.google.com/drive/folders/1f-PR3hkcT6ZHvdTiUBR16Hg-g6uNGvJ-?usp=sharing)

### Test data
[test data](https://drive.google.com/file/d/1Tl2fKMIQLn-qnxjCM_LN5uffK-5HCn0n/view?usp=drive_link)

```
conda create -n cospeech python=3.8
conda create cospeech
conda install pytorch==1.13.1 torchvision==0.14.1 torchaudio==0.13.1 pytorch-cuda=11.6 -c pytorch -c nvidia
pip install -r requirements.txt
```

```
python test.py
```
