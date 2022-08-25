# Compact Semantic Segmentation and Depth Estimation with Multi-task Learning

Implementasi program untuk webinar yang diselenggarakan oleh BISA AI dengan judul: \
Compact Semantic Segmentation and Depth Estimation with Multi-task Learning


## Informasi webinar: 
[[Link]](https://tampil.id/event/detail/VFdwWk1FNUJQVDA9) \
<img src="docs/event.jpg" width="400">


## Step:
1. Download dan extract set dataset [cityscapes](https://www.cityscapes-dataset.com/) 
    - leftImg8bit_trainvaltest.zip (11GB)
    - gtFine_trainvaltest.zip (241MB)
    - disparity_trainvaltest.zip (3.5GB)
2. Run jupyter notebook dan buka mtl_seg_dep.ipynb
3. Jalankan program sesuai instruksi yang tertulis di notebook
4. Trained model untuk inference dapat didownload [di sini](https://drive.google.com/drive/folders/1Jft1n9vXaNHllUg5JDKDCYX9BJTYza0D?usp=sharing)


## Other:
1. Algoritma MGN (Modified Gradient Normalization) dapat digunakan untuk menyeimbangkan proses learning pada kedua task. Pelajari lebih lanjut di:
    - O. Natan and J. Miura, “Towards Compact Autonomous Driving Perception with Balanced Learning and Multi-sensor Fusion,” IEEE Trans. Intelligent Transportation Systems, 2022. [[paper]](https://doi.org/10.1109/TITS.2022.3149370) [[code]](https://github.com/oskarnatan/compact-perception)
    - O. Natan and J. Miura, “End-to-end Autonomous Driving with Semantic Depth Cloud Mapping and Multi-agent,” IEEE Trans. Intelligent Vehicles, 2022. [[paper]](https://doi.org/10.1109/TIV.2022.3185303) [[code]](https://github.com/oskarnatan/end-to-end-driving)