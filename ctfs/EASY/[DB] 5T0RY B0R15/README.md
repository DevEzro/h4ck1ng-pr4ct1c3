<h4>
La base de datos de la película 'Story Boris' 
ha sido modificada sin autorización por un usuario
ajeno a la empresa. Ha cambiado la contraseña del usuario
'admin' de la base de datos y para colmo ha añadido datos inecesarios
en las tablas. Encuéntralos</h4>

> [!TIP] #1: El enunciado ya te ha dado una
  
> [!TIP] #2: Pr83b44854rh1dr4

> [!TIP] #3: La clave está en las tablas


#### Despliegue en local
`docker build -t story_boris .`
`docker run -d -p 5432:5432 --name story_boris_container story_boris`
