# VQA-Med-2019

- Website: https://www.imageclef.org/2019/medical/vqa/
- Mailing list: https://groups.google.com/d/forum/imageclef-vqa-med 
- Paper: http://ceur-ws.org/Vol-2380/paper_272.pdf
- Results of the VQA-Med-2019 challenge on crowdAI: https://www.crowdai.org/challenges/imageclef-2019-vqa-med/leaderboards 

Task:
-------------------
VQA-Med 2019 focused on radiology images and four main categories of questions: Modality, Plane, Organ system and Abnormality. These categories are designed with different degrees of difficulty leveraging both classification and text generation approaches. In this second edition of the VQA challenge, we targeted medical questions asking about one element only (e.g. what is the organ principally shown in this mri? in what plane is this mammograph taken? is this a t1 weighted, t2 weighted, or flair image? what is most alarming about this ultrasound?), and that can be answered from the image content without requiring additional medical knowledge or domain-specific inference.  

VQA-Med-2019 Data:
-------------------
The VQA-Med-2019 dataset includes a training set of 3,200 medical images with 12,792 Question-Answer (QA) pairs, a validation set of 500 medical images with 2,000 QA pairs, and a test set of 500 medical images with 500 questions. 

1) The training, validation and test sets are available at: <https://zenodo.org/records/10499039> 

3) The VQA-Med-2019 test set and the reference answers are also available at: <https://github.com/abachaa/VQA-Med-2019/tree/master/VQAMed2019Test>  

Please see the readme files [[1]](https://github.com/abachaa/VQA-Med-2019/blob/master/README-VQA-Med-2019-Data.txt) [[2]](https://github.com/abachaa/VQA-Med-2019/blob/master/VQAMed2019Test/README-VQA-Med-2019-TestSet.txt) for more detailed information about the dataset and the categories of questions and answers.


Reference: 
-------------------

If you use the VQA-Med 2019 dataset, please cite our paper:
"VQA-Med: Overview of the Medical Visual Question Answering Task at ImageCLEF 2019". Asma Ben Abacha, Sadid A. Hasan, Vivek V. Datla, Joey Liu, Dina Demner-Fushman, Henning Müller. Working Notes of CLEF 2019. Paper available at: <https://ceur-ws.org/Vol-2380/paper_272.pdf>   


@Inproceedings{ImageCLEFVQA-Med2019,

        author = {Asma {Ben Abacha} and Sadid A. Hasan and Vivek V. Datla and Joey Liu and Dina Demner-Fushman and Henning M\"uller},
        
        title = {VQA-Med: Overview of the Medical Visual Question Answering Task at ImageCLEF 2019},

        url = {https://ceur-ws.org/Vol-2380/paper\_272.pdf}
        
        booktitle = {Working Notes of {CLEF} 2019},
        
        series = {{CEUR} Workshop Proceedings},

        volume       = {2380},
        
        year = {2019},
        
        publisher    = {CEUR-WS.org}, 
        
        month = {September 9-12},
        
        address = {Lugano, Switzerland}
        }
