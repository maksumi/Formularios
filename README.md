## Tipos de Campos de Entrada en Formularios HTML:
### Información sobre tipo y uso de inputs para formularios (unos vistos en clase y otros investigados)
`1. Texto:
   <!-- Campo para ingresar texto -->
   <input type="text" name="nombre" placeholder="Nombre" required>

2. Contraseña:
   <!-- Campo para ingresar contraseñas -->
   <input type="password" name="contrasena" placeholder="Contraseña" required>

3. Número:
   <!-- Campo para ingresar números -->
   <input type="number" name="edad" min="0" max="150" step="1" required>

4. Correo Electrónico:
   <!-- Campo para ingresar correos electrónicos -->
   <input type="email" name="correo" placeholder="correo@example.com" required>

5. Teléfono:
   <!-- Campo para ingresar números de teléfono -->
   <input type="tel" name="telefono" placeholder="123-456-7890" required>

6. Fecha:
   <!-- Campo para seleccionar fechas -->
   <input type="date" name="fecha" required>

7. Hora:
   <!-- Campo para seleccionar horas -->
   <input type="time" name="hora" required>

8. URL:
   <!-- Campo para ingresar URLs -->
   <input type="url" name="sitioWeb" placeholder="http://www.ejemplo.com" required>

9. Selección (Dropdown):
   <!-- Menú desplegable de opciones -->
   <select name="pais" required>
     <option value="usa">Estados Unidos</option>
     <option value="canada">Canadá</option>
     <option value="mexico">México</option>
   </select>

10. Casillas de Verificación:
    <!-- Casilla de verificación -->
    <input type="checkbox" name="suscripcion" value="si"> Suscribirse

11. Botones de Radio:
    <!-- Botones de selección exclusiva -->
    <input type="radio" name="genero" value="masculino" checked> Masculino
    <input type="radio" name="genero" value="femenino"> Femenino

12. Área de Texto:
    <!-- Área de texto de múltiples líneas -->
    <textarea name="comentarios" rows="4" cols="50" placeholder="Comentarios"></textarea>

13. Enviar:
    <!-- Botón para enviar el formulario -->
    <input type="submit" value="Enviar">

14. Restablecer:
    <!-- Botón para restablecer el formulario -->
    <input type="reset" value="Restablecer">`
