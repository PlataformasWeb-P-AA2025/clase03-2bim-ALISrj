### Qué pasa si en el modelo no tenemos un related_name

![image](https://github.com/user-attachments/assets/7290c950-f6b6-42c0-9b65-c4ed122c1c8f)

En el momento de crear la foreign key en la tabla NumeroTelefonico, para hacer la relación con la tabla estudiante, no escribimos un related_name (el cual nos permite acceder a los objetos referenciados por la relación como si fueran otro atributo). Cuando no escribimos un related_name, el valor por defecto siempre será el nombre de la clase en minúscula más guión bajo seguido de la palabra "set", en este caso el related_name es numerotelefonico_set
