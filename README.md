# Introducción
En este repositorio se encuentra diferentes utilidades para la consola linux.

## Configuración colores shell
Visitar [https://github.com/Mayccoll/Gogh](https://github.com/Mayccoll/Gogh). El actual esquema instalado es *Tomorrow*

## tmux
En el directorio .tmux, se encuentra:
1. tmux.conf que se colocaría en ~/.tmux.conf
2. tmux/ que se colocaría en ~/.tmux/ . Estos plugins vienen del repo [https://github.com/tmux-plugins/tpm](https://github.com/tmux-plugins/tpm)

Recursos adicionales:
[http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/](http://www.hamvocke.com/blog/a-guide-to-customizing-your-tmux-conf/)

## ssh
Configuración para crear "shortcuts" con conexiones ssh. De esta forma, se puede usar directamente _ssh devhost_ por ejemplo, para conectarnos a la máquina que hayamos definido con nombre de host devhost en el fichero _.ssh/config_.

Bastaría copiar el fichero config al directorio ~/.ssh/