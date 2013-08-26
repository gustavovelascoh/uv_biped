add_custom_command(
	OUTPUT uv_biped.urdf
	COMMAND rosrun xacro xacro.py ${CMAKE_SOURCE_DIR}/src/${ROS_PACKAGE_NAME}/robots/uv_biped.urdf.xacro > ${CMAKE_SOURCE_DIR}/src/${ROS_PACKAGE_NAME}/model/uv_biped.urdf 
	DEPENDS uv_biped.urdf.xacro
	)
	
	export ROS_PACKAGE_PATH=${SANDIA_HAND_ROS_PACKAGE_PATH}:${CMAKE_SOURCE_DIR}/ros:$ENV{ROS_PACKAGE_PATH} &&