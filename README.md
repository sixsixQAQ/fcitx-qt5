## Environment

The libraries were generated on debian 11 with gcc 10.2.1-6, qt 6.3.1 and qt 5.15.2.

## Usage
First, choose the .so file version you need, Qt6 or Qt5.
(
  `libfcitxplatforminputcontextplugin-qt6.so` 
or
  `libfcitxplatforminputcontextplugin.so`
）


Then put  the .so  file  to the path below :

```shell
<QT_PATH>/Tools/QtCreator/lib/Qt/plugins/platforminputcontexts/
```

Change the permission of it:
```shell
chmod 755 *.so
```

Resatrt Qt Creator, and you can enter Chinese character in it now.
