# AvancesProyectoImagenes


using Swin-t transformers to do a semantic segmentation in MinneApple
el notebook de la entrega final es el que termina con FINAL. 

Cuando ya esta descargado el dataset en el colab y esta inicializado el mmdetection los archivos de config_swin2.py y coco_instance_base.py van en la carpeta de '/content/mmdetection/configs/' y '/content/mmdetection/configs/base/datasets'.

Mientras que los archivos json con las anotaciones van en la carpeta de /content/detection/train/

Con estos archivos subidos se puede correr el modelo.

A la vez esta subido en el repositorio el archivo de la configuración final (config_swin_CON_ALTERACIONES.py), ya que el notebook realiza alteraciones a la configuracion provista.

igualmente no se puede saltar el paso de subir el coco_instance_base.py y los dataset con las annotaciones correspondientes en el lugar indicado.

Tambien este repositorio cuenta con un par de imagenes de ejemplo de la segmentación semantica y un json con los las metricas pedidas (llamado scalars.json)

Este github cuenta con la planificación

y este es el link del video de la presentacion https://youtu.be/BFQnu4bLAFQ
