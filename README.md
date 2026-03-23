# Olá, sou o Vinicius Adriano Pereira!

## **Introdução**

Sou **estudante** do **2º ano** do **ensino médio** e atualmente estou **aprendendo Java**.

**Gosto** de **trabalhar** com a parte do **backend com** as **ferramentas** ☕**Java** + 🍃**Spring framework** e **Banco de dados**.

## ***Conecte-se comigo***
[![LinkedIn](https://img.icons8.com/?size=60&id=xuvGCOXi8Wyg&format=png&color=000000)](https://www.linkedin.com/in/viniciusadrianopereira/)
[![GitHub](https://img.icons8.com/?size=60&id=12598&format=png&color=FFFFFF)](https://github.com/ViniciusAp08)

## **Habilidades**

[![GitHub](https://img.icons8.com/?size=60&id=12598&format=png&color=FFFFFF)](https://github.com/ViniciusAp08)
![Git](https://img.icons8.com/?size=60&id=6Qr2kBSBemvq&format=png&color=000000)
![Java](https://img.icons8.com/?size=60&id=13679&format=png&color=000000) 
![Spring Framework](https://img.icons8.com/?size=60&id=90519&format=png&color=000000)
![SQL](https://img.icons8.com/?size=60&id=dwJoQUjh5qoh&format=png&color=6167FF)

||
|-----|
|GitHub [![GitHub](https://img.icons8.com/?size=25&id=12598&format=png&color=FFFFFF)](https://github.com/ViniciusAp08)|
|Git ![Git](https://img.icons8.com/?size=25&id=6Qr2kBSBemvq&format=png&color=000000)|
|Java ![Java](https://img.icons8.com/?size=25&id=13679&format=png&color=000000) |
|Spring Framework ![Spring Framework](https://img.icons8.com/?size=25&id=90519&format=png&color=000000)|
|Banco de Dados SQL ![SQL](https://img.icons8.com/?size=25&id=dwJoQUjh5qoh&format=png&color=6167FF)|

```
import java.time.LocalDateTime;
import java.time.format.DateTimeFormatter;

public class main {
    public static void main (String[] args){    
        LocalDateTime date = LocalDateTime.now();
        DateTimeFormatter dateFormatter; 
        dateFormatter = DateTimeFormatter.ofPattern
        ("dd/MM/yyyy HH:mm:ss");
        
        System.out.println("Hello, world!);
        System.out.println("Data e hora de Hoje: + 
        date.format(dateFormatter));
    }
}
```

```
SELECT
    *
FROM
    car_features as cf
WHERE
    cf.id = 5
ORDER BY
    cf.color desc
```