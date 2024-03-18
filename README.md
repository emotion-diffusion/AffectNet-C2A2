# AffectNet-C2A2

This repo contains C2A2 emotion labels for 283900 images from the training split of the AffectNet dataset.

The file [`AffectNet-C2A2.csv`](data/AffectNet-C2A2.csv) contains image emotion annotations in a CSV format:

```
image,valence,arousal,z
0000792211b64f6a59bd2d95fee49eabe6373ec1d88f2285bae2ba9b.jpg,-0.12292647361755371,0.039163004606962204,0.01705397292971611
0000f8a4575c15055a9ee0a72c9aa5bf9ac00558173565802479a287.jpg,0.2109116166830063,0.12904193997383118,0.036105938255786896
```

You need to obtain a copy of the AffectNet data from http://mohammadmahoor.com/affectnet/ separately

The file [`emotions.csv`](data/emotions.csv) also contains 3D points for basic and compound emotions.

## Citation

If you use this data in your paper or find it otherwise useful, please cite us:

```
bibtex goes here
```
