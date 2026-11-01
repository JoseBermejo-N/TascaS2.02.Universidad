# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 2 correctas de 6 queries

## ❌ Query 1: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
 apellido1 | apellido2 | nombre
+Sánchez | Pérez | Salvador
+Saez | Vega | Juan
+Heller | Pagac | Pedro
+Koss | Bayer | José
+Strosin | Turcotte | Ismael
+Herzog | Tremblay | Ramón
+Herman | Pacocha | Daniel
+Lakin | Yundt | Inma
+Gutiérrez | López | Juan
 Domínguez | Guerrero | Antonio
+Hernández | Martínez | Irene
 Gea | Ruiz | Sonia
-Gutiérrez | López | Juan
-Heller | Pagac | Pedro
-Herman | Pacocha | Daniel
-Hernández | Martínez | Irene
-Herzog | Tremblay | Ramón
-Koss | Bayer | José
-Lakin | Yundt | Inma
-Saez | Vega | Juan
-Sánchez | Pérez | Salvador
-Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.53 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 2: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-nombre | apellido1 | apellido2
-Pedro | Heller | Pagac
-Ismael | Strosin | Turcotte
+apellido1 | apellido2 | nombre
+Heller | Pagac | Pedro
+Strosin | Turcotte | Ismael
```

⏱ Tiempo: 0.42 ms
🔍 No se usó ningún índice en esta consulta.

---

## ❌ Query 3: Incorrecto
```diff
--- 
+++ 
@@ -1,3 +1,3 @@
-id | nombre | apellido1 | apellido2 | fecha_nacimiento
-7.00 | Ismael | Strosin | Turcotte | 1999-05-24
-22.00 | Antonio | Domínguez | Guerrero | 1999-02-11
+id | nombre | apellido1 | apellido2
+7.00 | Ismael | Strosin | Turcotte
+22.00 | Antonio | Domínguez | Guerrero
```

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.39 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.42 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Error
- **Descripción**: 'NoneType' object is not iterable

