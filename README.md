# MTNet: Learning Modality-aware Representation with Transformer for RGBT Tracking(IEEE International Conference on Multimedia and Expo (ICME23))
This is the results of the ICME2023 paper "MTNet: Learning Modality-aware Representation with Transformer for RGBT Tracking".
![image](pipeline.png)

The ability to learn robust multi-modality representationhas played a critical role in the development ofRGBT tracking. However, the regular fusion paradigm and the invariable tracking template remain restrictive to the feature interaction. In this paper, we propose a modality-aware tracker based on transformer, termed MTNet. Specifically, a modalityaware network is presented to explore modality-specific cues, which contains both channel aggregation and distribution module (CADM) and spatial similarity perception module (SSPM). A transformer fusion network is then applied to capturing global dependencies to reinforce instance representations. To estimate the precise location and tackle the challenges, such as scale variation and deformation, we design a trident prediction head and a dynamic update strategy which jointly maintain a reliable template for facilitating inter-frame communication. Extensive experiments validate that the proposed method achieves satisfactory results compared with the state-of-the-art competitors on three RGBT benchmarks while reaching real-time speed.
<div align="center">
   <img src="MT-RGB.gif"  height=240><img src="MT-T.gif" height=240>
</div>

## 🌟GTOT results
You can download the raw result GTOT-result.rar

**GTOT PR:0.935 SR:0.760**
![image](gtot-result.png) 
## 🌟RGBT-234 results
You can download the raw result RGBT234-result.rar

**RGBT234 PR:0.850 SR:0.619**
![image](rgbt234-result.png)
## 🌟LaSheR results
You can download the raw result LaSHeR-result.rar

**LasHeR PR:0.608 NPR:563 SR:0.474**
![image](lasher-result.png)
## Citation
Please cite this paper in your publications if it helps your research:

```
@inproceedings{hou2022mirnet,
  title={MIRNet: A Robust RGBT Tracking Jointly with Multi-Modal Interaction and Refinement},
  author={Hou, Ruichao and Ren, Tongwei and Wu, Gangshan},
  booktitle={2022 IEEE International Conference on Multimedia and Expo (ICME)},
  pages={1--6},
  year={2022},
  organization={IEEE}
}
```

```
@inproceedings{hou2023mtnet,
  title={MTNet: Learning Modality-aware Representation with Transformer for RGBT Tracking},
  author={Hou, Ruichao and Xu, Boyue and Ren, Tongwei and Wu, Gangshan},
  booktitle={2023 IEEE International Conference on Multimedia and Expo (ICME)},
  pages={1--6},
  year={2023},
  organization={IEEE}
}
```
