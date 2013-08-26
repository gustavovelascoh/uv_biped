uv_biped
========

ROS package for static and dynamic control for a simplified Atlas robot model. Based on DRCsim project.

Instrucciones:
==============

1. Crear el espacio de trabajo:

  $ mkdir -p my_workspace/src
  
  $ cd my_workspace/src
  
  $ catkin_init_workspace
  
2. Clonar el repositorio:

  $ git clone https://github.com/gustavovelascoh/uv_biped.git
  
3. Añadir el directorio del espacio de trabajo a la variable $ROS_PACKAGE_PATH:

  $ export ROS_PACKAGE_PATH=`pwd`:$ROS_PACKAGE_PATH
  
4. Lanzar el archivo uv_biped.launch

  $ roslaunch uv_biped uv_biped.launch
