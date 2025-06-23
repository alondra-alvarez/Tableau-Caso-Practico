# Tableau-Caso-Practico
## CONTEXTO
En este repositorio se analiza por medio de Tableau los datos personales de empleados de la compañía SRL con la finalidad de que el equipo de recursos humanos tomen la información para identificar puntos clave, y con base en ellos, optimizar la gestión del talento y  fomentar un entorno laboral más inclusivo y diverso.  
**Para ver el dashboard en tableau hacer [clic aqui](https://public.tableau.com/views/Tableau_Caso_Practico/HRAnalytics3?:language=es-ES&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)**
## OBJETIVO
Los analistas de Recursos Humanos necesitan un dashboard interactivo y dinámico que les permita identificar puntos clave, y con base en ellos, optimizar la gestión del talento y fomentar un entorno laboral más inclusivo y diverso.
## PASOS GENERALES
1. Importa la base de datos HRDataset.csv en Tableau. 
2. Desarrolla un dashboard que incluya al menos tres gráficos de los vistos en clase, respondiendo a algunas de las ideas de análisis descritas anteriormente.
3. Establecer los KPI principales a ser medidos y utilizando la función "campo calculado" de tableau generalos y agregarlos como texto
   - Empleados contratados (hires count)   
   - Numero de bajas (Attrition count)
   - Porcentage de bajas (Attrition rate)
   - Emmpleados activos (Active employees)
   - Indice de permanencia (Avg. retention (months)
4. Para dar mas detalle a los KPIs se realizaron algunos graficos
   - **Comparativa de Contratacions vs Bajas (Hires vs terminations)**
    ![hires vs terminations](https://github.com/user-attachments/assets/0e3b3a8e-0060-4bed-bb68-e65354be5c6c)

     
   - **Comparativa de satisfaccion vs Desempeño (Satisfaction vs performance)**
      ![satisfaction vs performance](https://github.com/user-attachments/assets/5623c0a6-fb9e-42a9-bf5b-9c34de15f914)

     
   - **Bajas por genero (Atrition by gender)**
    ![Attrition by gender](https://github.com/user-attachments/assets/82eab61d-6e89-4432-bd30-3afa3d4d61e5)

   - **Bajas por departamento (Attrition by department)**
     ![Attrition by department](https://github.com/user-attachments/assets/253959e2-a0e6-44a3-88da-e9e2d2b56a0a)


5. Generar dos filtros uno por fecha y otro por departamento para una vista segmentada
## CONCLUSIONES
-Se observa un attrition rate del 33% a lo largo de los 12 años analizados (2006-2018) con un promedio de retencion de 9 meses  
-Se observan 3 picos muy marcados de contrataciones a lo largo de los 12 años en (febrero,mayo y septiembre)  
-De observa una mayor cantidad de bajas en mujeres que en hombres (60-44) respectivamente  
-La mayoria de los empleados se clasifican en desempeño satisfactorio (fully meets) expectantions y con un desempeño (performance) de 3 a 5  
-El departamento con mayores bajas es el de produccion  



