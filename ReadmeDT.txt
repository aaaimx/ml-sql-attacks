# Código DTSQLIA

**DTSQLIA** es un árbol de decisión diseñado para identificar ataques de inyección antes de ingresar la información a las bases de datos.

Se enfoca en predecir ataques a nivel de usuario y bloquear las entradas de datos que posiblemente puedan ser maliciosas. Los usuarios pueden ajustar las características según sus necesidades. Además, mediante `explainerdashboard`, los usuarios pueden observar el peso de las características en el modelo. También se puede guardar el modelo y cargarlo sin necesidad de reentrenar.

Para poder entrenar un modelo, se necesita un dataset con datos clasificados como ataques de inyección o no ataques de inyección.

**Versión de Python:** 3.10.4

Las librerías y versiones están en "requirements.txt" y se pueden instalar con el siguiente comando:

```bash
pip install -r requirements.txt
