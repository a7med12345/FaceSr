# Comparison Between our method  and FSRGAN

We have two methods supervised and unsupervised

### PSNR comparison:


####  Comparison

##### Artificial Low  Resolution

Artificial Low resolution images is generated by downsampling high rsolution images from 128x128 to 16x16.

1- Visual Comparison

a- Front View

|BICUBIC| FSRGAN| Ours(Supervise| Ours(Unsupervised)|Groundtruth
|:----------------------------------------- :|:------------------------:|:--------:|:-----------:|:-----------:
![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_01_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_01_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_01_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0001_01_output.jpg 'uns')| ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_01_gt.jpg 'gt')|  
![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_02_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_02_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_02_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0001_02_output.jpg 'uns')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_02_gt.jpg 'gt')|  
![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_03_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_03_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_03_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0001_03_output.jpg 'uns')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0001_03_gt.jpg 'gt')|
![alt text](images/artificial_Low_resolution_visual_comparison/0_000001_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_000001_fsrnet.png 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_000001_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_000001_output.jpg 'uns')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_000001_gt.png 'gt')|
![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_01_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_01_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_01_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0002_01_output.jpg 'uns')| ![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_01_gt.jpg 'gt')|  
![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_02_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_02_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_02_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0002_02_output.jpg 'uns')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0002_02_gt.jpg 'gt')|
![alt text](images/artificial_Low_resolution_visual_comparison/0_0003_02_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0003_02_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0003_02_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0003_02_output.jpg 'uns')|   ![alt text](images/artificial_Low_resolution_visual_comparison/0_0003_02_gt.jpg 'gt')|
![alt text](images/artificial_Low_resolution_visual_comparison/0_0004_10_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0004_10_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0004_10_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0004_10_output.jpg 'uns')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0004_10_gt.jpg 'gt')| 
![alt text](images/artificial_Low_resolution_visual_comparison/0_0005_06_input.jpg 'bicubic')|    ![alt text](images/artificial_Low_resolution_visual_comparison/0_0005_06_fsrnet.jpg 'fsrnet')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0005_06_output.jpg 'ours')| ![alt text](images/artificial_Low_resolution_visual_comparison/unsupervised/0_0005_06_output.jpg 'uns')|  ![alt text](images/artificial_Low_resolution_visual_comparison/0_0005_06_gt.jpg 'gt')|  

b- Side View

|FSRGAN                                                                               | Ours(Supervised)     |  Ours(Unsupervised)|GroundTruth|
|:------------------------                                                            :|:------------------------:|:--------:|:-----------:
![alt text](images/artificial_sideview/fsrnet/0_image32714.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image32714_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image32714_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image32714.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image43394.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image43394_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image43394_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image43394.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image41743.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image41743_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image41743_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image41743.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image43555.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image43555_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image43555_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image43555.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image53039.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image53039_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image53039_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image53039.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image53812.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image53812_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image53812_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image53812.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image58018.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image58018_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image58018_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image58018.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image60272.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image60272_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image60272_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image60272.jpg 'gt')| 
![alt text](images/artificial_sideview/fsrnet/0_image68246.jpg 'fsrgan')|    ![alt text](images/artificial_sideview/0_image68246_output.jpg 'super')|  ![alt text](images/artificial_sideview/unsupervised/0_image68246_output.jpg 'unsup')| ![alt text](images/artificial_sideview/0_image68246.jpg 'gt')| 


2- PSNR

We Calculate Average PSNR for around 9000 test images

|  Method | PSNR                 |
|---      |---                   |
|  FSRGAN |  22.84  |  
|  Ours(Supervised)  |  23.65  |  
|  Ours(Unsupervised)   |  21.97    | 



##### Real World Low Resolution data

1- Visual Comparison

a- Failure for the Supervised Approach

THe supervised approach fails when the original image is in low resolution 
 
