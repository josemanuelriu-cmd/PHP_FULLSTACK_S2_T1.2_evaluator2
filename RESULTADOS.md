# 📊 Análisis de Consultas SQL


## 📈 Resumen
✅ 23 correctas de 26 queries

## ✅ Query 1: Correcto

⏱ Tiempo: 0.37 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 2: Correcto

⏱ Tiempo: 0.31 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 3: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 4: Correcto

⏱ Tiempo: 0.33 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 5: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 6: Correcto

⏱ Tiempo: 0.38 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 7: Correcto

⏱ Tiempo: 0.53 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_asignatura,id_curso_escolar, PRIMARY,nif, PRIMARY

---

## ✅ Query 8: Correcto

⏱ Tiempo: 0.40 ms
✅ Se usó índice(s) en la consulta: id_profesor,id_grado, PRIMARY,id_departamento, PRIMARY

---

## ✅ Query 9: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: PRIMARY,id_curso_escolar, PRIMARY

---

## ✅ Query 10: Correcto

⏱ Tiempo: 0.43 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 11: Correcto

⏱ Tiempo: 0.37 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 12: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 13: Correcto

⏱ Tiempo: 0.36 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY

---

## ✅ Query 14: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: PRIMARY

---

## ✅ Query 15: Correcto

⏱ Tiempo: 0.32 ms
✅ Se usó índice(s) en la consulta: id_profesor, id_departamento

---

## ✅ Query 16: Correcto

⏱ Tiempo: 0.30 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 17: Correcto

⏱ Tiempo: 0.32 ms
🔍 No se usó ningún índice en esta consulta.

---

## ✅ Query 18: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento, PRIMARY

---

## ✅ Query 19: Correcto

⏱ Tiempo: 0.33 ms
✅ Se usó índice(s) en la consulta: id_departamento

---

## ✅ Query 20: Correcto

⏱ Tiempo: 0.35 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ✅ Query 21: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_grado

---

## ❌ Query 22: Error
- **Descripción**: 1054 (42S22): Unknown column 'g.tipo' in 'group statement'


## ❌ Query 23: Error
- **Descripción**: 1054 (42S22): Unknown column 'am.nombre' in 'field list'


## ✅ Query 24: Correcto

⏱ Tiempo: 0.39 ms
✅ Se usó índice(s) en la consulta: id_profesor, PRIMARY,nif, PRIMARY

---

## ✅ Query 25: Correcto

⏱ Tiempo: 0.34 ms
🔍 No se usó ningún índice en esta consulta.

🚨 **Problemas detectados:**
⚠️ Evitar `SELECT *`. Usar solo las columnas necesarias.

---

## ❌ Query 26: Error
- **Descripción**: 'NoneType' object is not iterable

