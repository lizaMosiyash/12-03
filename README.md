# Домашнее задание к занятию "`SQL. Часть 1`" - `Солдатенкова Елизавета`

---

### Задание 1

```
select DISTINCT  district from address where district LIKE 'k%a'and district not like '% %';
```

![1](https://github.com/lizaMosiyash/12-03/blob/master/screenshots/1.PNG)


---

### Задание 2

```
select * from payment where payment_date between '2005-06-15' and '2005-06-19' and amount > 10.00;
```

![2](https://github.com/lizaMosiyash/12-03/blob/master/screenshots/2.PNG)


---

### Задание 3

```
select * from rental order by rental_id desc limit 0,5;
```

![3](https://github.com/lizaMosiyash/12-03/blob/master/screenshots/3.PNG)


---

### Задание 4

```
select lower(last_name), lower(replace(first_name, 'LL', 'PP')) from customer where active=1 and first_name in ('Kelly', 'Willie');
```

![4](https://github.com/lizaMosiyash/12-03/blob/master/screenshots/4.PNG)


---

