1-¿Existe el link en la imagen en la rama master?
Primero se sube la carpeta git_landing_MO_G68 a github, con los links rotos. Luego se crea una nueva rama feature-1 y en esa rama se trabaja y se arreglan los links. Finalmente se 
se vuelve a la rama master con git checkout master, y desde alli se hace un merge con el comando git merge feature-1 para que la rama master quede al dia con la rama feature-1 y los links 
queden redireccionando a github.com .
