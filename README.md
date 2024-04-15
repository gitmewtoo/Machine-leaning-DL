Discussion and Conclusion: 
This experiment was started on a comprehensive exploration of the dataset, initially 
exploring the categories and their corresponding file counts. Subsequently, audio data 
underwent visualization, revealing their inherent characteristics and similarities through 
plotted representations. Transitioning from raw audio to mel-spectrograms provided further 
insights into their distinct features. 
Training the dataset on a CNN model yielded promising results with an accuracy of 85% 
and a validation accuracy of 68%, suggesting that augmentation is needed. 
Challenges: 
Challenges surfaced during the augmentation phase, particularly in determining suitable 
parameters for frequency and amplitude augmentation. The wide amplitude range 
necessitated cautious scaling to maintain data integrity. 
Augmentation strategies were tested on select files to ascertain optimal ranges, ensuring 
f
 idelity to the original data. Scaling up augmentation to meet dataset demands introduced 
computational deadlock due to memory constraints. To address this, augmentation 
parameters were manually adjusted to generate 2000 files per iteration, repeated over 13 
cycles. 
Upon completion of augmentation, the dataset, comprising original and augmented files, 
underwent shuffling and partitioning for training and testing. The adoption of ResNet152V2 
as the model stemmed from its capability to leverage transfer learning, mitigating 
computational complexities associated with large datasets.
![image](https://github.com/gitmewtoo/Machine-leaning-DL/assets/121586893/9d461ba6-33cc-497f-940e-ddc5c1dba21b)
![image](https://github.com/gitmewtoo/Machine-leaning-DL/assets/121586893/9292b884-82be-4371-b310-0230480f42b8)


In conclusion, while this study achieved great results, several avenues for improvement 
and extension exist. Future improvement could explore more sophisticated augmentation 
techniques, optimize computational efficiency, and investigate alternative model 
architectures to further enhance performance, as well as larger original dataset would be 
better for real world applications.
