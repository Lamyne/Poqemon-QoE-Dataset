# Poqemon-QoE-Dataset

This work is proposed to describe a new dataset that contains many QoE Influence Factors (QoE IFs) and subjective Mean Opinion Scores(MOS).
This dataset is collected during the PoQeMoN project (www.ip-label.fr/performance-wire/ projet-collaboratif-platform-quality-evaluation-mobile-networks) 
where a crowd measurement platform is implemented to assess YouTube end user’s QoE in mobile environments (UMTS, HSPA, LTE, etc.). This dataset concerns
collecting a lot of QoE  IFs using  a  VLC  media  player.  The  used  platform  consists  on  an  Android-based  applica-
tion  developed  and  installed  on  the  end  user  device  (phones and  tablets).  The  testbed  experiment  mainly  consists  of  the
following elements:

• A dedicated mobile application has been developed for experimentation.

• The  evaluation  was  performed  at  different  locations  (train  station, walking, etc.).

• Users were trained to perform the video session tests.

• Nine  devices  are  used  by  participants  to  achieve  tests.  The devices  have  different  characteristics  like  screen  size,  android
version and Cpu.

• Several  types  of  videos  were  used  (e.g.  sport,  movie  trailer, documentary, news, music,... etc.).

• Four   several   mobile   networks   were   tested   (Orange,   SFR, Bouyegues and Free)



1- Source:

Creators: 
- Lamine Amour (lamine.amour@u-pec.fr) 
- Sami Souihi (sami.souihi@u-pec.fr) 
- Abdelhamid Mellouk (mellouk@u-pec.fr)

2- Data Set Information:

The dataset was built from a crowdsourcing campagn test where 1560 samples covering 29 Quality of Experience Impact Factors (QoE IFs). 
The used videos are of different types/complexities.

The geographical location of the testbed was the LiSSi laboratory (http://lab.lissi.fr/) around Paris city in France. 181 testers 
prticipated in the test campaign. All of them were researchers (their family) and students  from different disciplines aged 19 to 38 years with
few or no experience with video assessment experimentation.

3- Attribute Information:

-> The content of the dataset can be uploaded with different formats. These formats are:

    name.csv : Microsoft Excel 2013 file.

    name.arff : Weka files (https://en.wikipedia.org/wiki/Weka_(machine_learning).

    name.data : Open Document format (https://en.wikipedia.org/wiki/OpenDocument.


-> Both files contain 22 QoE IFs and the Mean Opinion Scors (MOS)given by userss.

  1)  id
	
  2)  user_id
 	
  3)  QoA_VLCresolution
 	
  4)  QoA_VLCbitrate
	
  5)  QoA_VLCframerate  
 	
  6)  QoA_VLCdropped
	
  7)  QoA_VLCaudiorate
 	
  8)  QoA_VLCaudioloss
 	
  9)  QoA_BUFFERINGcount
 	
  10) QoA_BUFFERINGtime
	
  11) QoS_type
 	
  12) QoS_operator
	
  13) QoD_model
 	
  14) QoD_os-version
  
  15) QoD_api-level
 	
  16) QoU_sex
	
  17) QoU_age
  
  18) QoU_study
 	
  19) QoF_begin_time
 	
  20) QoF_shift
  
  21) QoF_audio
  
  22) QoF_video
  
  23) MOS
	
--> Each variable belongs to a category of QoE Influence Factors (QoE IFs) that consists:
  - Video parameters from VLC video player (QoA) (3 to 10)
  
- Network information (QoS) (11 to 12)

 - Device characteristics  (QoD)(13 to 15)
 
 - User's profil (QoU) (16 to 18)	
 
- User feedback (QoF)(19 to 22)		  
             
--> Number of Instances : 

-class 1 (MOS = 1): 92  

-class 2 (MOS = 2): 119

-class 3 (MOS = 3): 244

-class 4 (MOS = 4): 787

-class 5 (MOS = 5): 300

--> Number of Attributes 	
   23

  
 
--> NOTES: 
    - 2st (Vresolution) attribute is class identifier for the video resolution (240p, 360p)
      
    - 10st (Ntype) attribute is class identifier for the used network type in the assessment:
    
• 1 : EDGE

• 2 : UMTS 

• 3 : HSPA

• 4 : HSPAP

• 5 : LTE
      
     
   - 11st (Noperator) attribute is class identifier for the network operator in France:
   
• 1 : SFR 

• 2 : BOUYEGUES 

• 3 : ORANGE 

• 4 : FREE
      
   - 14st (QoU_sex) User's gender.
   
• 0 -> Woman

• 1 -> man
  
		   
- 15st (QoU_study) High user's level study

• 5 -> University

• 4 -> Secondary school

• 3 -> College

• 2 -> Premary school

• 1 -> Other
	  
- 19st (MOS) Mean Opinion Scroe that a tester will give at the end of each video view.

• 5 -> Excellent

• 4 -> Good

• 3 -> Fair

• 2 -> Poor

• 1 -> Bad



4- Related publications

  1) Stéphanie Moteau, Fabrice Guillemin and Thierry Houdoin:
    Correlation between QoS and QoE for HTTP YouTube content in Orange cellular networks
    Conference 2017.

   -> The data was used by Orange to identify the Quality of Service (QoS) 
   indicators in order to predict the Quality of Experience (QoE) for HTTP YouTube content 
    on mobile networks. A part of the results are based on experiments on the Orange network. 
	

   (2) 
    Lamine Amour, Sami Souihi, Said Hoceini, Abdelhamid Mellouk:
		"Building a Large Dataset for Model-based QoE Prediction in the Mobile Environment". 
		The 18th ACM International Conference on Modeling, Analysis and Simulation 
		of Wireless and Mobile Systems, pages 313-317. November 2015.

   --> Here, the data set built methodlogy is explained, where the ACR method were used to
   evaluate subjectevly the user's QoE using Mean Opinion Score (MOS). Furthermore, this 
   data was used to illustrate the QoE IFs interaction problem in the QoE assessment.
   

5- ACKNOWLEDGMENTS

This work has been funded by Orange in the framework of the French cooperative project “Platform for Quality Evaluation
of Mobile Networks”, Pˆole de Comp´etitivit´e Systematic (FUI 16).
