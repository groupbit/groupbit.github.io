# Groupbit

## Configuración del entorno

Para correr este sitio, es necesario instalar Ruby. La forma más sencilla de hacerlo es ejecutando lo siguiente:

```bash
sudo apt install ruby-full
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