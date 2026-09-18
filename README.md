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
| Cifrado simétrico | DES · 3DES · AES; modos GCM/CBC/CTR/ECB; ataque CPA sobre ECB (imagen); comparativa de cifradores de bloque |
| Cifrado asimétrico (RSA-2048) | Alice/Bob con clave pública y privada; problema de factorización |
| Intercambio de claves (Diffie-Hellman) | Derivar un secreto compartido en canal público; MITM y forward secrecy |
| Funciones hash | MD5/SHA-1/SHA-256/SHA-512; efecto avalancha; propiedad de una sola vía |
| Firma digital | RSA-PSS real: firmar, verificar y detectar manipulación |
| PKI y certificados | Cadena de confianza, certificado X.509, validación y escenarios de fallo (CA, caducidad, MITM) |
| Protocolos seguros | Handshake TLS 1.3, sobre híbrido PGP en vivo, referencia de comandos OpenSSL |
| Esteganografía | Ocultación LSB en imágenes combinada con cifrado RSA/AES |
| Cifrar archivos | AES-256-GCM + PBKDF2, cifrado y recuperación de ficheros |
| Criptoanálisis | KPA, CCA (maleabilidad RSA textbook) |
| Ataques de implementación | Padding Oracle (CBC), Timing Attack, análisis de potencia (SPA) |
| Fallos históricos | Colisión MD5 real, reutilización de keystream en WEP/RC4 |
| Mitigaciones | Servicios de seguridad por algoritmo y tabla resumen de buenas prácticas |

## Ejecutar en local

Es una única página estática. Basta con abrir `index.html` en el navegador, o servirla:

```bash
python3 -m http.server 8000
# luego abre http://localhost:8000
```

## Aviso

Material didáctico. Usa este conocimiento únicamente con sistemas propios o con autorización.
