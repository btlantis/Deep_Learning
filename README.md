Hi! This is Duen-shian (Ben) Wang, 

and I am looking for any opportunities as a computational chemistry and a deep learning researcher. 

Please feel free to reach out to me by LinkedIn or email. Thank you!

LinkedIn https://www.linkedin.com/in/duen-shian-wang/
Email duenshianwang@gmail.com

######################################################################################################

Here are the examples for deep learning applications on drug discovrey realm.
*1. Deep_learning_sample1_drug_discovery_oneInput_twoOutputs.ipynb


Hightlight
-Utilized RDKit (Open-Source Cheminformatics Software  https://www.rdkit.org/)
-Appying K-fold validation and randomized initial weights to unbia train process.


How to use?
If you have small molecule drugs with SMILE and other numerical chemical/physical properties.
-One Input: Featurized numerical feature of the small molecule from SMILE by chemcepterize_mol() function + flatten trick.
-Multiple Outputs: e.g., binary class, binding affinity..etc

PS: If you have more than one numerical feature, try Concatenate all numerical features as One Iuput. 


*2. Deep_learning_sample1_drug_discovery_twoInputs_twoOutputs.ipynb


Hightlight
-Utilized RDKit (Open-Source Cheminformatics Software  https://www.rdkit.org/)
-Appying K-fold validation and randomized initial weights to unbia train process.
-Using both numerical and graphic data as inputs.


How to use?
If you have small molecule drugs with SMILE and other numerical chemical/physical properties.
-Two Input: Featurized numerical feature of the small molecule from SMILE by chemcepterize_mol() function + flatten trick, and the graphic feature  chemcepterize_mol() function. 
-Multiple Outputs: e.g., binary class, binding affinity..etc

PS: I take advantege of ResNet model to optimize the CNN part.
