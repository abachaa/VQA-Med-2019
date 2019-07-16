------------------------------------
VQA-Med-2019: Test Set
------------------------------------

(1) VQAMed2019_Test_Questions.txt : contains 500 questions in the following format: <Image-ID>|<Question>

		(note that <Image-ID> is the image file name without the .jpg extension) 


(2) VQAMed2019_Test_Images : A directory containing 500 images that are associated to the test questions


(3) VQAMed2019_Test_Questions_w_Ref_Answers.txt: contains the question categories and reference answers manually validated by 2 medical doctors.
 
We took into account the cases of (1) multiple correct answers and (2) optional parts in the reference answers: 
1) # denotes several possible answers (retrieving one of the answers is considered correct), example: 
synpic54143|abnormality|what is the primary abnormality in this image?|anaplastic oligodendroglioma#multi-cystic complex mass
2) () denotes an optional part that makes the answer perfect but could be ignored, example: 
synpic35171|abnormality|what is abnormal in the ct scan?|(angioinvasive aspergillosis with) septic cerebral emboli

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
        publisher = {CEUR-WS.org $<$http://ceur-ws.org$>$},
        month = {September 9-12},
        address = {Lugano, Switzerland}
        }
        
 Contact Information
 --------------------------
Asma Ben Abacha: asma.benabacha@nih.gov   https://sites.google.com/site/asmabenabacha/
