# ProyectoFinalClienteServidor
final proyect of client/server subject

execute this proyect with the next steps
--------------------------------------------------
1. in console one: python bodega.py
2. in console two: python inventario.py
3. in console three: python bodega.py

to execute again the step 1 or 2, you must kill the processes like the next steps:
--------------------------------------------------
1. -> lsof -i :6060
2. -> kill -9 pid
3. -> lsof -i :5050
4. -> kill -9 pid
