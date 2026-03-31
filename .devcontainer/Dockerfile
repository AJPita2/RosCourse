FROM osrf/ros:humble-desktop

# Instalar herramientas adicionales
RUN apt-get update && apt-get install -y \
    python3-pip \
    python3-colcon-common-extensions \
    && rm -rf /var/lib/apt/lists/*

# Configurar el entorno
RUN echo "source /opt/ros/humble/setup.bash" >> /root/.bashrc