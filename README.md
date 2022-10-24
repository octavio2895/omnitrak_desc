# Omnitrak
Paquete para visualización del omnitrak en RVIZ y la simulación en Gazebo.

# Pasos: 
1. Descargar el paquete de este repositorio y descomprimirlo como "omnitrak_description" en: /home/catkin_ws/src
2. Descargar las mallas (meshes) del siguiente Google Drive: https://drive.google.com/drive/folders/138GZCuYr_zvqPTwIL-Sw-f9tEYIyxQQI?usp=sharing
3. Descomprimir la carpeta de mallas y guardarla como "meshes" en el paquete "omnitrak_description"

![paquete](https://user-images.githubusercontent.com/90019998/197624462-787cd3b4-62fb-4045-ab21-736ad4fd9741.png)

4. En la terminal de ubuntu: 
>*cd catkin_ws
>*catkin_make

5. Para correr la simulación en rviz:
>*source devel/setup.bash
>*roslaunch omnitrak_description display.launch

![Screenshot from 2022-10-24 15-33-07](https://user-images.githubusercontent.com/90019998/197624243-f547040b-32f6-4a45-80b3-e477138ab75f.png)

6. Para correr la simulación en Gazebo:
source devel/setup.bash
roslaunch omnitrak_description gazebo.launch

![omnitrakgazebo](https://user-images.githubusercontent.com/90019998/197624234-7f31ff2f-2f6a-473e-9bc8-58b356c5c53a.png)


