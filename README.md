# cp-6bm1-equipo8 — Cómputo Paralelo · 6BM1 · 27/1

Repositorio del equipo 8 para las Prácticas 1–6 y el proyecto integrador.

## Integrantes

| Nombre | Boleta | Usuario GitHub |
| :--- | :--- | :--- |
| Flores López Mariana | 2024630852 | marianafloreslopez99 |
| Gonzalez Gonzalez Alan | 2024630830 | Alan-GG117 |
| Pérez Guzmán Shaiel Aylin | 2024630673 |ayliinperezg01 |

## Fichas técnicas de hardware

### Flores López Mariana
| Campo | Valor |
| :--- | :--- |
| Modelo de CPU | AMD Ryzen 7 5700U with Radeon Graphics |
| Núcleos físicos / Hilos lógicos | 8 / 16 |
| Frecuencia Base / Turbo | 1.80Ghz / 4.30GHz |
| Caché L1d / L2 / L3 | L1d: 256 KiB <br>L2: 4 MiB <br>L3: 4 MiB |
| Memoria RAM | 7.4Gb |
| Extensiones Vectoriales | SSE4.2, AVX, AVX2 y FMA  |
| Sistema operativo y kernel | Ubuntu 24.04.5 LTS (WSL2) / Kernel 6.18.40.1-microsoft-standard-WSL2  |
| Compilador | Gcc y g++ 13.3.0 |
| Python / NumPy / BLAS | Python 3.12.13, NumPy 2.5.3, OpenBLAS 0.3.34.106.0 |
| GPU (Si hay) | AMD Radeon Graphics integrada; no se detectó GPU NVIDIA mediante nvidia-smi |
| Condiciones | Computadora conectada a la corriente, sin otras aplicaciones de alto consumo abiertas, pruebas ejecutadas en WSL2 |

### González González Alan
| Campo | Valor |
| :--- | :--- |
| Modelo de CPU | AMD Ryzen 7 6800H with Radeon Graphics |
| Núcleos físicos / Hilos lógicos | 8 / 16 |
| Frecuencia Base / Turbo | 3.20Ghz / 4.7GHz |
| Caché L1d / L2 / L3 | L1d: 256 KiB (8 instances)<br>L2: 4 MiB (8 instances)<br>L3: 16 MiB (1 instance) |
| Memoria RAM | 7.4Gb |
| Extensiones Vectoriales | Avx avx2 fma sse4_2 |
| Sistema operativo y kernel | Ubuntu 24.04 en WSL2, kernel 6.6 |
| Compilador | Gcc y g++ 13.3.0 |
| Python / NumPy / BLAS | Python 3.12.3, NumPy 2.5.3, OpenBLAS 0.3.34.106.0 |
| GPU (Si hay) | Nvidia GeForce RTX 3060 |
| Condiciones | Computadora conectada a la corriente, en modo "Turbo". Medición hecha en un entorno virtualizado. Durante la prueba, en Windows estaba abierto VSCode, CMD, Adobe Acrobat Reader y Word. |

### Pérez Guzmán Shaiel Aylin
| Campo | Valor |
| :--- | :--- |
| Modelo de CPU | AMD Ryzen 5 5500U with Radeon Graphics |
| Núcleos físicos / Hilos lógicos | 6 / 12 |
| Frecuencia Base / Turbo | Pendiente de consultar las especificaciones del modelo |
| Caché L1d / L2 / L3 | L1d: 192 KiB <br>L2: 3 MiB <br>L3: 4 MiB |
| Memoria RAM | 6.7Gb |
| Extensiones Vectoriales | SSE, SSE2, SSE3 (aparece como pni), SSSE3, SSE4.1, SSE4.2, AVX, AVX2 y FMA |
| Sistema operativo y kernel | Ubuntu 24.04, ejecutado mediante WSL2; kernel 6.18.40.1-microsoft-standard-WLS2 |
| Compilador | Gcc y g++ 13.3.0 |
| Python / NumPy / BLAS | Python 3.12.13, NumPy y BLAS pendiente de verificar. GPU pendiente de verificar, el equipo reporta gráficos integrados AMD Radeon. |
| GPU (Si hay) | Gráficos integrados AMD Radeon (™) Graphics, detectados por Windows. No se ha verificado su disponibilidad para cómputo general desde WSL2. |
| Condiciones | Laptop con Windows 11 y Ubuntu 24.04 mediante WSL2. Las mediciones se realizaron en un entorno virtualizado. |

## Convenciones

- Rama `main` siempre funcional; trabajo en ramas `practicaN/...` con pull request.
- Mensajes de commit descriptivos; commits de los tres integrantes.
- Cada práctica se entrega con una etiqueta (`practica1`, `practica2`, ...).