|FSRGAN                                                                               | Ours(Supervised)     |  Ours(Unsupervised)|Original Image|
|:------------------------                                                            :|:------------------------:|:--------:|:------------:|
![alt text](images/real_data/failure_cases/fsrnet/0_2_Demonstration_Demonstration_Or_Protest_2_235.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/0_2_Demonstration_Demonstration_Or_Protest_2_235.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/0_2_Demonstration_Demonstration_Or_Protest_2_235.jpg 'unsup')|   ![alt text](images/real_data/failure_cases/gt1/0_2_Demonstration_Demonstration_Or_Protest_2_235.jpg 'gt')
![alt text](images/real_data/failure_cases/fsrnet/0_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_636.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/0_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_636.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/0_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_636.jpg 'unsup')| ![alt text](images/real_data/failure_cases/gt1/0_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_636.jpg 'gt')| 
![alt text](images/real_data/failure_cases/fsrnet/1_0_Parade_marchingband_1_291.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/1_0_Parade_marchingband_1_291.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/1_0_Parade_marchingband_1_291.jpg 'unsup')| ![alt text](images/real_data/failure_cases/gt1/1_0_Parade_marchingband_1_291.jpg 'gt')| 
![alt text](images/real_data/failure_cases/fsrnet/1_0_Parade_Parade_0_373.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/1_0_Parade_Parade_0_373.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/1_0_Parade_Parade_0_373.jpg 'unsup')|  ![alt text](images/real_data/failure_cases/gt1/1_0_Parade_Parade_0_373.jpg 'gt')|
![alt text](images/real_data/failure_cases/fsrnet/3_0_Parade_marchingband_1_259.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/3_0_Parade_marchingband_1_259.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/3_0_Parade_marchingband_1_259.jpg 'unsup')| ![alt text](images/real_data/failure_cases/gt1/3_0_Parade_marchingband_1_259.jpg 'gt')| 
![alt text](images/real_data/failure_cases/fsrnet/1_23_Shoppers_Shoppers_23_30.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/1_23_Shoppers_Shoppers_23_30.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/1_23_Shoppers_Shoppers_23_30.jpg 'unsup')| ![alt text](images/real_data/failure_cases/gt1/1_23_Shoppers_Shoppers_23_30.jpg 'gt')|
![alt text](images/real_data/failure_cases/fsrnet/2_0_Parade_marchingband_1_161.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/2_0_Parade_marchingband_1_161.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/2_0_Parade_marchingband_1_161.jpg 'unsup')|   ![alt text](images/real_data/failure_cases/gt1/2_0_Parade_marchingband_1_161.jpg 'gt')| 
![alt text](images/real_data/failure_cases/fsrnet/2_12_Group_Large_Group_12_Group_Large_Group_12_211.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/2_12_Group_Large_Group_12_Group_Large_Group_12_211.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/2_12_Group_Large_Group_12_Group_Large_Group_12_211.jpg 'unsup')| ![alt text](images/real_data/failure_cases/gt1/2_12_Group_Large_Group_12_Group_Large_Group_12_211.jpg 'gt')| 
![alt text](images/real_data/failure_cases/fsrnet/3_2_Demonstration_Demonstration_Or_Protest_2_884.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/3_2_Demonstration_Demonstration_Or_Protest_2_884.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/3_2_Demonstration_Demonstration_Or_Protest_2_884.jpg 'unsup')|  ![alt text](images/real_data/failure_cases/gt1/3_2_Demonstration_Demonstration_Or_Protest_2_884.jpg 'gt')|
![alt text](images/real_data/failure_cases/fsrnet/3_17_Ceremony_Ceremony_17_5.jpg 'fsrgan')|    ![alt text](images/real_data/failure_cases/supervised/3_17_Ceremony_Ceremony_17_5.jpg 'super')|  ![alt text](images/real_data/failure_cases/unsupervised/3_17_Ceremony_Ceremony_17_5.jpg 'unsup')|  ![alt text](images/real_data/failure_cases/gt1/3_17_Ceremony_Ceremony_17_5.jpg 'gt')|


b- Success of the supervised Approach

