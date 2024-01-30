# G2LP
Wire-removal Video Dataset in G2LP-Net: Global to Local Progressive Video Inpainting Network
# Wire-removal Video Dataset
The WRV dataset has been specifically curated for the challenges of video inpainting in irregularly slender regions. It encompasses 150 video clips that are extracted from movies and TV series. What sets the WRV dataset apart is its real-world scenarios where video frames may not have fixed foregrounds, or might even showcase multiple dynamic foregrounds such as action sequences involving several individuals.

A distinct feature of this dataset is the naturally occurring masks due to dynamic thin wires and small auxiliary props commonly used in martial arts stunts. This makes the dataset particularly representative of genuine challenges found in film post-production.

The primary challenge with the WRV dataset lies in effectively utilizing contextual information. Due to the irregular and slender nature of the to-be-inpainted regions, leveraging surrounding contextual details is paramount to achieving authentic inpainting results.

## Data Examples

Below are some examples from the dataset. Each example includes an image and its corresponding label.

<div style="display: flex; justify-content: space-between;">
  
  <div style="flex: 1; text-align: center; padding: 5px; max-width: 100%;">
    <img src="example/8m56s-GT/00000.png" style="width: 50%; height: auto;">
    <p>Example Image 1: Original Image</p>
  </div>
  
  <div style="flex: 1; text-align: center; padding: 5px; max-width: 100%;">
    <img src="example/8m56s-MASK/0001.png" style="width: 50%; height: auto;">
    <p>Example Image 2: Mask</p>
  </div>
  
  <div style="flex: 1; text-align: center; padding: 5px; max-width: 100%;">
    <img src="example/8m56s-IN/0001.png" style="width:50%; height: auto;">
    <p>Example Image 3: Artificially Restored Image</p>
  </div>
  
</div>




## Wire-removal Dataset Link (480P version)

[Baidu Disk](https://pan.baidu.com/s/1aKNL7l1tr_WPkyrfxAXqxw?pwd=xc17)

[Google Drive](https://drive.google.com/file/d/1qxRGsgI-qku8bJ13jKpbY6cJGc4fDlpu/view?usp=drive_link)

## Wire-removal Dataset Link(4K version)

Waiting for updates ......

## Citation


If this research benefits your work or involves the use of this dataset, please consider citing the following paper:
   ```bibtex
@article{ji2022g2lp,
title={G2LP-Net: Global to Local Progressive Video Inpainting Network},
author={Ji, Zhong and Hou, Jiacheng and Su, Yimu and Pang, Yanwei and Li, Xuelong},
journal={IEEE Transactions on Circuits and Systems for Video Technology},
volume={33},
number={3},
pages={1082--1092},
year={2022},
publisher={IEEE}
}
```
## License

This project is licensed under the [MIT License](LICENSE). Please refer to the LICENSE file for detailed terms.
