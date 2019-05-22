# Groupbit

## Configuración del entorno

Para correr este sitio, es necesario instalar Ruby. La forma más sencilla de hacerlo es ejecutando lo siguiente:

```bash
gpg2 --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3 7D2BAF1CF37B13E2069D6956105BD0E739499BDB
curl -L https://get.rvm.io | bash
echo 'source ~/.rvm/scripts/rvm' >> ~/.bashrc 

# Abrir una nueva consola para ejecutar lo siguiente:
rvm autolibs disable
rvm install 2.6.3
rvm --default use 2.6.3
```

Luego, hay que instalar [Bundler](https://bundler.io/), el gestor de bibliotecas de Ruby:

```bash
gem install bundler
```

## Instalación y ejecución

Una vez configurado el entorno, hay que instalar las dependencias del proyecto. Para eso, ejecutamos lo siguiente dentro del directorio del proyecto:

```bash
bundle install
```

Por último, para correr el servidor ejecutaremos lo siguiente:

```bash
bundle exec jekyll s
```

El servidor se actualiza automáticamente con cada cambio que hagamos en cualquier archivo.