# Synthetic Student Dropout Dataset
# Estudiantes: Kevin Arrieta, Juan Niño, Ricardo Henriquez, Anderson ortega
Este dataset simula información histórica de estudiantes para predecir la deserción universitaria durante el primer año académico.

## Variables incluidas

- **Age**: Edad del estudiante (valores típicos entre 17 y 30, con algunos outliers entre -3 y 100).
- **Gender**: Género del estudiante (Male, Female, Other).
- **Place**: Lugar de origen (Urban, Rural, Suburban).
- **HS_Average**: Promedio de notas de secundaria (normalmente entre 1.0 y 5.0, con outliers negativos o muy altos).
- **Admission_Score**: Puntaje de examen de admisión (0 a 100, con distribución normal alrededor de 60).
- **Semester1_Grades**: Promedio de notas en el primer semestre (1.0 a 5.0, con outliers).
- **Socioeconomic**: Nivel socioeconómico (Low, Middle, High).
- **Scholarship**: Si el estudiante tiene beca (1 = Sí, 0 = No).
- **Loan**: Si el estudiante tiene préstamo educativo (1 = Sí, 0 = No).
- **Financial_Aid**: Si recibe otro tipo de ayuda financiera (1 = Sí, 0 = No).
- **Dropout**: Variable objetivo, indica si el estudiante abandonó (1 = Sí, 0 = No).

## Características adicionales

- **Cantidad de registros**: 500.
- **Valores nulos**: Se introdujeron de manera aleatoria en un 3% de los registros en todas las columnas.
- **Outliers**: Se añadieron en variables numéricas (edades irreales como -3 o 100; notas con valores negativos o mayores a 10).
- **Variables categóricas**: Gender, Place, Socioeconomic.

Este dataset fue creado únicamente con fines académicos y de práctica en Machine Learning.
