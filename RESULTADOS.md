# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 5 correctas de 7 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.35 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.20 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.19 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.16 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.21 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 6: Incorrecto
```diff
--- 
+++ 
@@ -1,13 +1,13 @@
-apellido1 | apellido2 | nombre | departamento
-Fahey | Considine | Antonio | Economía y Empresa
-Hamill | Kozey | Manolo | Informática
-Kohler | Schoen | Alejandro | Matemáticas
-Lemke | Rutherford | Cristina | Economía y Empresa
-Monahan | Murray | Micaela | Agronomía
-Ramirez | Gea | Zoe | Informática
-Ruecker | Upton | Guillermo | Educación
-Schmidt | Fisher | David | Matemáticas
-Schowalter | Muller | Francesca | Química y Física
-Spencer | Lakin | Esther | Educación
-Stiedemann | Morissette | Alfredo | Química y Física
-Streich | Hirthe | Carmen | Educación
+nombre | apellido1 | apellido2 | nombre_departamento
+Zoe | Ramirez | Gea | Informática
+Manolo | Hamill | Kozey | Informática
+David | Schmidt | Fisher | Matemáticas
+Alejandro | Kohler | Schoen | Matemáticas
+Cristina | Lemke | Rutherford | Economía y Empresa
+Antonio | Fahey | Considine | Economía y Empresa
+Esther | Spencer | Lakin | Educación
+Carmen | Streich | Hirthe | Educación
+Guillermo | Ruecker | Upton | Educación
+Micaela | Monahan | Murray | Agronomía
+Alfredo | Stiedemann | Morissette | Química y Física
+Francesca | Schowalter | Muller | Química y Física
```

⏱ Tiempo: 0.25 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ❌ Query 7: Error
- **Descripción**: 'NoneType' object is not iterable

