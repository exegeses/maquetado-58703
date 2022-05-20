# Tipos de selectores

> En css tenemos diferentes tipos de selectores

## Selector de etiqueta
> Utilizamos el selector de etiqueta para redefinir la estética de una etiqueta en el HTML, ***cada vez*** que aparezca en el documento.

    p{
        padding:16px;
        /* todos los párrafos tendrán 16px de padding */
    }

## Selector de ID
> Utilizamos el selector de ID para identificar a un elemento ***único*** en el HTML. O sea que ***no se va a repetir***.
> No debemos tener en un mismo documento HTML dos o más elementos con el mismo ID

    #nombreID{
        color: #ddd;
    }

## Selector de class
> Utilizamos el selector de clase para elementos que ***se van a repetir***, o sea varios con le misma estética

    .nombreClase{
            color: #0d0;
    }
