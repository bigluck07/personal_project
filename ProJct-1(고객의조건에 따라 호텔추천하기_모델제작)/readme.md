# π sec4_project_recommend_hotel_in_spain
- νΈνμμ½ λ° λ¦¬λ·° λ°μ΄ν°λ₯Ό μ¬μ©νμ¬ κ³ κ°λ€μ΄ μνλ μ‘°κ±΄μ νΈνμ μΆμ²νλ λͺ¨λΈμ μ μνλ€.

- λ°μ΄ν°μμ λͺλͺ μΉΌλΌμ λ½μ λͺ¨λΈμ λ§λ€κ³ , κ³ κ°μ νκ·Έμ λ°λΌ νΈν μ€ κ°μ₯λ§μ λ¦¬λ·°λ₯Ό λ³΄μ ν νΈν μμ 5κ³³μ μλ €μ£Όκ³ , κ³ κ°μ΄ μνλ νΈνμ μ‘°κ±΄(μ«μ΄νλμ‘°κ±΄, μ’μνλμ‘°κ±΄)μ μμ°μ΄ μ²λ¦¬λ₯Ό ν΅ν΄ κ°μ₯ λΉμ·ν λ¦¬λ·°λ₯Ό κ°μ§ νΈν 5κ°μ©μ μλ €μ£Όλ λͺ¨λΈμ΄λ€.

