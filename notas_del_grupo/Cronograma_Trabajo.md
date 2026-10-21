# Cronograma del Trabajo


| Partes | Tareas | Fechas | Estado |
|--------|--------|--------|--------|
| Parte 1 | > Formación del grupo.<br> > Elección del dataset.<br> > Elección de la pregunta.<br> > Creación del repo. | 16-18 de octubre | ✅
| Parte 2 | > Análisis en Python.<br> > Creación del colab. | 18-25 de octubre | 🔜 |
| Parte 3 | > Creación del informe | 26 oct - 1 nov | 🔜 |
| Parte 4 | > Creación de diapos.<br> > Complemento (opcional).<br> > Revisión final de todo. | 2-5 noviembre | 🔜 |
| Parte 5 | > Entrega y defensa del trabajo. | 6 noviembre | 🔜 |

#
#
## Tareas detalladas del notebook:<br>
### Parte 1:<br>
1. ~Carga del dataset en un df de pandas.~<br>
2. ~Mostrar primeras filas (.head()) y últimas filas (.tail()).~<br>
3. ~Verificamos dimensiones del df (.shape).~<br>
4. Inspeccionamos con .info antes de ponernos mas descriptivos.<br>
5. ~Verificamos el tipo de datos en las columnas (.dtypes).~<br>
6. ~Verificar cobertura temporal (fecha inicio-fin de los datos).~<br>
7. Contabilizar valores nulos (.isnull().sum()).<br>
8. Contabilizar duplicados (df.duplicated().sum()).<br>
9. ~Mostrar estadística descriptiva (.describe()).~<br>
### Parte 2:<br>
1. Definir de forma escrita la pregunta que guía el resto del analisis.<br>
2. Definir motivación del análisis.<br>
3. ¿Qué respuesta encontramos? (a responder al finalizar el análisis).<br>
## A tener en cuenta:<br>
1. Al menos **DOS** transformaciones justificadas:<br>
     a) Filtrar filas.<br>
     b) Convertir tipos.<br>
     c) Crear columnas derivadas.<br>
     d) Manejar nulos.<br>
2. Al menos calcular **DOS** estadísticos de resumen agrupados usando .groupby().<br>
3. Mínimo **TRES** gráficos de distintos tipos:<br>
     a) Evolución temporal o distribución:<br>
          I. Serie principal.<br>
          II. Histograma.<br>
          III. Boxplot.<br>
     b) Comparación entre categorías:<br>
           I. Barras simples o apiladas (ejes etiquetados y unidades).<br>
     c) Relación entre dos variables:<br>
           I. Diagrama de dispersión o líneas superpuestas.<br>
