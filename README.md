# helm_menu

main_menu
├── 1. Instalar plugins [ ResourceRequests | SecretCreator | ValidaPassword ]
├── 2. Instalar [ repo | chart | affinityNode | replicas | con secret ]
├── 3. Instalar [ repo | chart | affinityNode | replicas | plugin valida info sensible del values ]
├── 4. Listar y comprobar
│   ├── A. Listar pods de un namespace
│   ├── B. Listar pods en formato YAML en un namespace
│   ├── C. Listar secretos de un namespace
│   ├── D. Listar charts instalados de un namespace
│   ├── E. Listar repositorios de Helm
│   └── 0. Volver al menú principal
├── 5. Limpieza / Eliminar
│   ├── A. Desinstalar un chart en namespace
│   ├── B. Eliminar un repositorio de Helm
│   └── C. Eliminar un secret
│   └── 0. Volver al menú principal
├── 6. Utilización de Plugins
│   ├── A. Listar plugins disponibles
│   ├── B. Ejecutar un plugin sobre un local chart
│   └── C. Mostrar ayuda de un plugin
│   └── 0. Volver al menú principal
├── 7. Tan solo agrega un nuevo repo, por si queres usar los plugins
└── 0. Salir
