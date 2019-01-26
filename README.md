# Evaluación Colaborativa
Este es un algoritmo de evaluación colaborativa para la revición de documentos implementado en javascript.
### Variables:
z= calificación final\
w= Calificaciones de la evaluación entre pares (estudiantes)\
x= Calificación asignada por el docente\
m= base de calificación; por ejemplo la calificaciòn es sobe 10\
n= Número de revisiones totales, incluye estudiantes y docente\
y=valor que se obtiene de la comparación de la nota por evaluar que coloca un estudiante con la nota que asigna el docente\
p= número de evaluaciones realizada por el estudiante\
### Expresión Matemática:
\
![equation](http://latex.codecogs.com/gif.latex?z(w,x,y)=(\frac{(\frac{\sum_{w=0}^{w=n-1}\frac{w}{m}}{n}*m)+x}{2}*0.8)+((\sum_{y=0}^{y=p-1}y)*0.2))
### Equivalencia:
\
![equation](http://latex.codecogs.com/gif.latex?%20\begin{cases}%20y=m%20&\hbox{cuando%20}%20(x-(0.05m))%3C=%20w%20%3C=%20(x+(0.05m))%20&%20y=m0.9%20&\hbox{cuando%20}%20(x-(0.15m))%3C=%20w%20%3C=%20(x+(0.15m))%20&%20y=m0.6%20&\hbox{cuando%20}%20(x-(0.25m))%3C=%20w%20%3C=%20(x+(0.25m))%20&%20y=m0.5%20&\hbox{cuando%20}%20(x-(0.35m))%3C=%20w%20%3C=%20(x+(0.35m))%20&%20y=m0.4%20&\hbox{cuando%20}%20(x-(0.45m))%3C=%20w%20%3C=%20(x+(0.45m))%20&%20y=m0.2%20&\hbox{cuando%20}%20(x-(0.46m))%3C=%20w%20%3C=%20(x+(0.46*m))%20&\end{cases})
