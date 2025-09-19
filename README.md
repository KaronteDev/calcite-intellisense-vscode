# Calcite IntelliSense (Custom HTML Data)

Esta extensión añade IntelliSense HTML (completado, hover y docs) para componentes Calcite a partir de un fichero JSON `customData`.

## Uso en local / Depuración

1. Instala deps:
   ```bash
   npm i
   ```
2. Verifica que el JSON existe en:
   ```
   custom-data/vscode.html-custom-data.json
   ```
3. Pulsa **F5** en VS Code → se abre una nueva ventana "Extension Development Host".
4. Abre un HTML y escribe etiquetas/atributos de Calcite para ver el autocompletado.

## Publicación
- Empaqueta:
  ```bash
  npx vsce package
  ```
- Publica:
  ```bash
  npx vsce publish
  ```

## Notas
- `contributes.html.customData` apunta al JSON incluido en la carpeta del paquete.
- Si cambias el JSON, recarga la ventana de desarrollo de la extensión.
