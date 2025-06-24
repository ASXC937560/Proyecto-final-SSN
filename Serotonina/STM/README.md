Aquí hacemos la simulación STM en la carpeta run a partir de los pseudopotenciales de C,H,O y N, el stm.fdf y el structure.fdf. Con la geometría optimizada anteriormente (optimization.xyz) generamos a partir del jupyter notebook (STM_Final_Version) la molecula centrada y en versión .fdf para la simulación (structure.fdf).

Con el jupyter notebook anteriormente mencionado y los resultados de la simulación en la carpeta run obtenemos el Hamiltoniano, a partir de este vemos los autoestados (cuantos hay y su energía en eV), vemos el HOMO y el LUMO y la densidad de estados en un rango de energía de -10 a 10 eV.

Con el jupyter notebook vemos la densidad electrónica del LUMO y HOMO y de al aplicar 5V y -6V, esto se guarda en la carpeta results.

En analysis, hay las imagenes de la densidad electrónica LUMO y HOMO y de los estados accesibles al aplicar 5V y -6V.

Por último, y más importante en la carpeta STM images están las imagenes STM de los estados ocupados (corresponden al aplicar 5 V) y los estados vacios (corresponden al aplicar -6V) de la serotonina los cuales se podrían ver en un laboratorio real mediante microscopía STM.
