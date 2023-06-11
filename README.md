#создал таблицу
id_mobile_phones,models_mobile_phones,manufacturers_phones,prices_phones,quantity_phones
1,"Galaxy S22 Ultra",Samsung,91575,2
2,"Galaxy A03 4/64 Gb",Samsung,7451,1
3,"Galaxy Note20 Ultra 12/256 Gb",Samsung," 12395"," 50"
4,"iPhone 11 128 Gb', 'Apple",Apple,37453,1
5,"iPhone 13 128 Gb",Apple,52544,72
6,"Redmi Note 10 Pro 6/128 Gb",Xiaomi," 17566",88
Выведите весь ассортимент товаров марки “Samsung”
SELECT * FROM mobile_phones
WHERE manufacturers_phones = 'Samsung';
Выведите название, производителя и цену для товаров, количество которых превышает 2
SELECT models_mobile_phones, manufacturers_phones, prices_phones 
FROM mobile_phones
WHERE quantity_phones > 2;
