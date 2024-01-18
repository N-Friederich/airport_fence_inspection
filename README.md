<div style="text-align: center;">
   <table style="border-style: hidden!important;">
      <tr>
         <td>
            <img src="https://www.iosb.fraunhofer.de/content/dam/iosb/Logo_IOSB.jpg"  width="1850.11"/>
         </td>
         <td>
            <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/3a/Logo_KIT.svg/1024px-Logo_KIT.svg.png" width="1024" />
         </td>
      </tr>
   </table>
</div>

# <div align="center"> Fence Inspection at Airports Using Object Detection </div> </br> <div align="center"> WACV Paper 2024 </div>

This repository contains the data for the paper "Fence Inspection at Airports Using Object Detection" from the "Winter Conference of Applied Computer Vision 2024" (WACV '24).

1. Training weights & metadata of the best models:
   - YOLOv5 from section 4.5 with automated hyperparameter tuning: [Zenodo](https://zenodo.org/records/10431213)
   - YOLOv5 from section 4.8 with a higher image resolution of 624×960 (vs. 512×768 before): [Zenodo](https://zenodo.org/records/10459934)

2. Training weights & metadata of the best MMDetection models <a href="https://openaccess.thecvf.com/content/ICCV2021/papers/Feng_TOOD_Task-Aligned_One-Stage_Object_Detection_ICCV_2021_paper.pdf">TOOD</a>  and <a href="https://arxiv.org/pdf/2008.13367.pdf">VFNet</a>:
   - TOOD from section 4.6 with a ConvNeXt-T backbone: [Zenodo](https://zenodo.org/records/10459965)
   - VFNet from section 4.6 with a Res2Net backbone: [Zenodo](https://zenodo.org/records/10469934)