|FSRGAN                                                                               | Ours(Supervised)     |  Ours(Unsupervised)|Original Image|
|:------------------------                                                            :|:------------------------:|:--------:|:------------:|
![alt text](images/real_data/success_cases/fsrnet/0_0_Parade_marchingband_1_184.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_0_Parade_marchingband_1_184.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_0_Parade_marchingband_1_184.jpg 'unsup')|   ![alt text](images/real_data/success_cases/gt1/0_0_Parade_marchingband_1_184.jpg 'gt')
![alt text](images/real_data/success_cases/fsrnet/0_0_Parade_marchingband_1_432.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_0_Parade_marchingband_1_432.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_0_Parade_marchingband_1_432.jpg 'unsup')| ![alt text](images/real_data/success_cases/gt1/0_0_Parade_marchingband_1_432.jpg 'gt')| 
![alt text](images/real_data/success_cases/fsrnet/0_0_Parade_marchingband_1_668.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_0_Parade_marchingband_1_668.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_0_Parade_marchingband_1_668.jpg 'unsup')| ![alt text](images/real_data/success_cases/gt1/0_0_Parade_marchingband_1_668.jpg 'gt')| 
![alt text](images/real_data/success_cases/fsrnet/0_0_Parade_marchingband_1_1016.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_0_Parade_marchingband_1_1016.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_0_Parade_marchingband_1_1016.jpg 'unsup')|  ![alt text](images/real_data/success_cases/gt1/0_0_Parade_marchingband_1_1016.jpg 'gt')|
![alt text](images/real_data/success_cases/fsrnet/0_0_Parade_marchingband_1_873.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_0_Parade_marchingband_1_873.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_0_Parade_marchingband_1_873.jpg 'unsup')| ![alt text](images/real_data/success_cases/gt1/0_0_Parade_marchingband_1_873.jpg 'gt')| 
![alt text](images/real_data/success_cases/fsrnet/0_2_Demonstration_Demonstration_Or_Protest_2_326.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_2_Demonstration_Demonstration_Or_Protest_2_326.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_2_Demonstration_Demonstration_Or_Protest_2_326.jpg 'unsup')| ![alt text](images/real_data/success_cases/gt1/0_2_Demonstration_Demonstration_Or_Protest_2_326.jpg 'gt')|
![alt text](images/real_data/success_cases/fsrnet/0_2_Demonstration_Protesters_2_522.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_2_Demonstration_Protesters_2_522.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_2_Demonstration_Protesters_2_522.jpg 'unsup')|   ![alt text](images/real_data/success_cases/gt1/0_2_Demonstration_Protesters_2_522.jpg 'gt')| 
![alt text](images/real_data/success_cases/fsrnet/0_9_Press_Conference_Press_Conference_9_303.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/0_9_Press_Conference_Press_Conference_9_303.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/0_9_Press_Conference_Press_Conference_9_303.jpg 'unsup')| ![alt text](images/real_data/success_cases/gt1/0_9_Press_Conference_Press_Conference_9_303.jpg 'gt')| 
![alt text](images/real_data/success_cases/fsrnet/5_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_631.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/5_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_631.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/5_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_631.jpg 'unsup')|  ![alt text](images/real_data/success_cases/gt1/5_12_Group_Team_Organized_Group_12_Group_Team_Organized_Group_12_631.jpg 'gt')|
![alt text](images/real_data/success_cases/fsrnet/5_35_Basketball_Basketball_35_532.jpg 'fsrgan')|    ![alt text](images/real_data/success_cases/supervised/5_35_Basketball_Basketball_35_532.jpg 'super')|  ![alt text](images/real_data/success_cases/unsupervised/5_35_Basketball_Basketball_35_532.jpg 'unsup')|  ![alt text](images/real_data/success_cases/gt1/5_35_Basketball_Basketball_35_532.jpg 'gt')|



2- FID Score


|  Method | FID                 |
|---      |---                   |
|  FSRGAN |  39.40  |  
|  Ours(Supervised)  |  29.00  |  
|  Ours(Unsupervised)   |  28.65    | 
