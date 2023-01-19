<br />

[![Open In Studio Lab](https://studiolab.sagemaker.aws/studiolab.svg)](https://studiolab.sagemaker.aws/import/github/org/repo/blob/master/path/to/notebook.ipynb)

# deepLearning2022FallProject
<br />

<img width="551" alt="截屏2022-11-09 下午7 34 47" src="https://user-images.githubusercontent.com/50295329/200971617-0616eff7-c5ac-4fc5-a8f7-8a0de2050737.png">

## Abstract

In the project, we intended to achieve the best modified residual network (ResNet) model with the highest test accuracy and no more than 5 million parameters on the CIFAR-10 image classification dataset. In the first part of the work, we kept all 6 parameters at the initial ResNet values and only modified one at a time.According to this approach, we can see how each hyperparameters tuning influences the test accuracy and parameters on the residual network model. Then we selected out all possible best performing values for each parameters based on the previous work and combine them together to define the hyperparameter values for the final project model. The fi-nal ResNet architecture parameters were built as follow-ing: N = 3, Bi = 3, Ci = 68, Fi = 2, P = 7, Ki = 1, batch size = 64.Moreover, we compared different optimizers and finally chose ADAM optimizer with the learning rate = 0.001. At last, our best performing model ran 140 epochs and achieved the highest test accuracy of 92.83%, with 4,883,906 parameters. Therefore, The final modified ResNet model successfully satisfy the project goal. 

## Deliverables
This project has two deliverables:
• A project report (15 points).
• A project codebase (10 points).
Projects will be graded on:
2
• clarity and quality of submitted project report;
• quality of final results. Aim for test accuracy of at least 80% as a minimum baseline; if your
design is sensible, you should be able to achieve upwards of 90%;
• and clarity and quality of submitted codebase

<br />

<img width="551" alt="image" src="https://user-images.githubusercontent.com/50295329/203223059-c90a0090-106e-42be-9502-b2b89876dcc8.png">








## Licence
Distributed under the MIT License.


