
# EAAPI Snippets - README

Bu proje, Açık Atölye adına Emre Aydemir tarafından geliştirilen EAApi konseptine yardımcı olan snippet'leri içerir. EAAPI ve EAAdmin modülleri ile projelerinizde hızlı ve standartlaştırılmış kod üretimi sağlayarak işlerinizi hızlandırmayı amaçlar.

## Özellikler

### EAAPI Snippet'leri

- **service** (`s`): Temel servis kodu oluşturur.
- **controller** (`c`): Temel controller kodu oluşturur.
- **module** (`m`): Temel module kodu oluşturur.
- **BaseModel** (`bm`): `BaseModel` sınıfını kalıtım alan bir entity oluşturur.
- **TypeModel** (`tm`): `TypeModel` sınıfını kalıtım alan bir entity oluşturur.

### EAAdmin Snippet'leri

- **baseModelSchema** (`bms`): `BaseModel` içeren schema ve model oluşturur.
- **typeModelSchema** (`tms`): `TypeModel` içeren schema ve model oluşturur.
- **requiredVariable** (`rv`): Schema'da kullanılacak required değişkeni oluşturur.
- **nullableVariable** (`nv`): Schema'da kullanılacak nullable değişkeni oluşturur.
- **selectTypeVariable** (`stv`): `id` ve `name` alanlarına sahip select türünde bir değişken oluşturur.
- **formColumnElement** (`fce`): `formColumn` elementini oluşturur.
- **TypeViewModel** (`tvm`): `Type` içeren bir viewmodel oluşturur.
- **BaseViewModel** (`bvm`): `BaseModel` içeren bir viewmodel oluşturur.
- **service** (`s`): Frontend servisi oluşturur.

## Derleme ve Kurulum

EAAPI Snippet paketi Visual Studio Code'a kolayca entegre edilebilir. Aşağıdaki komutları kullanarak paketi derleyebilir ve kurabilirsiniz:

```bash
vsce package
code --install-extension eaa-snippets-0.0.1.vsix
```
