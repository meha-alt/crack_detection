## 📄 Research Paper
# Deep-Learning Based Concrete Crack Segmentation and Quantification Using U-Net, YOLO-Seg, and SAM2 with YOLO26-seg Guided Refinement]

The complete research paper accompanying this codebase is available below:
[![Download/View Paper (PDF)](https://img.shields.io/badge/Google%20Drive-Read%20Research%20Paper%20(PDF)-1f4287?style=for-the-badge&logo=googledrive&logoColor=white)](https://drive.google.com/file/d/1IadD7SxlYx-qAzDY2vex3P0Xx9tepz_k/view?usp=sharing)

## 📄 Abstract
Automated crack detection is critical for assessing material degradation and en
suring the integrity of structural systems.While deep learning has advanced visual
inspection, pixel-level crack segmentation remains challenging particularly in the
presence of complex backgrounds and noise. However,precise segmentation is essen
tial for reliable crack quantification, including width estimation for severity assess
ment. This study evaluates the segmentation fidelity of an instance segmentation
model, YOLO26-seg, against the promptable fine-tuned Segment Anything Model
(SAM2) guided using YOLO26-seg across a 200-image dataset.Quantitative anal
ysis reveals different operational trade offs between the two approaches.YOLO26
seg-guided SAM2 framework demonstrated statistically significant superiority in
precision with only a marginal dip in recall .This demonstrates that YOLO26-seg
effectively localizes crack regions, whereas guided SAM2 refines the predicted bound
aries producing more accurate segmentation mask.However,YOLO26-seg demon
strated greater robustness maintaining highly stable and consistent recall regardless
of image difficulty whereas SAM2 is highly prompt sensitive,with inaccurate prompt
occasionally leading to degraded segmentation.Ultimately, YOLO26-seg is optimal
for reliable, high-speed detection,while the proposed YOLO26-seg-guided SAM2
pipeline generates a more precise mask enabling a more accurate width estimation

