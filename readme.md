- ¿Qué comando utilizaste en el paso 11? ¿Por qué?

**git reset --hard HEAD~1 , HEAD~1 para volver al commit ancestro y hard para descartar los cambios del commit tiene el coomit reseteado.**

- ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?

**git reflog , para buscar el hash del commit **

**git reset --hard 13d21b7 , para volver al commit identificado e incorporar los cambios a la rama activa styled**

- El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

** No,  porque no se hizo el merge ya que no tiene sentido que styled absorba a master porque el commit en el que está la rama master es el commit ancestro, habria que activar la rama master y que esta absorba a la styled.**


- El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

** Sí, porque en ambas ramas hay modificaciones en las mismas líneas del mismo archivo git-nuestro.md.**

 - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué? 

** No, porque la rama styled ya incorpora en sus commits ancestros los cambios de master, por lo que es capáz de realizar un merge fast forward.**

- ¿Qué comando o comandos utilizaste en el paso 25?

**  git log --graph --oneline --decorate**

- El merge del paso 26, ¿Podría ser fast forward? ¿Por qué? 

** Sí, por la misma razon de la pregunta del paso 21.**

** git merge --no-ff title  **

- ¿Qué comando o comandos utilizaste en el paso 27?

** git reset HEAD~1**

- ¿Qué comando o comandos utilizaste en el paso 28? 

** git checkout -- git-nuestro.md**

- ¿Qué comando o comandos utilizaste en el paso 29? 

** git branch -D title**

- ¿Qué comando o comandos utilizaste en el paso 30? 

** git reflog , para buscar el hash del commit del merge**

**  git reset --hard 7189950 , para incorporar en la rama master el commit donde teniamos el merge que deshicimos antes.**

- ¿Qué comando o comandos usaste en el paso 32? 

** git reflog**

**  git checkout 2912ec9**

- ¿Qué comando o comandos usaste en el punto 33? 

** git reflog**

** git checkout 7189950 **

  