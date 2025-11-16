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

### Доработка после проверки
Показывает этот сертификат для моего бакета, который доступен на 158-160-175-162.nip.io
<img width="1919" height="965" alt="image" src="https://github.com/user-attachments/assets/1978d198-6019-4ed5-a9ad-244c67163a7b" />
<img width="1673" height="739" alt="image" src="https://github.com/user-attachments/assets/c5ad157f-60b7-4e0c-b170-677ba90ccb40" />

Добавил свой сертификат для бакета
<img width="1919" height="914" alt="image" src="https://github.com/user-attachments/assets/58dae337-0b7f-4f9e-bb1a-3bd8e0db3a40" />

