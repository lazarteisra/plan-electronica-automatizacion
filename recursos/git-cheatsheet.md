# Git — Referencia rápida

## El ciclo de cada día
- `git add .` → Añadir un archivo que puede texto o mensaje
- `git commit -m "mensaje"` → Subir el archivo creado en este caso seria un mensaje
- `git push` → Confirmar los cambios que estoy subiendo

## Para consultar
- `git status` → Sirve para ver el estado de un archivo indicando si a sido modificado o esta preparado para el siguiente comm
- `git log --oneline` → Para ver el historial de commits/cambios subidos
- `git diff HEAD~1` → Es para ver que cambio en un archivo antes de hacer un commit

## Para deshacer
- `git restore archivo` → Para restaurar un archivo antes del commit

## Errores comunes que ya resolví
- Password authentication not supported → usar token ghp_... dado en github
- mkidir not found → el comando correcto es mkdir
- nada para hacer commit → revisar Ctrl+S en VS Code
