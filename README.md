# Semi-Supervised-Learning-Meta-Pseudo-Learning-

I made this project with reference the following article.
https://arxiv.org/abs/2003.10580

![SSL_diagram (1)](https://user-images.githubusercontent.com/64545114/131904512-f7205389-709a-4f3b-bff2-1706ec613076.png)

Firstly you should run the train_teacher.ipynb. This code provides to train your labeled dataset.

Then run the prepare_unlabeled_dataset.ipynb. This code provides to prepare your unlabeled dataset. There are 2 augmentation method. Adding noise and cut-out. You can choose one of them or use both of them.

And then run the make_pseudo_labels.ipynb. This code provides producing pseudo labels for your augmented unlabeled dataset.

And then run the train_student_model.ipynb. This code provides to train your augmented pseudo labeled dataset. You should use your teacher model weight as a pretrained model.

Lastly run the inferance.ipynb. This code provides to save predict result as a cvs file.
