# **BoxingX: A Multi-Modal Benchmark for Boxing Action Recognition and Localization**
![Dataset_page-0001 (1)](https://github.com/user-attachments/assets/a2b83031-14a3-4779-8eaa-89cb11cb3ebd)

🥊BoxingX is a large-scale, richly annotated benchmark dataset specifically created to advance research in vision-based analysis of boxing actions. The dataset comprises 6,915 finely segmented punch clips extracted from 20 unedited YouTube boxing videos, covering six distinct punch types:

**1) Cross**

**2) Jab**

**3) Lead Hook**

**4) Lead Uppercut**

**5) Rear Hook**

**6) Rear Uppercut**

This benchmark is developed to address the lack of domain-specific datasets in combat sports and is intended for tasks such as action recognition, temporal localization, pose-based classification, and skill assessment.# BoxingX-A-Multi-Modal-Benchmark-for-Boxing-Action-Recognition-and-Localization

**🗃️Dataset Features**

Total Clips: 6,915

- Training: 5,513 (Subjects S1–S15)

- Validation: 1,402 (Subjects S16–S20)

Punch Types (6 classes):

- Cross, Jab, Lead Hook, Lead Uppercut, Rear Hook, Rear Uppercut

Videos: 20 unedited YouTube videos

- 18 athletes (11 male, 7 female)

- Real-world, monocular RGB recordings

Annotations:

- Temporal punch boundaries

- Per-clip class labels

- Frame-wise 2D pose keypoints (AlphaPose)

Pose Tracking:
Annotation_file/ # Punch annotations with temporal boundaries and class labels
- Center-of-mass tracking

- Person of interest selected and tracked across frames

Pose Normalization:

- Keypoints scaled to video dimensions

- Poses padded to max 25 frames (30 fps)

## The pose estimations from the RGB videos are extracted using the [**AlphaPose**](https://github.com/MVIG-SJTU/AlphaPose?tab=readme-ov-file) model, and the estimated poses follow the [**COCO format**](https://cocodataset.org/#format-data).
## 📂 Dataset Structure
```bash
dataset/
├── Annotation_files/
├── RGB_videos/
└── Skeleton_data/
```
The dataset is organized into the following format:

- The **`Annotation_file`** contains punch metadata in the format:  
This information is stored in an Excel (.xlsx) file, where each row corresponds to a single punch clip.

We will provide a public link to access this dataset after publication.
📥 **[Download Dataset (Available after publication)](https://drive.google.com/drive/folders/1Vyl8twJQ1qkqEPwhvfsrJsJ8nLQ92uoy)**




