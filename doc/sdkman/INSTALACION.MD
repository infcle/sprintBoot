## I. INSTALACIÓN SDKMAN
**Pagina oficial https://sdkman.io/**

*Nota: solo se intala en distribuciones linux o macOS*

### Paso 01
Descarga e instalación (no utilizar usuario root)

```
curl -s "https://get.sdkman.io" | bash
```

### Paso 02

reinciar equipo o correr la siguiente instrucción

```
source "$HOME/.sdkman/bin/sdkman-init.sh"
```

### Paso 03

Verificar instalación

```
sdk version
```
---

## INSTALACIÓN JDK 11

### Paso 01

Instalar JDK 11

```
sdk install java 11.0.19-zulu
```

### Paso 02

Verificar version

```
java -version
```
---
## INSTALACIÓN MAVEN

### Paso 01

Instalar Maven

```
sdk install maven 3.6.3
```

### Paso 02

Verificar version

```
mvn -version
```
