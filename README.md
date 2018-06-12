# new-project-cocos2dx-js
Documentación para comenzar con Cocos2Dx-JS

1. Crear proyecto:
```bash
cocos new -l js WebGame
```
2. Ejecutar proyecto:
```bash
cocos run -p web
```
3. Compilar y publicar proyecto:
```bash
cocos run -p web -m release [--advanced]
```
4. Ejecutar tests:
```bash
// Or enter js test folder
cd tests/js-tests

// Compile or run test case
cocos compile -p ios|mac|android|win32|win8_1|metro|web -m debug|release
cocos run -p ios|mac|android|win32|win8_1|metro|web -m debug|release
```