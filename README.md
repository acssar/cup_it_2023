# cup it 2023
## Data science section
### my first case championship    
TeamRoulette 411 (The team was put together with roulette)   


the case was provided by VKontakte
![image](https://user-images.githubusercontent.com/10894740/229022276-924c1ae8-be1d-4781-a548-a7aac7ca69b6.png)

We achieved to get HQA.   

"High Quality Award — тем, кто прислал решения высокого качества — можем смело сказать: ваши решения были максимально близки к финалу."


![image](https://user-images.githubusercontent.com/10894740/229023813-c4da5bfc-8485-4d34-abe2-34d7b6b10607.png)


research.ipynb - dataset research conducted mainly by Julia   
bert_ranking_vk.ipynb - the core model I have chosen to use is distilBERT, it's lighter than BERT, but has good performance   
![image](https://user-images.githubusercontent.com/10894740/229025119-5a7fe115-c68d-4b40-a141-0f4e81b83bf8.png)
Idea to use first token with size of 768 that is used when doing sequence classification (classification of sentences in the problem of text modeling). We built dataset using this scheme: [CLS] TEXT [SEP] COMMENT [SEP]    
so this token responds to connection between TEXT and COMMENT    
![image](https://user-images.githubusercontent.com/10894740/229026357-5a22a128-776f-42b5-b076-dde431569e25.png)



