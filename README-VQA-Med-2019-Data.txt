========================
VQA-Med @ ImageClef 2019
========================

** The test set is available here: https://github.com/abachaa/VQA-Med-2019/tree/master/VQAMed2019Test 
     (Readme file: https://github.com/abachaa/VQA-Med-2019/blob/master/VQAMed2019Test/README-VQA-Med-2019-TestSet.txt) 

Training and Validation Sets:
-------------------------------

All datasets are available at: https://zenodo.org/records/10499039 

- Training set: 3,200 images with 12,792 Question-Answer (QA) pairs.
- Validation set: 500 images with 2,000 QA pairs.

We considered 4 categories of questions: 
- Modality, Plane, Organ system and Abnormality.

Examples:
- is this a t1 weighted, t2 weighted, or flair image?
- in which plane is the mri displayed?
- what is the organ principally shown in this x-ray?
- what is most alarming about this ct scan? 

We included additional files organized by category (if needed to train the VQA models). Below are the list of classes for each question category: Plane, Organ and Modality.  

N.B. We will not provide the categories of the questions in the test set. 

================================
Planes (16)
================================
    Axial
    Sagittal
    Coronal
    AP
    Lateral 
    Frontal
    PA
    Transverse
    Oblique
    Longitudinal
    Decubitus
    3D Reconstruction
    Mammo - MLO
    Mammo - CC
    Mammo - Mag CC
    Mammo - XCC

================================
Organ Systems (10)
================================
    Breast 
    Skull and Contents
    Face, sinuses, and neck
    Spine and contents
    Musculoskeletal 
    Heart and great vessels 
    Lung, mediastinum, pleura 
    Gastrointestinal 
    Genitourinary 
    Vascular and lymphatic 

================================
Modalities (36)
================================
1)   [XR]
XR - Plain Film

2)  [CT]
CT - noncontrast
CT w/contrast (IV)
CT - GI & IV Contrast
CTA - CT Angiography
CT - GI Contrast
CT - Myelogram
Tomography

3)  [MR]
MR - T1W w/Gadolinium
MR - T1W - noncontrast
MR - T2 weighted
MR - FLAIR
MR - T1W w/Gd (fat suppressed)
MR T2* gradient,GRE,MPGR,SWAN,SWI
MR - DWI Diffusion Weighted
MRA - MR Angiography/Venography
MR - Other Pulse Seq.
MR - ADC Map (App Diff Coeff)
MR - PDW Proton Density
MR - STIR
MR - FIESTA
MR - FLAIR w/Gd
MR - T1W SPGR
MR - T2 FLAIR w/Contrast
MR T2* gradient GRE

4) [US]
US - Ultrasound
US-D - Doppler Ultrasound

5) [MA]
Mammograph

6)  [GI]
BAS - Barium Swallow
UGI - Upper GI
BE - Barium Enema
SBFT - Small Bowel

7) [AG]
AN - Angiogram
Venogram

8) [PT] 
NM - Nuclear Medicine
PET - Positron Emission


-------------------
Reference: 
-------------------

If you use the VQA-Med-2019 dataset, please cite our paper:
"VQA-Med: Overview of the Medical Visual Question Answering Task at ImageCLEF 2019". Asma Ben Abacha, Sadid A. Hasan, Vivek V. Datla, Joey Liu, Dina Demner-Fushman, Henning Müller. CLEF 2019 Working Notes.  

@Inproceedings{ImageCLEFVQA-Med2019,
        author = {Asma {Ben Abacha} and Sadid A. Hasan and Vivek V. Datla and Joey Liu and Dina Demner-Fushman and Henning M\"uller},
        title = {VQA-Med: Overview of the Medical Visual Question Answering Task at ImageCLEF 2019},
        booktitle = {CLEF 2019 Working Notes},
        series = {{CEUR} Workshop Proceedings},
        year = {2019},
        publisher = {CEUR-WS.org}, 
        month = {September 9-12},
        address = {Lugano, Switzerland}
        }
