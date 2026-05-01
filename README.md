# CeVi Voice Demo

Asistente de voz integrado de las máquinas láser C4V — demo del flujo conversacional.

Acceso: https://sebastianjcv97.github.io/cevi-demo/

Demo standalone que usa:
- Web Speech API (reconocimiento de voz nativo del navegador)
- Web Speech Synthesis (síntesis de voz nativa)
- Match local de keywords contra 24 entradas de la KB

En producción real:
- Reconocimiento: Groq Whisper Large v3
- Cerebro: Claude Haiku 4.5 + RAG
- Voz: Edge TTS Dalia (es-MX-DaliaNeural)
- Hardware: ESP32-S3 con micrófono I2S y parlante

Más info: C4V Laser · sebastianjcv97@gmail.com
