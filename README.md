## Задание 1. Yandex Cloud   

1. С помощью ключа в KMS необходимо зашифровать содержимое бакета:

 - создать ключ в KMS;
   <img width="1855" height="698" alt="image" src="https://github.com/user-attachments/assets/38bd35d5-6a8f-412c-b92b-986c60070d0d" />
 - с помощью ключа зашифровать содержимое бакета, созданного ранее.
   <img width="1850" height="529" alt="image" src="https://github.com/user-attachments/assets/03d2a89f-d7fb-4e4e-9905-fb4b0724154b" />

2. (Выполняется не в Terraform)* Создать статический сайт в Object Storage c собственным публичным адресом и сделать доступным по HTTPS:

 - создать сертификат;
   <img width="1865" height="652" alt="image" src="https://github.com/user-attachments/assets/c5edf0fe-12d3-42c2-bdd5-3023482cc2ae" />
   <img width="1603" height="569" alt="image" src="https://github.com/user-attachments/assets/c91e7b8d-5835-4500-a6d3-8eea38a3ad5f" />
  <img width="1179" height="661" alt="image" src="https://github.com/user-attachments/assets/6a2dffa5-16b3-44c9-bdd5-6b0bf8f70d31" />
  <img width="1265" height="760" alt="image" src="https://github.com/user-attachments/assets/c87e1704-f6f7-4239-bbaf-cca627e64983" />

 - создать статическую страницу в Object Storage и применить сертификат HTTPS;
 - в качестве результата предоставить скриншот на страницу с сертификатом в заголовке (замочек).
Создал новый бакет, попробывал на него сделать.

Показывает этот сертификат 
<img width="1919" height="1029" alt="image" src="https://github.com/user-attachments/assets/3c38ff36-5eb6-401c-a67d-4c986b10cb39" />


Создал сертфикаты использовал и HTTP и DNS, прошло уже более 2 суток и так валидация не прошла.
<img width="1879" height="994" alt="image" src="https://github.com/user-attachments/assets/0b89747b-3b93-4cea-a2f7-ede4964cae3c" />
<img width="1878" height="997" alt="image" src="https://github.com/user-attachments/assets/9f1e3c8b-6525-4b5b-aeef-3d78199f1c2d" />
