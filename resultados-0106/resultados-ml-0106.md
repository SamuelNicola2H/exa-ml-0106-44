# Reporte de Análisis de Datos - Pandas

`Samuel Nicola Machine Learning pandas, NC 0106`

## 1. DataFrame Convertido
```text
         Mina  Trabajadores  Produccion_ton
0  La Caridad          3500          150000
1  Buenavista          4200          180000
2  Peñasquito          2800          120000
3   Fresnillo          1800           80000
4       Canoa           900           45000
5   El Sauzal           600           30000
```

## 2.1 Primeras Filas (head)
```text
         Mina  Trabajadores  Produccion_ton
0  La Caridad          3500          150000
1  Buenavista          4200          180000
```

## 2.2 Últimas Filas (tail)
```text
        Mina  Trabajadores  Produccion_ton
4      Canoa           900           45000
5  El Sauzal           600           30000
```

## 2.3 Dimensiones (Filas, Columnas)
```text
(6, 3)
```

## 2.4 Tipos de Datos por Columna
```text
Mina                str
Trabajadores      int64
Produccion_ton    int64
dtype: object
```

## 2.5 Información General (info)
```text
<class 'pandas.DataFrame'>
RangeIndex: 6 entries, 0 to 5
Data columns (total 3 columns):
 #   Column          Non-Null Count  Dtype
---  ------          --------------  -----
 0   Mina            6 non-null      str  
 1   Trabajadores    6 non-null      int64
 2   Produccion_ton  6 non-null      int64
dtypes: int64(2), str(1)
memory usage: 276.0 bytes

```

## 3. Estadísticas Generales de Produccion_ton
```text
count         6.000000
mean     100833.333333
std       59364.692088
min       30000.000000
25%       53750.000000
50%      100000.000000
75%      142500.000000
max      180000.000000
Name: Produccion_ton, dtype: float64
```

## 4. Ordenar Ascendente por Produccion_ton
```text
         Mina  Trabajadores  Produccion_ton
5   El Sauzal           600           30000
4       Canoa           900           45000
3   Fresnillo          1800           80000
2  Peñasquito          2800          120000
0  La Caridad          3500          150000
1  Buenavista          4200          180000
```

## 5. Ordenar Descendente por Trabajadores
```text
         Mina  Trabajadores  Produccion_ton
1  Buenavista          4200          180000
0  La Caridad          3500          150000
2  Peñasquito          2800          120000
3   Fresnillo          1800           80000
4       Canoa           900           45000
5   El Sauzal           600           30000
```

`Samuel Nicola Machine Learning pandas, NC 0106`