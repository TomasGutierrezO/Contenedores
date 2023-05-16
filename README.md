# Contenedores

Instrucciones básicas:

1. Para la utilización de este proyecto, se debe clonar el repositorio:
  git clone https://github.com/TomasGutierrezO/Contenedores.git
  
2. Luego se debe acceder a la carpeta "Contenedores".

3. Se debe modificar el archivo "web.py" ubicado en la carpeta "web", la ruta completa es "/Contenedores/web/web.py".
   En este archivo se modifica la siguiente línea (línea 66):
    return redirect('http://localhost:5600/?password=270204') ---> En lugar de "localhost", se escribe la dirección ip de la máquina.
    
4. Se guarda el archivo y se vuelve a la carpeta "Contenedores"

5. Se inicializa:
    sudo docker-compose up
    
    
Nota: para ingresar a la página, se entra por el puerto 80 (ip_de_la_máquina:80)
