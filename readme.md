# Robotica Trabajo Final - Vizdoom
## Instrucciones para instalar (ubuntu)
Instalación de dependencias necesarias para compilar de la libreria de python
```
sudo apt install cmake libboost-all-dev libsdl2-dev libfreetype6-dev libgl1-mesa-dev libglu1-mesa-dev libpng-dev libjpeg-dev libbz2-dev libfluidsynth-dev libgme-dev libopenal-dev zlib1g-dev timidity tar nasm
```
Instalación de la libreria usando un ambiente virtual
```
python3 -m venv venv
source venv/bin/activate
pip install vizdoom
pip install wheel
pip install torch
pip install scikit-image
```

## Ejecución
Para ejecutar el ejemplo basico
```
python basic.py
python learning_2d.py
python learning_3d.py
```
