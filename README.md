# helm_menu
![image](https://github.com/user-attachments/assets/946461ab-9059-4b2f-bcb8-4a1c438ed2e1)


ChatGPT :
¡Gracias por compartir el script! Parece ser un script Bash bastante completo para gestionar Helm charts en un clúster de Kubernetes. Aquí tienes un resumen de lo que hace cada sección:
Configuración de Colores: Define varios colores para la salida en terminal, mejorando la legibilidad de los mensajes.
check_tools: Verifica que las herramientas necesarias (git, helm, kubectl, curl) estén instaladas. Si falta alguna, el script se detiene con un mensaje de error.
list_namespaces: Muestra todos los namespaces disponibles en el clúster de Kubernetes.
validate_namespace: Verifica si el namespace proporcionado por el usuario existe en el clúster.

Opciones de Menú:

clone_repos: Clona varios repositorios de Helm desde GitHub a un directorio local.
deploy_chart: Despliega un chart desde un repositorio remoto de Helm. Permite definir afinidad de nodos y el número de réplicas.
install_and_validate: Instala un chart de Helm con la opción de validar información sensible usando un plugin, si se elige así.
list_and_check: Permite listar recursos en el namespace seleccionado (pods, secretos, charts instalados, etc.).
cleanup_and_remove: Elimina recursos como charts, repositorios de Helm y secretos en el namespace seleccionado.
manage_plugins: Administra plugins de Helm (listar, ejecutar, mostrar ayuda).
add_repo: Añade un nuevo repositorio de Helm.
main_menu: Presenta un menú principal para que el usuario seleccione la acción deseada. Basado en la opción elegida, llama a la función correspondiente.

Inicio del Script:

Verifica que las herramientas necesarias estén instaladas.
Lista los namespaces disponibles y solicita al usuario que elija uno.
Inicia el menú principal para la interacción del usuario.
