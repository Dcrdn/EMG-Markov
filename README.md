Requisitos
jupyter lab instalado
https://jupyter.org/install

Clonar repo y en terminal correr
jupyter lab

Abre una terminal en jupyter lab  y corre:
conda env create --file signalsenv.yml

Esto creará el ambiente para correr nuestro signals

Ahora
conda install -c anaconda ipykernel
python -m ipykernel install --user --name=signals

Abre el jupyter notebook y selecciona el kernel como signals

Ahora puedes correr todo el proyecto

Si este error aparece:
failed to find libmagic.

Correr:
pip uninstall python-magic
pip install python-magic-bin==0.4.14