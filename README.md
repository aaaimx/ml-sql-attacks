
# Código DFSQLIA

**DFSQLIA** es un deep forest compuesto de 4 niveles con árbol de decisión y random forest diseñado para identificar ataques de inyección antes de ingresar la información a las bases de datos.

Se enfoca en poder predecir ataques a nivel usuario y bloquear las entradas de datos que posiblemente puedan ser maliciosas, el usuario puede ajustar las caracteristicas según su necesidad, tambien mediante explainerdashboard los usuarios pueden observar el peso de las características en cada modelo, se puede guardar los modelos individuales y se puede cargar los modelos sin necesidad de reentrenar

Para poder entrenar un modelo, se necesita un dataset con datos clasificados como ataques de inyección o no ataques de inyección.

**Versión de Python:** 3.10.4

Las librerías y versiones están en "requirements.txt" y se pueden instalar con el siguiente comando:

```bash
pip install -r requirements.txt
