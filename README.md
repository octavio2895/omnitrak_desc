# Omnitrak
Paquete para visualización del Omnitrak en RViz y la simulación en Gazebo

![imagen](https://user-images.githubusercontent.com/90019998/197627431-4c818193-2cdf-47a8-a8ab-47962bb637af.png)

# Pasos: 
1. Descargar el paquete de este repositorio y descomprimirlo como **omnitrak_description** en: 
```
/home/catkin_ws/src
```

3. Descargar las mallas (meshes) del siguiente [Google Drive](https://drive.google.com/drive/folders/138GZCuYr_zvqPTwIL-Sw-f9tEYIyxQQI?usp=sharing)

4. Descomprimir la carpeta de mallas y guardarla como **meshes** en el paquete:
```
omnitrak_description
```

![paquete](https://user-images.githubusercontent.com/90019998/197624462-787cd3b4-62fb-4045-ab21-736ad4fd9741.png)

4. En la terminal de Ubuntu: 
```
cd catkin_ws
catkin_make
```

5. Para correr la simulación en RViz:
```
source devel/setup.bash
roslaunch omnitrak_description display.launch
```

![rviz1](https://user-images.githubusercontent.com/90019998/198401639-d3a7c047-57eb-498a-b92c-c5715fcc12d6.png)

Para poder mover las articulaciones por medio del slider es necesario tener instalado **joint_state_publisher**

6. Para correr la simulación en Gazebo:
```
source devel/setup.bash
roslaunch omnitrak_description gazebo.launch
```

![omnitrak1](https://user-images.githubusercontent.com/90019998/198398273-077b85a6-5d6d-4209-86bd-3a118901b732.png)


