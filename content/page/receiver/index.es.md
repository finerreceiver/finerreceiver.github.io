---
title: "Receiver"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-04-06T16:26:29Z
featured: false
draft: false
---

## Especificaciones

FINER es un sistema receptor SIS de doble polarización con separación de bandas laterales (2SB). Las tablas resumen la configuración instalada para la primera luz y las metas de diseño del sistema completo.

| General | |
|---|---|
| Número de bandas | 2 (en la primera luz se observa una banda a la vez) |
| Haces por banda | 1 |
| Polarizaciones por banda | 2 |
| Bandas laterales por banda | 2 (2SB) |

| | Banda 4 (primera luz) | Banda 6+7 | Banda 4+5 (mejora prevista) |
|---|---|---|---|
| Radiofrecuencia | ≈138–178 GHz | ≈210–351 GHz | 120–210 GHz |
| Frecuencia intermedia (por banda lateral y polarización) | 4–8 GHz | 4–20 GHz | 4–20 GHz |
| Temperatura de ruido del receptor (SSB, meta de diseño) | — | 75 K | 45 K |

El desempeño medido se publicará aquí después de la puesta en marcha en el LMT.

## Descripción del sistema

En la primera luz, FINER tiene dos receptores de entrada (front-end) en un mismo criostato: un receptor MMIC de banda 4 y un receptor de banda ancha de banda 6+7, ambos desarrollados en el NAOJ. Se prevé añadir más adelante un receptor de banda ancha de banda 4+5 que cubra 120–210 GHz. Unos conmutadores de FI seleccionan qué banda alimenta las cuatro cadenas de FI, de modo que se observa una banda a la vez; la observación simultánea en dos bandas es una opción para una futura mejora de la óptica.

![blockdiagram](blockdiagram.png)
**Figura. Diagrama de bloques del sistema FINER completo (diseño).**

### Óptica
La óptica a temperatura ambiente de FINER toma el haz después del espejo M4 del LMT mediante un par de espejos motorizados (el «periscopio»), que pueden colocarse y retirarse a distancia. Un chopper con una carga de cuerpo negro se usa para la calibración de intensidad. Más adelante se prevé un chopper rápido de cielo para la conmutación rápida de posición. La resolución espacial (tamaño de la PSF) es de unos 7 segundos de arco × (frecuencia / 200 GHz)<sup>−1</sup>.

### Receptores de entrada
Los receptores de entrada aprovechan la tecnología de mezcladores SIS de alta densidad de corriente crítica desarrollada para la ampliación de ancho de banda y sensibilidad de ALMA (WSU) ([Kojima et al. 2017](https://ui.adsabs.harvard.edu/abs/2017ITTST...7..694K/), [2020](https://ui.adsabs.harvard.edu/abs/2020A%26A...640L...9K/); [Kang et al. 2026](https://arxiv.org/abs/2606.25637)), que proporciona una amplia cobertura de frecuencia instantánea.

### Espectrómetros
- **Espectrómetros de banda ancha (DRS4, ELECS Inc.).** Dos chasis DRS4 digitalizan ocho bandas base de 10.24 GHz de ancho con convertidores analógico-digitales de 3 bits a 20.48 GSa/s y producen espectros con resolución de 20 MHz ([Hagimoto et al. 2024](https://doi.org/10.1117/12.3018296)). La separación de bandas laterales también se realiza digitalmente.
- **Espectrómetros de alta resolución (XFFTS, RPG).** Los espectrómetros XFFTS del receptor de 2 mm del LMT, B4R (2.5 GHz de ancho de banda, 88 kHz de resolución), siguen disponibles para espectroscopía de alta resolución.

### Datos y software
FINER se controla desde el sistema de control del telescopio del LMT. El formato de datos y el sistema de reducción se están desarrollando junto con el equipo del LMT.

## Documentos técnicos

| Documento | Versión | Descarga |
|---|---|---|
| Propuesta de FINER al LMT (en inglés) | Versión A, 15 de junio de 2023 | [PDF (5 MB)](/files/FINER_Proposal_verA.pdf) |

La propuesta describe el diseño y el plan originales; la configuración y el calendario se han actualizado desde entonces, como se describe en esta página.

## Referencias
Consulte [Publicaciones](../publications/) para los artículos sobre el instrumento.
