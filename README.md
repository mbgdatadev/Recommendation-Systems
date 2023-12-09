# Recommendation-Systems
***
- [Recommendation Systems Nedir?](#recommendation-systems-nedir)
- [Association Rule Learning Nedir?](#association-rule-learning-nedir)
- [Content Based Filtering Nedir?](#content-based-filtering-nedir)
- [Item Based Collaborative Filtering Nedir?](#item-based-collaborative-filtering-nedir)

***
## **Recommendation Systems Nedir?**

Recommendation Systems (Öneri sistemleri), kullanıcılara belirli ürünleri, içerikleri veya hizmetleri öneren ve tavsiye eden algoritmalar veya yazılım araçlarıdır. Bu sistemler, genellikle kullanıcıların geçmiş tercihleri, davranışları veya benzer kullanıcıların tercihleri gibi verileri kullanarak kişiselleştirilmiş öneriler sunarlar. Öneri sistemleri, e-ticaret sitelerinde, video akış platformlarında, müzik uygulamalarında ve daha birçok alanda kullanıcı deneyimini geliştirmek ve kullanıcılara daha uygun içerikleri sunmak için kullanılır.
***
## **Association Rule Learning Nedir?**

Association Rule Learning (İlişki Kural Öğrenimi), veri madenciliği ve makine öğrenimi alanında kullanılan bir tekniktir. Bu teknik, veri kümelerindeki ilişkileri ve bağlantıları belirlemek için kullanılır. Özellikle büyük veri setlerinde, birlikte sıkça görülen öğeler arasındaki ilişkileri tanımlamak amacıyla kullanılır.

Bu teknik, genellikle "eğer X, o zaman Y" şeklinde ifade edilen kuralları ortaya çıkarır. Örneğin, bir market alışverişi veri setinde, "Müşteri A, X ve Y ürünlerini satın aldığında genellikle Z ürününü de alır" gibi kurallar çıkarılabilir. Bu kural tabanlı öğrenme yöntemi, özellikle öneri sistemleri ve pazarlama stratejilerinde kullanılarak veri analitiği süreçlerine değer katar.

 - **Apriori Algoritması Nedir?**

   Apriori, Association Rule Learning (İlişki Kural Öğrenimi) için kullanılan bir algoritmadır. Büyük veri setlerinde sıkça görülen öğeler arasındaki ilişkileri belirlemek için kullanılır. Temel amacı, belirli 
   bir destek ve güvene dayalı olarak öğe kümeleri arasındaki ilişkileri ortaya çıkarmaktır.

   Algoritma, veri setindeki öğelerin sıklıklarını analiz ederek, bu öğeler arasında sıkça görülen kombinasyonları tespit eder. Örneğin, bir market veri setinde sıkça birlikte satın alınan ürün gruplarını 
   belirlemek için kullanılabilir.

   Apriori algoritması, "minsup" ve "minconf" gibi parametrelerle belirlenen destek ve güven eşik değerlerine göre çalışır. Destek, belirli bir öğe kümesinin ne sıklıkta görüldüğünü ifade ederken, güven ise bu 
   kümeler arasındaki ilişkinin ne kadar güvenilir olduğunu belirtir.

   Bu algoritma, market sepet analizi gibi birçok alanda kullanılarak öneri sistemleri ve veri madenciliği çalışmalarında önemli bir rol oynar.

***
## **Content Based Filtering Nedir?**

Content Based Filtering (İçerik tabanlı filtreme), öneri sistemlerinde kullanılan bir yöntemdir. Bu yöntemde, kullanıcıların geçmiş tercihleri ve beğenileri temel alınarak, içerikler arasındaki benzerlikler kullanıcılara önerilir. Özellikle bir öğenin içeriği veya özellikleri dikkate alınarak benzer içeriklere sahip diğer öğeler önerilir.
***
## **Item Based Collaborative Filtering Nedir?**

Item Based Collaborative Filtering (Öğe odaklı işbirlikçi filtreleme), öneri sistemlerinde kullanılan bir yöntemdir. Bu yöntemde, kullanıcıların benzer öğeleri beğenme eğilimlerine dayalı olarak öğeler arasındaki benzerlikler incelenir ve kullanıcılara öneriler sunulur.

Bu yöntemde, öğeler arasındaki benzerlik genellikle kullanıcı tercih matrisi üzerinden hesaplanır. Özellikle, bir öğenin diğer öğelerle olan benzerlik derecesi, kullanıcıların bu öğeleri nasıl değerlendirdiğine dayalı olarak belirlenir.

Item Based Collaborative Filtering, öğeler arasındaki ilişkileri belirleyerek kullanıcıların ilgisini çekebilecek öğeleri tavsiye etmeyi amaçlar. Kullanıcıların tercihlerine dayalı olarak benzer öğeleri bulma ve önerme sürecinde etkilidir.

Bu yöntemde, öğeler genellikle bir dizi özellik veya etiketle temsil edilir. Örneğin, bir film için tür, yönetmen, oyuncular gibi özellikler kullanılabilir. Kullanıcının daha önce beğendiği bir film, aynı türde veya aynı yönetmene sahip olan diğer filmler tarafından önerilebilir.

Content Based Filtering, kullanıcıların kişisel tercihlerini dikkate alarak önerilerde bulunabilen bir öneri sistemi yöntemidir. Özellikle içeriğin niteliklerine dayalı olarak önerilerde bulunmasıyla dikkat çeker.

***
## **User Based Collaborative Filtering Nedir?**

User Based Collaborative Filtering (Kullanıcı odaklı işbirlikçi filtreleme), öneri sistemlerinde kullanılan bir yöntemdir. Bu yöntemde, bir kullanıcının benzerliklerini diğer kullanıcılara göre değerlendirerek öneriler yapılır.

Bu yöntemde, kullanıcılar arasındaki benzerlikler genellikle kullanıcı tercih matrisi üzerinden hesaplanır. Özellikle, bir kullanıcının diğer kullanıcılarla benzer öğeleri nasıl değerlendirdiği üzerinden benzerlik dereceleri belirlenir.

User Based Collaborative Filtering, bir kullanıcının geçmiş tercihleri ve davranışlarına dayanarak benzer kullanıcıların beğendiği öğeleri önermeyi amaçlar. Bu sayede, bir kullanıcının ilgisini çekebilecek öğeleri bulmak ve önermek için benzer kullanıcıların tercihleri dikkate alınır.
***
## **Model Based Matrix Factorization Nedir?**

Model Based Matrix Factorization (Model tabanlı matris çözümleme), öneri sistemlerinde kullanılan bir yöntemdir. Bu yöntemde, büyük boyutlu kullanıcı-öğe tercih matrislerini küçük boyutlu faktör matrislerine dönüştürerek öneriler oluşturulur.

Bu yöntemde, matrisler arasındaki boşlukları doldurmak için modelleme teknikleri kullanılır. Özellikle, matris faktörizasyonu gibi tekniklerle büyük tercih matrisleri daha küçük boyutlu matrislere ayrıştırılır ve bu faktörler arasındaki ilişkiler modelde kullanılır.

Model Based Matrix Factorization, öneri sistemlerinde büyük veri setlerini işlerken verimlilik sağlar ve eksik bilgileri tahmin eder. Bu yöntem, kullanıcı tercihleri ve öğe özellikleri arasındaki ilişkileri belirleyerek önerilerde bulunur.

