# Usa la imagen base de Python
FROM python:3.9

# Establece el directorio de trabajo dentro del contenedor
WORKDIR /app

# Copia los archivos de la aplicación al contenedor
COPY . .

# Instala las dependencias
RUN pip install Flask
RUN pip install SQLAlchemy==1.4.23

# Expone el puerto 5000 (el puerto en el que se ejecuta Flask)
EXPOSE 5000

# Comando para ejecutar la aplicación
CMD ["python", "app.py"]
