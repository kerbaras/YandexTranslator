# YandexTranslator
An implementation for the Yandex rest translation service for smalltalk

## Instalation
```
Gofer it
    smalltalkhubUser: 'matiaspierobon' project: 'YandexTranslator';
    configurationOf: 'YandexTranslator';
    loadDevelopment.
```

## Usage
```
YandexTranslator translate: 'I love smalltalk' to: 'fr'.
YandexTranslator translate: 'Me gusta smalltalk' from: 'es' to: 'fr'.
YandexTranslator new
    from: 'es';
    to: 'en';
    text: 'El texto a traducir';
    translate.
```
