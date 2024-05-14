# MauiCameraMediaFileDivice

## Descripcion 
En esta aplicacion se usa la camara del dispositivo android y windows  

## Configuración de Android Manifest

A continuación se muestra el `AndroidManifest.xml` necesario para la aplicación, que incluye los permisos y configuraciones requeridos:

```xml
<?xml version="1.0" encoding="utf-8"?>
<manifest xmlns:android="http://schemas.android.com/apk/res/android">
    <application android:allowBackup="true" android:icon="@mipmap/appicon" android:roundIcon="@mipmap/appicon_round" android:supportsRtl="true"></application>
    <uses-permission android:name="android.permission.ACCESS_NETWORK_STATE" />
    <uses-permission android:name="android.permission.INTERNET" />
    <uses-permission android:name="android.permission.CAMERA" />
    <uses-permission android:name="android.permission.READ_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.WRITE_EXTERNAL_STORAGE" />
    <uses-permission android:name="android.permission.READ_MEDIA_AUDIO" />
    <uses-permission android:name="android.permission.READ_MEDIA_IMAGES" />
    <uses-permission android:name="android.permission.READ_MEDIA_VIDEOS" />
    <queries>
        <intent>
            <action android:name="android.media.action.IMAGE_CAPTURE" />
        </intent>
    </queries>
</manifest>
```

## Licencia

Este proyecto está licenciado bajo la Licencia MIT - mira el archivo [LICENSE.md](https://www.youtube.com/watch?v=aUbasIfag-E) para detalles
