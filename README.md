# Cripto·Lab — Laboratorio de Criptografía

Sitio educativo interactivo para que estudiantes comprendan las distintas formas de usar
la criptografía: cifrado **simétrico** (AES), **asimétrico** (RSA) y **funciones hash**,
con ejemplos de Alice y Bob, cifrado de archivos, medición del tiempo de ejecución y
demostraciones **en vivo** de vulnerabilidades y criptoanálisis.

Todo se ejecuta en el navegador (Web Crypto API + crypto-js); ningún dato sale del equipo.

## 🌐 Ver el sitio

GitHub Pages: **https://edison-enriquez.github.io/criptografia/**

## Contenido

| Sección | Qué demuestra |
| --- | --- |
| Cifrado simétrico (AES) | Modos GCM/CBC/CTR/ECB, tiempo de ejecución, ataque CPA sobre ECB (imagen) |
| Cifrado asimétrico (RSA-2048) | Alice/Bob con clave pública y privada, problema de factorización |
| Funciones hash | MD5/SHA-1/SHA-256/SHA-512, efecto avalancha, propiedad de una sola vía |
| Cifrar archivos | AES-256-GCM + PBKDF2, cifrado y recuperación de ficheros |
| Criptoanálisis | KPA, CCA (maleabilidad RSA textbook) |
| Ataques de implementación | Padding Oracle (CBC), Timing Attack, análisis de potencia (SPA) |
| Fallos históricos | Colisión MD5 real, reutilización de keystream en WEP/RC4 |
| Mitigaciones | Tabla resumen de buenas prácticas |

## Ejecutar en local

Es una única página estática. Basta con abrir `index.html` en el navegador, o servirla:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Aviso

Material didáctico. Usa este conocimiento únicamente con sistemas propios o con autorización.
