Con la geometría optimizada anteriormente (optimization.xyz) generamos a partir del jupyter notebook (STM_Final_Version) la molecula centrada y en versión .fdf para la simulación (structure.fdf).

Hacemos la simulación STM en la carpeta run a partir de los pseudopotenciales de C,H y N, el stm.fdf y el structure.fdf.

Con el jupyter notebook anteriormente mencionado y los resultados de la simulación en la carpeta run obtenemos el Hamiltoniano, a partir de este vemos los autoestados (cuantos hay y su energía en eV), vemos el HOMO y el LUMO y la densidad de estados en un rango de energía de -10 a 10 eV.

Con el jupyter notebook vemos la densidad electrónica del HOMO y LUMO y de al aplicar 6V y -5V, esto se guarda en la carpeta results.

En analysis, hay las imagenes de la densidad electrónica HOMO y LUMO y de los estados accesibles al aplicar 6V y -5V.

Por último, y más importante en la carpeta STM images están las imagenes STM de los estados ocupados (corresponden al aplicar 6V) y los estados vacios (corresponden al aplicar -5V) del DMT los cuales se podrían ver en un laboratorio real mediante microscopía STM.
