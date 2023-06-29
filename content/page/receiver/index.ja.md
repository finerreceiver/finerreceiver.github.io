---
title: "Receiver"
subtitle: ""
summary: ""
authors: []
tags: []
categories: []
date: 2023-06-29T00:00:00Z
featured: false
draft: false
---

## FINER受信システムの仕様（2023年6月現在)
| General | |
|---|---|
| バンド数 | 2 (アルマ2のバンド4+5受信機、およびバンド6+7受信機に相当) |
| 1バンドあたりのビーム数 | 1 |
| 1バンドあたりの偏波数 | 2 |
| 1バンドあたりのサイドバンド数 | 2 |

| 項目 | 低周波バンド(Band 4+5) | 高周波バンド(Band 6+7) |
|---|---|---|
| 観測周波数(RF) | 125−210 GHz | 210−350 GHz|
| 中間周波数(IF) | 4-20.48 GHz | 4-20.48 GHz |
| 受信機雑音温度 | 45 K | 75 K |


## システムの概要
FINER consists of low- and high-frequency band SIS receivers, each of which covers the ALMA's Band 4+5 (120-210 GHz) and Band 6+7 (210-350 GHz), respectively. The front-end receivers are followed by the back-end spectrometers with wide-band and high-dispersion modes.

![blockdiagram](blockdiagram.png)
**Figure. Block diagram.**

### 光学系
A dual-polarization single beam from each receiver band is coupled with the LMT's optics. The FINER warm optics is planed to have a beam-switching mechanism which allows a quick (~1 Hz) position switching for atmospheric removal. The spatial resolution (i.e. PSF size) is 7 arcsec X (frequency/200 GHz)^-1, depending on observing frequency.

### フロントエンド受信機
The front-end receiver exploits the high critical current density SIS mixer technology ([Kojima et al. 2017](https://ui.adsabs.harvard.edu/abs/2017ITTST...7..694K/), [2020](https://ui.adsabs.harvard.edu/abs/2020A%26A...640L...9K/)) for ALMA 2 (wideband sensitivity upgrade, WSU), which allows us to have a wide instantaneous frequency coverage.

### バックエンド分光計
FINER has two sets of digital spectrometers with different spectral resolutions and bandwidths.

- Wide-band spectrometers (DRS4, ELECS Inc.). Analog IF input is digitized by a set of 3-bit 20.48 GSa/s analog-to-digital converters (ADCs), each of which offers a 10.24 GHz bandwidth with a 20 MHz spectral resolution.
- High-resolution spectrometers (XFFTS, RPG). spectroscopy is offered by the array of 2.5-GHz digital spectrometers, XFFTS (RPG).

### データ処理

## 技術文書

| Document | Version | Download |
|---|---|---|
| Proposal | 1-May-2023 | (in prep.) |
| Overview | 1-May-2023 | (in prep.) |

