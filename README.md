# TP2_TS
# 1-Sauvegardez ce fichier dans bureau,puis charger-le dans MATLAB 

![image](https://user-images.githubusercontent.com/97410524/215356390-423d9d66-abde-44a2-b6f8-6e6b2331deec.png)

 
# 2- Tracez le signal enregistré en fonction du temps
 
 ![image](https://user-images.githubusercontent.com/97410524/215356026-523533cd-053c-49ce-93e2-0d46bdf5bdcd.png)

 ![image](https://user-images.githubusercontent.com/97410524/215356013-d16972b6-c61e-4d80-8316-703f1cd4a751.png)

 
puis en uitilisant la commande 'sound' on peut l'ecouter
# 3-On peut également le compresser en multipliant la fréquence 2 ou le dilater en la divisant par 2

![image](https://user-images.githubusercontent.com/97410524/215356047-66af241c-d9f2-46d9-975a-986adef5efac.png)


 
- Il est important de noter que la compression du son a tendance a conserver les pics à hautes fréquences, ce qui donne l’impression que le son est diminué et aigue.
-par contre La dilatation accompagnée d'une augmentation d’amplitude des pics à basses fréquences, ce qui donne l’impression que le son est grave et amplifié

# 4-on trace le signal , puis on essaye de repérer les indices du début et de fin de la phrase « Rien ne sert de ».

 ![image](https://user-images.githubusercontent.com/97410524/215356058-651ffecf-89a1-4673-8849-99d9aea29d7d.png)
 
 
![image](https://user-images.githubusercontent.com/97410524/215356063-75c74a29-854c-4afe-884e-e06bed26ced4.png)

 
# 5- Pour segmenter le premier mot, il faut par exemple créer un vecteur « riennesertde »contenant les n premières valeurs du signal enregistré x puis one cree le vecteur avant de l'écouter
 ![image](https://user-images.githubusercontent.com/97410524/215356079-be8bcc18-eb61-4456-baf3-5e0e56be7b12.png)

# 6- on segmente cette fois la phrase en créant des variables : riennesertde, courir, ilfaut, partirapoint.

 ![image](https://user-images.githubusercontent.com/97410524/215356087-3af75fbc-c74a-4180-9ecb-2826768e12ce.png)

# 7-Réarrangez ce vecteur pour écouter la phrase synthétisée « Rien ne sert de partir à point, il faut courir ».

![image](https://user-images.githubusercontent.com/97410524/215356100-96193a7f-0db0-43db-aaa2-a658cda4a83b.png)

 
# Synthèse et analyse spectrale d’une gamme de musique

![image](https://user-images.githubusercontent.com/97410524/215356149-40566633-9276-4b74-883e-e4242b09ac05.png)

# 1- on cree un programme qui permet de jouer une gamme de musique. La fréquence de chaque note est précisée dans le tableau ci-dessous. Chaque note aura une durée de 1s.

![image](https://user-images.githubusercontent.com/97410524/215356299-78f0147b-541b-439d-86e3-d5ed7c6a3925.png)

# 2- Utilisez l’outil graphique d’analyse de signaux signalAnalyzer pour visualiser le spectre de votre gamme

 ![image](https://user-images.githubusercontent.com/97410524/215356313-73520e06-d3a3-49d6-8c67-b23ce53ab586.png)

![image](https://user-images.githubusercontent.com/97410524/215356335-b01c70d3-d0b3-4b69-b72f-ba54e8b8d89d.png)

 
# 3- Tracez le spectrogramme qui permet de visualiser le contenu fréquentiel du signal au cours du temps 
![image](https://user-images.githubusercontent.com/97410524/215356456-eac638c1-d7c5-4af6-9711-840a0fad449e.png)

 
# 4- Le spectre d’un signal à temps continu peut être approché par transformée de Fourier discrète (TFD) ou sa version rapide (Fast Fourier Transform (FFT). 

![image](https://user-images.githubusercontent.com/97410524/215356469-50c50e2b-518e-4c9f-af01-bf2f7f1a56b1.png)
![image](https://user-images.githubusercontent.com/97410524/215356474-243e45c2-01fb-46d9-9b86-cb749775fc4a.png)
