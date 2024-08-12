We will create a Neural Networks based Factorization Machine: taking ideas from
https://github.com/d2l-ai/d2l-en/blob/master/chapter_recommender-systems/deepfm.md and https://arxiv.org/pdf/1906.00091

Best performing model was the DeepFM as shown above with some slight changes in the MLP structure
![image](https://github.com/user-attachments/assets/ea3d3f91-c62d-4280-acfd-10c8d8295a87)


On our ratings_small movielens dataset, we begin with a simple matrix factorization approach to get a MSE of 2.12 on validation set

![image](https://github.com/user-attachments/assets/0e2e478a-2a8e-4516-828f-fd0b80f0b945)



and finally on a Factorization Machine + MLP, we get a MSE on validation set of 0.81

![image](https://github.com/user-attachments/assets/30eaecb0-02cc-4196-8b6a-f505ae3256e2)
