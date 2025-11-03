# lab4 — Gráficos (Rust)

Repositorio de la práctica/laboratorio 4 de gráficos. Proyecto en Rust que contiene una pequeña aplicación de renderizado usando primitivas y carga de modelos desde `assets/`.

Contenido principal
- `src/` — código fuente en Rust (p. ej. `main.rs`, `triangle.rs`, `vertex.rs`, `fragment.rs`, `framebuffer.rs`).
- `assets/` — modelos y recursos (por ejemplo `models/Nave.mtl`).
- `Cargo.toml` — configuración y dependencias de Cargo.

Requisitos
- Rust toolchain (rustc + cargo). Recomendado: la toolchain `stable`.

Cómo compilar (Windows PowerShell)

1. Abrir PowerShell en la carpeta del proyecto (la raíz donde está `Cargo.toml`).
2. Ejecutar:

```powershell
cargo build
```

Esto descargará dependencias y compilará el proyecto en modo debug.

Cómo ejecutar

Después de compilar, ejecutar la aplicación con:

```powershell
cargo run
```

Si prefieres usar la versión optimizada/release:

```powershell
cargo build --release
cargo run --release
```

Estructura rápida y puntos de interés
- `src/main.rs` — punto de entrada y flujo principal.
- `src/triangle.rs`, `src/line.rs`, `src/vertex.rs` — código relacionado con geometría y vértices.
- `src/fragment.rs`, `src/shaders.rs` — fragmentos/efectos y shaders emulados.
- `assets/` — coloca aquí modelos adicionales o recursos necesarios.

Comprobación rápida

- Para una comprobación inicial: `cargo build` debería terminar sin errores. Si hay errores, revisa la salida del compilador; suele indicar la ruta y línea donde se produjo el fallo.

Notas
- Este README es minimalista por diseño. Si necesitas que añada ejemplos de uso, capturas de pantalla, o instrucciones para dependencias adicionales (por ejemplo librerías del SO), dímelo y lo añado.

Licencia
- Añade aquí la licencia si corresponde (por ejemplo MIT, Apache-2.0). Actualmente no se especifica ninguna.

Contacto
- Pregunta cualquier duda o pide que añada instrucciones específicas para Windows, Linux o integraciones con IDEs.

![alt text](<NAVE.jpg>)