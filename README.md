# Calculo de Cuotas

App que permite seleccionar automaticamente un Dato del Usuario y lo muestra en un formulario, para luego hacer unos calculos y generar editar un Ticket usando Zendesk Apps Tools (ZAT).


# Consideraciones

### Si vas a usar GNU/Linux, deberás tener instalado estas Dependencias:

* nodejs  >= 6.3.x
* libnotify-bin
* ruby  >= 2.0.x
* ruby-dev
* ruby-all-dev
* openssh
* build-essential
* rbenv
* zlib1-dev

### Para el uso del Zendesk Apps Tools (ZAT), deberá instalar:
``` 
 $ gem install zendesk_apps_tools
 $ gem install zendesk_apps_support
 $ gem install rake
 $ gem install sinatra
```


### Para Validar y Generar un paquete
``` 
 $ zat validate
 $ zat create
```

### Screenshot(s):
<p align="center">
<img src="http://www.seguridadsistema.com.ve/github/zendesk/pantalla-calculadora.png" />
</p>

## Autor (Author)

  Jesus Maria Lobaton Escobar < jesuslobaton@gmail.com >

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details
