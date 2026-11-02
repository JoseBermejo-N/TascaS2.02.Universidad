# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 18 correctas de 22 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.50 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.40 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.38 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.49 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.78 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.48 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY, PRIMARY,id_departamento

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.55 ms
✅ Se usó índice(s) en la consulta: PRIMARY, PRIMARY,id_asignatura,id_curso_escolar

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.50 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ❌ Query 15: Error
- **Descripción**: 1054 (42S22): Unknown column 'd.nombre' in 'field list'


## ✅ Query 16: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ❌ Query 20: Incorrecto
```diff
--- 
+++ 
@@ -1,4 +1,4 @@
-grau | total
+grado | total
 Grado en Ingeniería Informática (Plan 2015) | 51.00
 Grado en Biotecnología (Plan 2015) | 32.00
 Grado en Ingeniería Agrícola (Plan 2015) | 0.00
```

⏱ Tiempo: 0.42 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 21: Incorrecto
```diff
--- 
+++ 
@@ -1,2 +1,2 @@
-grau | total
+grado | total
 Grado en Ingeniería Informática (Plan 2015) | 51.00
```

⏱ Tiempo: 0.41 ms
✅ Se usó índice(s) en la consulta: id_grado, PRIMARY

---

## ❌ Query 22: Error
- **Descripción**: 'NoneType' object is not iterable

