# DL-On-shelf-Books-Recognition
Library On-shelf Books Segmentation and Recognition based on Deep Visual Features.

On-shelf book segmentation and recognition are crucial steps in library inventory management and daily operation. In this paper, a detailed investigation of related work is conducted. RFID and barcode-based solutions suffer from expensive hardware facilities and long-term maintenance. Digital Image processing and OCR techniques are flawed due to a lack of accuracy and robustness. On this basis, we propose a visual and non-character system utilizing deep learning methods to accomplish on-shelf book segmentation and recognition tasks. Firstly, book spine masks are extracted from the image of on-shelf books by instance segmentation model, followed by affine transformation to rectangle images. Secondly, a spine feature encoder is trained to learn the deep visual features of spine images. Finally, the book inventory search space is constructed and the similarity metric between spine visual representations is calculated to recognize the target book identity. To train the models we collect high-resolution datasets of 10k-level and develop a data annotation software accordingly. For validation, we design simulated scenarios of recognizing 3.6k IDs from 5.6k book spines and achieve a best top1 accuracy of 99.18\% and top5 accuracy of 99.91\%. Furthermore, we develop a prototype of a mobile library management robot with embedded edge intelligence. It can automatically perform on-shelf book image capturing, spine segmentation and recognition, and target book grasping workflow.

The BookID dataset, book identity annotation software and the book screen tools can be downloaded from the link below:

链接：https://pan.baidu.com/s/1yqjDG56RO1PMfSMXD0Jl3g?pwd=mvar 
提取码：mvar
