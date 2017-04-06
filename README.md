# nextcloud-presidencia
### Instalación
Dentro de la carpeta *themes* del sitio Nextcloud se debe clonar el repositorio con el siguiente comando:
```sh
git clone git@github.com:opintel/nextcloud-presidencia.git
```

Despues se debera editar el archivo *config/config.php* teniendo como referencia la carpeta raiz del proyecto de Nextcloud. Se debera editar o agregar la linea siguiente al arrray de configuración:
```php
<?php
$CONFIG = array (
...
'theme' => 'nextcloud-presidencia',
...
);
```
Por ultimo se debe reiniciar el servidor apache con permisos de administrador:
```sh
sudo service apache2 restart
```
