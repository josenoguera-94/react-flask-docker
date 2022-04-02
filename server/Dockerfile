# Para escoger una plataforma
FROM python:3

# Para dirigirse a un espacio de trabajo (linux) si no existe la carpeta la crea
WORKDIR /app

# ENTORNO DE TRBAJAO O  VARIABLE DE ENTORNO
ENV FLASK_APP=app.py
ENV FLASK_ENV=development

# COPIA "requirements.txt a la carpeta raiz, en este caso /app"
# COPY ./requirements.txt .

# Copia todo de la carpeta del proyecto a la carpeta raiz en este caso /app dado que se redirecciono
COPY . .

# Ejecutar un comandos del lenguaje
RUN pip install -r requirements.txt

# Ejecutar comandos en consola  ["executable", "parameter"]
CMD [ "python", "app.py" ]



