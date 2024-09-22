# eaapi-snippets README

Bu Açık Atolye adına Emre Aydemir tarafından geliştirilmiş EAApi konsepti için yardımcı snippetler barındıran bir snippet kitidir.

## Features

### EAAPI

service, s: temel servis kodu üretir
controller, c: temel controller kodu üretir
module, m: temel module kodu üretir
BaseModel, bm: BaseModel'i kalıtım alan entity üretir
TypeModel, tm: TypeModel'i kalıtım alan entity üretir

### EAAdmin

baseModelSchema, bms,: BaseModeli içeren schema ve model üretir
typeModelSchema, tms: TypeModel içeren schema ve model üretir
requiredVariable, rv: schema da kullanılacak required değişken üretir
nullableVariable, nv: schema da kullanılacak nullable değişken üretir
selectTypeVariable, stv: select türü olan id ve name sahip olan değişken üretir
formColumnElement, fce: formColumn element üretir
TypeViewModel, tvm: Type içeren viewmodel üretir
BaseViewModel, bvm: base model içeren viewmodel üretir.
service, s: front servisi üretir

## Derleme ve kurulum

```bash
vsce package
code --install-extension eaa-snippets-0.0.1.vsix
```
