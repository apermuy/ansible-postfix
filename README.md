# Ansible Postfix
Rol Ansible para configurar Postfix en servidores Debian

## Pasos para despliegue

   * Incluir en ficheros host la máquina sobre las que se desplegará el playbook.
   * Configurar variables en el directorio roles/postfix/vars/common.yml
   * Ejecutar playbook: ansible-playbook -i host deploy.yml -K