
### El titulo, script SQL y capturas de las sentencias elaborar en archivo formato MARKDOWN y subir en un repositorio de GIT.

Titulo
![[Pasted image 20240522193044.png]]

Sentencias de creación de las tablas y inserción de datos
![[Pasted image 20240522192727.png]]

![[Pasted image 20240522192850.png]]


SELECT *
FROM register
WHERE asisted = 'True';

![[Captura de pantalla 2024-05-22 173145.png]]

SELECT *
FROM member
WHERE age > 30 AND age < 40

![[Captura de pantalla 2024-05-22 173702.png]]


SELECT *
FROM member
WHERE age > 30
AND email = 'john.smith@email.com';

![[Captura de pantalla 2024-05-22 174426.png]]

SELECT *
FROM conference
ORDER BY day;

![[Pasted image 20240522193700.png]]

SELECT *
FROM event
WHERE total_attendees > 100
AND start_date = '2024-09-15';

![[Pasted image 20240522193753.png]]