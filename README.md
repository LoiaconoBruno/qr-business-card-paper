# Una tarjeta con QR: paper de uso y guía de la idea

**Tarjeta digital.** Armá tu tarjeta en tres pasos y compartila como contacto (.vcf), como imagen con un QR que cualquier cámara convierte en contacto, por AirDrop, o con un enlace propio que podés grabar en un sticker NFC. Sin servidor, sin dependencias y con un codificador QR propio.

Paper de uso y guía de la idea detrás de **[QR Business Card](https://github.com/LoiaconoBruno/qr-business-card)**. Explica cómo se usa la herramienta, cómo funciona por dentro y qué dicen los especialistas sobre la idea de fondo, con referencias verificables.

- 📄 **[Leer el paper](https://loiaconobruno.github.io/qr-business-card-paper/)**
- 💻 **[Código](https://github.com/LoiaconoBruno/qr-business-card)**
- ▶ **[Probar la herramienta](https://loiaconobruno.github.io/qr-business-card/)**

> Preprint de Bruno Loiacono, estudiante de Física (Universidad de Buenos Aires). Documento de trabajo sin revisión por pares. Forma parte de [Ideas](https://github.com/LoiaconoBruno/ideas).

## Cómo se genera

`paper.md` es la fuente. La versión web (`index.html`) se arma con un script sin dependencias:

```bash
python3 tools/guia.py
```

## Licencia

El texto está bajo [CC BY 4.0](LICENSE-CC-BY-4.0.txt). El script que arma la versión web está bajo MIT. El detalle está en [LICENSE](LICENSE).
