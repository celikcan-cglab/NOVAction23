# NOVAction23 Dataset
Here we present NOVAction23 dataset, which is generated using NOVAction23 Engine.
 
## File Structure:
1. NOVAction23.zip : Includes all of our generated videos.
2. NOVA2DPose.zip : Includes pose information of NTU 20 and NOVAction23, which are ready to use with mmaction2 library.
3. labels.xlsx : Includes label information for NOVAction23 videos.
4. videoyoutube.xlsx : Includes links for YouTube videos of the given action classes.
 
## How to use? :
1. To determine the class information, you need to check video name (....Axyz.mp4 where xyz number indicates action class.)
2. You can get the label information from labels.xlsx. For video names are R00... (PxyzR00...) where xyz is indicates subjects numbered from 1 to 927. For video names with R01... (PxyzR01...) xyz indicates subjects between 927 and 1105. You should add 927 to number xyz if video name has R01 since xyz is a number between 1 and 178.
3. Skeleton informations are ready to run with mmaction2 library.
 
## About Labels:
You can check the subject number and the following features of the subject using the labels.xlsx file and following:
Environment: 1-suburban, 2-city, 3-subway, 4-downtown, 5-office.
Weather: 1-clear sky, 2-cloudy1, 3-cloudy2, 4-cloudy3.
Time of the day:  1-morning/sunset, 2-midday, 3-night.
Height:  1 2 3 low med high
Weight:  1 2 3 low med high
Skin:  1 2 3 white brown black
Gender:  1 male 2 female
 
## Download Links :
NOVAction23.zip : https://drive.google.com/file/d/1TkHZL2KTv17ZHSbyqla013Z8zO1QvxXX/view

NOVA2DPose.zip : https://drive.google.com/file/d/1TuABR_0lVcOBLPAufwM1BmDX-XMohv9G/view

labels.xlsx : https://docs.google.com/spreadsheets/d/1TuMdY5ZdY3USiJLTc6XhnUtQb1U482R8/view

videoyoutube.xlsx : https://docs.google.com/spreadsheets/d/1Tj2fKKHTRL6mRz7ACR0JeaqxA0tM8WYs/view
