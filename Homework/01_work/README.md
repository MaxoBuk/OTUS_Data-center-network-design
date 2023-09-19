## Проектирование адресного пространства

### Задачи:

- Собрать схему CLOS;
- Распределить адресное пространство.

## Выполнение:

### Собранная схема сети

![](https://github.com/MaxoBuk/OTUS_Data-center-network-design/blob/main/Homework/01_work/images/topology.jpeg)

---

### Таблица адресов


| hostname | interface |   IP/MASK   |
| :------: | :-------: | :----------: |
|  leaf-1  | Loopback2 | 10.2.0.1 /32 |
|  leaf-1  |  eth 1/1  | 10.4.1.1 /31 |
|  leaf-1  |  eth 1/2  | 10.4.2.1 /31 |
|          |          |              |
|  leaf-3  | Loopback2 | 10.2.0.3 /32 |
|  leaf-3  |  eth 1/1  | 10.4.1.3 /31 |
|  leaf-3  |  eth 1/2  | 10.4.2.3 /31 |
|          |          |              |
|  leaf-5  | Loopback2 | 10.2.0.5 /32 |
|  leaf-5  |  eth 1/1  | 10.4.1.5 /31 |
|  leaf-5  |  eth 1/2  | 10.4.2.5 /31 |
|          |          |              |
| spine-1 | Loopback1 | 10.1.1.0/32 |
| spine-1 |  eth 1/1  | 10.4.1.0/31 |
| spine-1 |  eth 1/2  | 10.4.1.2/31 |
| spine-1 |  eth 1/3  | 10.4.1.4/31 |
|          |          |              |
| spine-2 | Loopback1 | 10.1.2.0/32 |
| spine-2 |  eth 1/1  | 10.4.2.0/31 |
| spine-2 |  eth 1/2  | 10.4.2.2/31 |
| spine-2 |  eth 1/3  | 10.4.2.2/31 |

### Конфигурация оборудования

- #### leaf-1

```
config
```

- #### leaf-2

```
config
```

- #### leaf-3

```
config
```

- #### spine-1

```
config
```

- #### spine-2

```
config
```