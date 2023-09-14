# PipelineDemo
Demo de CI/CD usando Jenkins

#PreRequisitos

* Crea un repositorio en GitHub: https://docs.github.com/es/get-started/quickstart/create-a-repo
* Añade tu proyecto de UiPath a tu repositorio de GitHub: https://docs.uipath.com/studio/docs/managing-projects-git
* Descarga e instala Jenkins en tu máquina desde aquí: https://www.jenkins.io/download/
* Como prerequisito, antes de instalar Jenkins, necesitas instalar Java: https://www.jenkins.io/doc/administration/requirements/java/
* UiPath Cloud Orchestrator
* Instala la integración de UiPath en tu agente de Jenkins: https://plugins.jenkins.io/uipath-automation-package/

Si deseas que el pipeline se ejecute automáticamente con un push en tu repositorio, tendrás que crear un webhook.
Si no tienes una IP pública donde hayas alojado tu agente, puedes usar ngrok. De esta manera podrás crear un pipeline totalmente automatizado.
