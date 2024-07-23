## "Трансформеры в NLP и приложениях"

1. Простейшая полносвязная нейронная сеть на pytorch.  
    * [01]pytorch_foundation.ipynb  
    * датасет CIFAR10, 10 классов,  
    * метрика Accuracy
    * используется `torch`, `torchvision.datasets`, `torch.utils`, `matplotlib`, loss and optimizer: `CrossEntropyLoss`, `Adam`

2. Классификация с помощью библиотеки transformers huggingface.  
      * [02]huggingface_clothing_reviews.ipynb  
      * датасет [Women's E-Commerce Clothing Reviews](https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews)
         * Задача бинарной классификации Recommended IND, (имеется дисбаланс)  
         * Задача прогноз рейтинга (Rating), 5 классов, (имеется дисбаланс)    
      * метрика F1
      * используется `transformers huggingface`, `API trainer`, `nltk`, `seaborn`  

3. 
4.
