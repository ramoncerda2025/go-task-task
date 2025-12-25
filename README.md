# Task es un task runner / alternativa simple a Make escrito en Go. Usa un archivo YAML llamado Taskfile.yml para definir tareas con descripciones, dependencias, comandos, etc. Soporta variables, includes, plataformas cruzadas (incluyendo Android/Termux vía Go), y es ideal para automatizar scripts repetitivos sin las complicaciones de Makefiles.

# go-task/task:task: → nombre de la tarea

summary: → descripción (se muestra con task --list)

dependencies: → deps (tareas que se ejecutan antes)

commands: → cmds (los comandos a ejecutar
