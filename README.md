# SQL-ODEV-12
Patika.dev > SQL > ALT Sorgular > Ödev12

## 1. film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

      SELECT COUNT(*) FROM film
      WHERE length > (SELECT AVG(length) FROM film);
 
## 2. film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?

      SELECT COUNT(*) FROM film
      WHERE rental_rate = (SELECT MAX(rental_rate) FROM film);

## 3. film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.



## 4. payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.


