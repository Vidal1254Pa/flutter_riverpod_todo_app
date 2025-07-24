# Flutter Riverpod Todo App
[![Flutter version](https://img.shields.io/badge/flutter-3.10.6-blue?logo=flutter)](https://flutter.dev/docs/development/tools/sdk/releases)
[![License: MIT](https://img.shields.io/badge/license-MIT-purple.svg)](https://opensource.org/licenses/MIT)

Esta es una aplicación Todo simple construida usando Flutter y Riverpod, demostrando cómo realizar operaciones CRUD (Crear, Leer, Actualizar, Eliminar) de manera limpia y mantenible. Riverpod se utiliza como la solución de gestión de estado para la aplicación, promoviendo un enfoque declarativo y eficiente para manejar el estado de la aplicación.

## Prerrequisitos:

### Java Development Kit (JDK) 17
Este proyecto requiere Java 17 para el desarrollo de Android. Asegúrate de tener instalado JDK 17.

#### Instalación de Java 17:
```bash
# Verificar la versión actual de Java
java -version

# Windows (usando Chocolatey)
choco install openjdk17

# macOS (usando Homebrew)
brew install openjdk@17

# Ubuntu/Debian
sudo apt update
sudo apt install openjdk-17-jdk

# Configurar JAVA_HOME (Windows)
setx JAVA_HOME "C:\Program Files\OpenJDK\openjdk-17"

# Configurar JAVA_HOME (macOS/Linux)
export JAVA_HOME=/usr/lib/jvm/java-17-openjdk
```

### Flutter Version Management (FVM)
Este proyecto requiere Flutter versión 3.10.6. Se recomienda usar FVM para manejar las versiones de Flutter.

#### Instalación de FVM:
```bash
# Instalar FVM globalmente usando pub
dart pub global activate fvm

# O usando Homebrew (macOS)
brew tap leoafarias/fvm
brew install fvm

# O usando Chocolatey (Windows)
choco install fvm
```

#### Configurar Flutter 3.10.6:
```bash
# Instalar Flutter 3.10.6
fvm install 3.10.6

# Usar Flutter 3.10.6 en este proyecto
fvm use 3.10.6

# Verificar la versión
fvm flutter --version
```

## Comenzando:

1. Clona este repositorio en tu máquina local.
```bash
git clone https://github.com/IsaiasCuvula/flutter_riverpod_todo_app
cd flutter_riverpod_todo_app
```

2. Configura Flutter 3.10.6 usando FVM:
```bash
fvm use 3.10.6
```

3. Instala las dependencias del proyecto:
```bash
fvm flutter pub get
```

4. Ejecuta la aplicación en un emulador o dispositivo físico:
```bash
fvm flutter run
```

### Comandos útiles con FVM:
- `fvm flutter --version` - Verificar la versión de Flutter
- `fvm flutter doctor` - Verificar la configuración del entorno
- `fvm flutter clean` - Limpiar el proyecto
- `fvm flutter pub get` - Obtener dependencias

<p align="left">
 <img width="200" alt="iPhone13Mockup3" src="https://github.com/IsaiasCuvula/flutter_riverpod_todo_app/assets/68303716/161762c8-f304-4b19-9f4e-4006f50fdc83" />

<img width="200" alt="iPhone13Mockup2" src="https://github.com/IsaiasCuvula/flutter_riverpod_todo_app/assets/68303716/f23c201c-77d3-4fec-9339-3c9b47dce835" />
  
<img width="200" alt="iPhone13Mockup1" src="https://github.com/IsaiasCuvula/flutter_riverpod_todo_app/assets/68303716/62148f69-34f8-4f49-9889-a6649336723b" />
</p>