## π Data
### λ°μ΄ν° λ΄μ©
- ν΄λΉ λ°μ΄ν°λ μΊκΈμ [515K Hotel Reviews Data in Europe](https://www.kaggle.com/jiashenliu/515k-hotel-reviews-data-in-europe)
μμ λ°μμμ΅λλ€.

- μ νμ΄μ§μμ μκ°νκΈ°λ‘λ Booking.comμμ μ€ν¬λ© λμλ€κ³  νλ©°, μ λ½μ 1493κ°μ λ­μλ¦¬νΈνλ€μ λν 515,000κ°μ λ¦¬λ·°λ₯Ό λ°μ΄ν°λ‘ κ°μ§κ³  μλ€κ³  νλ€.

- 515,000κ°μ λ°μ΄ν° μ€ 'Spain'μ 'Barcelona'μ μλ νΈνλ€μ 2016~2017λ λ°μ΄ν°λ‘λ§ νλ‘μ νΈλ₯Ό μ§ννκ³ μ νλ€.(60149κ°μ λ°μ΄ν°)

### λ°μ΄ν° μ μ μ΄μ 
- ν΄λΉ λ°μ΄ν°λ₯Ό ν΅ν΄ κ³ κ°λ€μ΄ μνλ νΈνμ μΆμ²νκ³ μ νλ€.
  - μ¬μ©μλ νΈνμ μ ν μ¦ μ¬νλͺ©μ , λ£Έμ»¨λμ λ±μ μ ννκ³  μμ μ΄ μ°Ύκ³ μ νλ νΈν νΉμ κ°κ³ μΆμ§ μμ νΈνμ μ‘°κ±΄μ μΆκ°μ μΌλ‘ κΈ°μνμ¬ κ³ κ°γ·γΉμ΄ νΈνμ μ ννκ³  μμ½νλλ° λμμ μ€ μ μμκ²μ΄λΌ μκ°ν©λλ€.

- "μ΄λ€ νμ¬μμ λμ΄ μ΄ μ μμκΉ?"
   - ν΄λΉ λ°μ΄ν°κ° 'νΈν'μ κ΅­νλμ΄ μμ§λ§, κ³ κ°μκ² μ νμ νλ§€νκ±°λ, κ³ κ°μ μκ΅¬λ₯Ό νμνμ¬ μνμ μΆμ²νλ μλΉμ€λ₯Ό μ κ³΅νκ³ μ νλ νμ¬λΌλ©΄ λΉμ·ν λ°μ΄ν°λ₯Ό κ°μ§κ³  μμκ²½μ° μ¬μ©λ  μ μμ κ²μ΄λΌ μκ°νλ€. 

- "μ΄λ νμ¬μ μ΄λλΆλΆμ μ μ©ν΄ λ³Ό μ μμκΉ"
  - "νΈνμμ½μλΉμ€λ₯Ό μ κ³΅νλ νμ¬μ νΈνμΆμ² μλΉμ€, μ ν΅νλ§€μμ κ°μ μνλ₯ λ³ μΆμ²μνμ μ κ³΅νλ μλΉμ€ λ±"

## κ°μ€
- νΈνμ μ΄μ©ν κ³ κ°λ€μ λ¦¬λ·°λ₯Ό λΆμνμ¬ νΈνμΆμ² μλΉμ€λ₯Ό μ΄μ©νλ €λ κ³ κ°λ€μ λμ¦μ λ§μΆ°μ νΈνμ μΆμ²νμ¬ κ³ κ°μ νΈλ¦¬μ±μ λν μ μμ κ²λ€
- λ¦¬λ·°λ€μ μμ°μ΄μ²λ¦¬λ₯Ό ν΅ν΄ λΆμνμ¬ k-nnλͺ¨λΈμ ν΅ν΄ κ°μ₯ κ·Όμ ν λ¬Έμλ₯Ό μ°Ύκ³  ν΄λΉ λ¬Έμμ ν΄λΉνλ νΈνμ μ΄λ¦μ λ½μ μΆλ ₯ν  μ μμκ²μ΄λ€.
- μΆκ°μ μΌλ‘ μλΉμ€μ λ±λ‘λ νΈν λν νμ¬μ κ³ κ°μ΄λΌ μκ°μ΄ λκΈ°μ, κ° νΈνλ³ λ°μ λ¦¬λ·°μ μμ 10κ°μ λ¨μ΄λ€μ μ κ³΅ν  μ λ μμ κ²μ΄λ€.(μΌλ¨μ μ μ²΄νΈνμ 10κ° λ¨μ΄λ§ μΆλ Έμ΅λλ€.)

## π  Columns
- νΉμ±μ€λͺ
  - Hotel_Address: νΈνμ£Όμ
  - Review_Date: λ¦¬λ·°ν λ μ§
  - Average_Score: νΈνμ νκ·  μ μ(μ§λν΄ μ΅μ  μ½λ©νΈλ₯Ό κΈ°λ°μΌλ‘ κ³μ°λ¨)
  - Hotel_Name: νΈνμ΄λ¦
  - Reviewer_Nationality: λ¦¬λ·°μ΄μ κ΅­μ 
  - Negative_Review: λΆμ μ  λ¦¬λ·°. μμ κ²½μ° 'No Negative'λ‘ νκΈ°
  - ReviewTotalNegativeWordCounts: λΆμ μ  λ¦¬λ·°μ μ¬μ©λ μ΄ λ¨μ΄μ μ
  - Positive_Review: κΈμ μ  λ¦¬λ·°. μμ κ²½μ° 'No Positive'λ‘ νκΈ°
  - ReviewTotalPositiveWordCounts: κΈμ μ  λ¦¬λ·°μ μ¬μ©λ μ΄ λ¨μ΄μ μ
  - Reviewer_Score: λ¦¬λ·° μ μ
  - TotalNumberofReviewsReviewerHasGiven: λ¦¬λ·°μ΄μ μ§λ λ¦¬λ·°λ€μ κ°―μ
  - TotalNumberof_Reviews: νΈνμ΄ κ°μ§ λ¦¬λ·°μ μ
  - Tags: λ¦¬λ·°μ΄κ° νΈνμ λ¨ νκ·Έ
  - dayssincereview: κ²ν  λ μ§μ μ€ν¬λν λ μ§ μ¬μ΄μ κΈ°κ°μλλ€.
  - AdditionalNumberof_Scoring: ν¬μκ°λ€μ μν νΈνμ νκ°μ μ(λ¦¬λ·°λ₯Ό μμ±νμ§ μμ νκ°μλ μ‘΄μ¬)
  - lat: νΈνμ μλ
  - lng: νΈνμ κ²½λ


- μ¬μ©ν  νΉμ±
  - Hotel_Address, Hotel_Name, Negative_Review, Positive_Review, Tags


## μ μ²λ¦¬ κ³Όμ 
- 'Tags' νΌμ²μμ μλ°λͺ©μ , μΈμ, λ°©κ·λͺ¨ λΆλ¦¬νκΈ°
  - 'Tags'νΉμ±μ μλ¬Έμλ‘ λ§λ€κ³  ```re.sub```μ μ¬μ©ν μ μ²λ¦¬λ‘ κ΅¬λΆνκΈ° νΈνκ² λ§λ¬ 
    - ' , ' κΈ°μ€μΌλ‘ κ΅¬λΆμ§κ³  μλ‘μ΄ νΉμ±μΌλ‘ μμ± ν κΈ°μ‘΄ 'Tags'μ­μ 
  - μΈμ, λ°©κ·λͺ¨λ λ°μ΄ν°κ° λλ¬΄ μ§μ λΆ νμ¬ μ μΈν¨(μΆν μ μ ν΄μ μ‘°κ±΄μΌλ‘ μΆκ°ν  μ μλλ‘ ν  μμ )



- λ¦¬λ·°λ€μ ν ν°ν
  - μλ¬Έμν λ° λΆμ©μ΄μ²λ¦¬
    - λΆμ©μ΄λ 'spacy.load("en_core_web_sm")'λ₯Ό μ¬μ©νμΌλ, μ»€μ€ν°λ§μ΄μ§μ ν΅ν΄ λμ± μ νμ±μ λν
  - νμ μ΄μΆμΆ

- κ°μ νΈνλ¦¬λ·° ν©μ³μ νΈνλ€μ λ¦¬λ·° λ¦¬μ€νΈλ‘ λ§λ€κΈ°
  - κ°μνΈνμ λ¦¬λ·°λ 'Negative_Review', 'Positive_Review'λ‘ μμ°μ΄μ²λ¦¬λ₯Ό ν  μ μλλ‘ λ¦¬μ€νΈν ν¨
  - μ¦, νλμ νΈνμ κ°κ° ν κ°μ 'Negative_Review', 'Positive_Review'λ₯Ό κ°μ§


## λ°μ΄ν° λΆμ 
- μ μ²΄νΈνλ€μ λ¦¬λ·°λ€μ λΆμνμ¬ μμ 10κ°μ λ¨μ΄λ₯Ό μ μ ν¨
  - Negative_Review
  
    <img width="351" alt="αα³αα³αα΅α«αα£αΊ 2021-07-01 αα©αα? 7 16 26" src="https://user-images.githubusercontent.com/73811590/124108080-d64e2480-daa0-11eb-9e19-3eb73d53b934.png">
    
  - Positive_Review
  
    <img width="361" alt="αα³αα³αα΅α«αα£αΊ 2021-07-01 αα©αα? 7 16 49" src="https://user-images.githubusercontent.com/73811590/124108127-e403aa00-daa0-11eb-9aec-29555a5dfbc3.png">
    
- λ¦¬λ·°μ’λ₯ λ³ μ΄ λ¨μ΄μ κ°μ
  - Negative_Review


    ![image](https://user-images.githubusercontent.com/73811590/124109448-1a8df480-daa2-11eb-8af1-77e778df4084.png)
 
 
  - Positive_Review


    ![image](https://user-images.githubusercontent.com/73811590/124109463-1e217b80-daa2-11eb-89a1-181f1b66b0d5.png)


## π₯οΈ Model
-  Tf-IDF
```
# spacy tokenizer ν¨μ
def tokenize(document):
    
    doc = nlp(document)
    # punctuations: !"#$%&'()*+,-./:;<=>?@[\]^_`{|}~
    return [token.lemma_.strip() for token in doc if (token.is_stop != True) and (token.is_punct != True) and (token.is_alpha == True)]
    
# Tf-IDF
N_tfidf = TfidfVectorizer(stop_words='english'
                        ,tokenizer=tokenize
                        ,ngram_range=(1,2)
                        ,max_df=.7
                        ,min_df=3
                        ,max_features = 20000
                       )
P_tfidf = TfidfVectorizer(stop_words='english'
                        ,tokenizer=tokenize
                        ,ngram_range=(1,2)
                        ,max_df=.7
                        ,min_df=3
                        ,max_features = 20000
                       )
Negative_Review_dtm = N_tfidf.fit_transform(Negative_Review)
Negative_Review_dtm = pd.DataFrame(Negative_Review_dtm.todense(), columns=N_tfidf.get_feature_names())
print(Negative_Review_dtm.head())

Positive_Review_dtm = P_tfidf.fit_transform(Positive_Review)
Positive_Review_dtm = pd.DataFrame(Positive_Review_dtm.todense(), columns=P_tfidf.get_feature_names())
print(Positive_Review_dtm.head())
```

- μ μ¬λλ₯Ό μ΄μ©ν λ¬Έμκ²μ(NearestNeighbor (K-NN, K-μ΅κ·Όμ  μ΄μ))
```
# NearestNeighbor (K-NN, K-μ΅κ·Όμ  μ΄μ)
from sklearn.neighbors import NearestNeighbors

# dtmμ μ¬μ©ν NN λͺ¨λΈμ νμ΅μν΅λλ€. (λν΄νΈ)μ΅κ·Όμ  5 μ΄μ.
Negative_Review_nn = NearestNeighbors(n_neighbors=5, algorithm='kd_tree')
Negative_Review_nn.fit(Negative_Review_dtm)

Positive_Review_nn = NearestNeighbors(n_neighbors=5, algorithm='kd_tree')
Positive_Review_nn.fit(Positive_Review_dtm)
```

### μΆκ°κΈ°λ₯
```
# ['travel_perpos']μ ν΅ν΄μ ν΄λΉ μ νμμ κ°μ₯ λ§μ΄ μμ½λ μμ 5κ°μ νΈν μλ €μ£ΌκΈ°
def top5_hotel_by_travel_perpos(data, travel_perpos):
  travel_perpos_ls = data['travel_perpos'].unique()
  hotel_list = data['Hotel_Name'].unique()
  dic = {}
  for i in hotel_list:
    s = data[data['Hotel_Name']==i]['travel_perpos']=='travel_perpos'
    dic[i]=s.count()
  top5 = sorted(dic.items(), key=lambda x: x[1], reverse=True)[0:5]
  print(f"μλ ₯λ μλ°λͺ©μ μ '{travel_perpos}'μ΄λ©°, ν΄λΉ λͺ©μ μΌλ‘ κ°μ₯λ§μ΄ μ΄μ©λ μμ5κ° νΈνκ³Ό μ΄μ©μ μ λ λ€μκ³Ό κ°μ΅λλ€. ")
  return top5

# μ¬μ©μμ μ‘°κ±΄μ λ°λΌ νΈν μΆμ²νκΈ°
def kneighbors(data, Negative, Positive):
  hotel_list = data['Hotel_Name'].unique()
  test_N = N_tfidf.transform(Negative)
  test_P = P_tfidf.transform(Positive)
  Negative_kneighbors=Negative_Review_nn.kneighbors(test_N.todense())[1][0]
  Positive_kneighbors=Positive_Review_nn.kneighbors(test_P.todense())[1][0]
  print(f"μλ ₯λ μ«μ΄νλ νΈνμ‘°κ±΄μ\n {Negative}\nμ΄λ©°, μλ ₯λ μ‘°κ±΄κ³Ό λΉμ·ν λ¦¬λ·°κ° μλ νΈνμ λ€μκ³Ό κ°μ΅λλ€.")
  for i in hotel_list[Negative_kneighbors]:
    print(i)
  print("\n")
  print(f"μλ ₯λ μ νΈνλ νΈνμ‘°κ±΄μ\n {Positive}\nμ΄λ©°, μλ ₯λ μ‘°κ±΄κ³Ό λΉμ·ν λ¦¬λ·°κ° μλ νΈνμ λ€μκ³Ό κ°μ΅λλ€.")
  for i in hotel_list[Positive_kneighbors]:
    print(i)
  return
```

# λͺ¨λΈ μ±λ₯ νμΈ
μ΄μ©μ1
- μ¬νλͺ©μ : 'solotraveler'
- μ«μ΄νλ νΈνμ‘°κ±΄: 'bug, nosie, unkind staff'
- μ’μνλ νΈνμ‘°κ±΄: 'nice step, good breakfast and pool'

- μ‘°κ±΄ μλ ₯

```
user1 = {
    'travel_perpos':input("travel_perpos?:"),
    'n1':[input("negative_r?: ")],
    'p1':[input("positive_r?: ")]
    }
 >>> solotraveler
 >>> bug, nosie, unkind staff
 >>> nice step, good breakfast and pool
```

- μ¬νλͺ©μ μ λ°λ₯Έ μμ νΈν 5κ°
```
top5_hotel_by_travel_perpos(df, user1['travel_perpos'])
```
 - μλ ₯λ μλ°λͺ©μ μ 'solotraveler'μ΄λ©°, ν΄λΉ λͺ©μ μΌλ‘ κ°μ₯λ§μ΄ μ΄μ©λ μμ5κ° νΈνκ³Ό μ΄μ©μ μ λ λ€μκ³Ό κ°μ΅λλ€. 
    - [('Eurostars Grand Marina Hotel GL', 1082),
    - ('Catalonia Atenas', 1061),
    - ('Catalonia Plaza Catalunya', 964),
    - ('Catalonia Barcelona Plaza', 932),
    - ('Barcelona Princess', 897)]
 
 
- μ μν μ‘°κ±΄μ λ°λ₯Έ μΆμ²νΈν λ° λΉμΆμ² νΈν
```
kneighbors(df, user1['n1'], user1['p1'])
```
  - μλ ₯λ μ«μ΄νλ νΈνμ‘°κ±΄μ
 ['bug, nosie, unkind staff']
μ΄λ©°, μλ ₯λ μ‘°κ±΄κ³Ό λΉμ·ν λ¦¬λ·°κ° μλ νΈνμ λ€μκ³Ό κ°μ΅λλ€.
    - Catalonia Passeig de Gr cia 4 Sup
    - Eurohotel Diagonal Port
    - H10 Port Vell 4 Sup
    - Ilunion Bel Art
    - Hotel Omm


  - μλ ₯λ μ νΈνλ νΈνμ‘°κ±΄μ
 ['nice step, good breakfast, pool']
μ΄λ©°, μλ ₯λ μ‘°κ±΄κ³Ό λΉμ·ν λ¦¬λ·°κ° μλ νΈνμ λ€μκ³Ό κ°μ΅λλ€.

    - Catalonia Barcelona Plaza
    - Catalonia Ramblas 4 Sup
    - Catalonia Park Putxet
    - Novotel Barcelona City
    - Grand Hotel Central
