Parte 5:



1\. ¿El merge fue fast-forward?

&#x20;  Sí, fue fast-forward.



2\. ¿Por qué Git no necesitó crear un merge commit?

&#x20;  Porque `main` no tenía cambios nuevos y Git solo avanzó la rama hasta 

el último commit de feature/perfil.



Parte 6:



1\. ¿Qué diferencia observa respecto al merge anterior?

&#x20;  En el anterior solo se avanzó la rama, pero

&#x20;con --no-ff` se creó un merge commit.



2\. ¿Aparece un commit especial de merge?

&#x20;  Sí, aparece un commit que representa la unión de las dos ramas.



REFLEXIÓN Y ENTREGA:



1\. ¿Qué diferencia existe entre un commit normal y un amend?

&#x20;  Un commit guarda cambios nuevos y `amend` permite corregir el último commit.



2\. ¿Cuándo se produjo el fast-forward?

&#x20;  Cuando se unió la rama `feature/perfil` con `main`.



3\. ¿Para qué sirve la opción --no-ff?

&#x20;  Sirve para crear un commit de merge y mostrar la unión de las ramas.



4\. ¿Qué significa que exista un conflicto?

&#x20;  Que Git encontró cambios diferentes en la misma parte de un archivo y debemos elegir cuál dejar.



5\. ¿Cómo se resolvió el conflicto de config.txt?

&#x20;  Se eliminaron los marcadores del conflicto y se dejó el puerto en `3000`.



6\. ¿Qué parte del laboratorio presentó mayor dificultad?

&#x20;  Resolver el conflicto, porque fue necesario revisar y elegir manualmente el cambio correcto.



