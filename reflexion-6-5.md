# Reflexión final – Parte 6

1. Para qué sirve git rebase -i y ventajas  
Sirve para reorganizar y limpiar el historial de commits. Permite cambiar mensajes, combinar commits, reordenarlos o eliminar los innecesarios. Ventajas: historial más limpio, commits claros y mejor seguimiento de cambios.

2. Ejemplos de uso  
- reword: cambiar el mensaje de un commit que dice “arreglo” a algo más descriptivo.  
- squash: unir varios commits pequeños de un mismo cambio en uno solo.  
- drop: eliminar un commit que ya no es necesario o que era un error.

3. Riesgos de usar mal git rebase -i  
Si se reescribe la historia de una rama compartida, puede causar conflictos y confusión para otros colaboradores, ya que sus commits pueden quedar desincronizados.
