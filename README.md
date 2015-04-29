```multicompany_sequence ```
====
* Establece un filtro en las sequencias por compañia del usuario.

```multicompany_account_account ```
====
* Establece un group by por compañia en la vista de cuentas contables.

```multicompany_fiscalyear ```
====
* En estructuras multiempresa del tipo padre / hijo, si desde la empresa 
padre queremos seleccionar un ejercicio a nivel de informes, nos salen los 
ejercicios de la empresa padre y de cada una de las hijas. Si usamos son 
mismos code y name es imposible saber que ejercicio pertenece a que empresa.
Con este modulo, cambiamos la funcion name_get del objeto account_fiscalyear
para que nos muestre los ejercicios con el formato (codigo ejercicio - empresa)
