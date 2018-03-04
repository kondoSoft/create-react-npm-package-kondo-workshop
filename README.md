# Como crear un paquete npm usando react

## Introduccion

Si eres un apasionado de JS o de react, incluso si solo eres un entusiasta del desarrollo y has usado Node, conoces npm, el manejador de paquetes para Node.

Una de las ventajas que npm representa es que podemos instalar paquetes para node con tan solo un comando como...

```shell
npm install react
```

## Pero que son los paquetes npm?

La manera mas rapida de explicar es que son programas de JS y Node "enpaquetados" bajo una estructura estandar, estos paquetes pueden contener otros paquetes y pueden ser recursivos. es decir:

- Un programa de Node puede contener otro
- Las subrutinas o sub programas de Node pueden contener otros de manera recursiva

## Manos a la obra!

Comencemos desde el principio y de manera rapida instalemos Node.

## Que es Node?

Node es Javascript en tu computadora, JS fue hecho para trabajar y vivir en tu explorador, en la actualidad y gracias a Node podemos utilizarlo en nuestra computadora, gracias a esto JS a crecido de manera rapida y constante, antes solo lo encontrabas en el navegador, ahora lo encontraras hasta en tu refrigerador.

### Instalemos Node

Recomendamos el uso del `nvm` tal y como se muestra en este video. Si no lo tienes instalado, no te preocupes puedes hacerlo desde el [sitio oficial de Node](https://nodejs.org/es/)

Una ves que tengamos instalado node, estamos listos par continuar, verifiquemos que node este instalado y que npm venga con el.

```shell
node -v
npm -v
```

### Node y npm 

Node y npm son cosas diferentes sin embargo una perderia sentido sin la otra.

Para crear un programa en node es necesario usar npm, pero antes que nada...

```shell
npm -h
```

