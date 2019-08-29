# Awesome-CV-bibfiles
A collection of bibfiles related to computer vision for efficiency

## Highlights
- Bibfiles are organized by category
- Short name of the method is used as the index of reference item such as `RCNN` rather than `girshick14CVPR` for efficient retrieval

## Contributing
Please feel free to send [pull requests](https://github.com/hkzhang95/Awesome-CV-bibfiles/pulls). You can follow the [templates](#templates) of the reference item for more efficient cooperations.

## Table of Contents
- [Image Classification](bibfiles/image-classification.bib)
- [2D General Object Detection](bibfiles/2d-object-detection.bib)
- [Human Detection](bibfiles/human-detection.bib)

## Templates
- Recommended indentation: **4 spaces**
- Drop one line between reference items

### Conference paper
```
@inproceedings{index_name,
    author = {A and B and C},
    title = {title},
    booktitle = {abbreviation form of the conference, such as CVPR and ICCV},
    year = {xxxx}
}
```

Specially, for the Arxiv version:
```
@article{index_name,
    author = {A and B and C},
    title = {title},
    journal = {arXiv:xxxx.xxxxx},
    year = {xxxx}
}
```

### Journal paper
```
@article{index_name, 
    author = {A and B and C}, 
    title = {title},
    volume = {volume},
    number = {number},
    pages = {start-end},
    journal = {Abbreviation form of the journal, such as IJCV and T-PAMI},
    year = {xxxx}
}
```
