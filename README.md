# Sistema de Turno Unifila para Hospital

## Descripción
Este proyecto es una aplicación web simple diseñada para hospitales que implementa un sistema de fila única (Unifila). La aplicación muestra el último turno atendido y permite a los pacientes buscar su propio turno ingresando su nombre.

## Características
- Visualización del último turno atendido
- Búsqueda de turno por nombre
- Actualización automática del último turno atendido
- Interfaz de usuario intuitiva y responsiva
- Diseño adaptable a la identidad visual de cualquier hospital

## Tecnologías Utilizadas
- HTML5
- CSS3
- JavaScript (ES6+)
- Google Sheets (como base de datos simple)

## Instalación
1. Clone este repositorio:
   ```
   git clone https://github.com/tu-usuario/turno-unifila.git
   ```
2. Navegue al directorio del proyecto:
   ```
   cd turno-unifila
   ```
3. Abra el archivo `index.html` en su navegador web preferido.

## Uso
1. Al cargar la página, verá el último turno atendido.
2. Para buscar su turno, ingrese su nombre en el campo de texto y haga clic en "Buscar turno".
3. La aplicación mostrará su número de turno y cuántas personas faltan antes de su turno.

## Configuración
Para utilizar su propia hoja de cálculo de Google como fuente de datos:

1. Cree una hoja de cálculo de Google con las columnas: Turno, Nombre, Atendido
2. Publique la hoja de cálculo en la web (Archivo > Publicar en la web)
3. Copie el enlace de publicación
4. Reemplace la URL en la variable `urlCSV` en el archivo `index.html`

## Personalización
Para adaptar el sistema a su hospital:

1. Modifique los colores en el archivo CSS para que coincidan con la identidad visual de su hospital.
2. Actualice el logotipo y el nombre del hospital en el archivo HTML.
3. Ajuste los mensajes y textos según sea necesario para reflejar la terminología específica de su institución.

## Contribuir
Las contribuciones son bienvenidas. Por favor, abra un issue para discutir cambios mayores antes de crear un pull request.
