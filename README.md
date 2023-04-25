## Usage
First, choose the .so file version you need, Qt6 or Qt5.

`libfcitxplatforminputcontextplugin-qt6.so` 
or
`libfcitxplatforminputcontextplugin.so`
）

Then put  the .so file  to the path below :
```shell
<QT_PATH>/Tools/QtCreator/lib/Qt/plugins/platforminputcontexts/
```

Then change the permission of it:
```shell
chmod 755 *.so
```

Resatrt Qt Creator, and you can enter Chinese character in it now.
