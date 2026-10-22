# VideoFake-HeadSwap

Ayrı Colab projesi: **daha geniş kafa / saç çizgisi** kapsayan yüz değişimi (FaceFusion tabanlı).

VideoFake (roop/inswapper) sadece yüzü değiştirir. Bu proje FaceFusion ile maskeyi **üste (saça doğru)** genişleterek alın + saç çizgisi + daha fazla kafa bölgesini kapsar.

> Gerçek “saç modeli transferi” (kısa → uzun saç vb.) değildir. Kaynakla **benzer saç** + geniş maske en iyi sonucu verir.

## Open in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ixelizm/VideoFake-HeadSwap/blob/main/HeadSwap_colab.ipynb)

## Quick start

1. Runtime → **GPU**
2. Hücreleri sırayla çalıştır
3. Yüz fotoğrafı + hedef video yükle
4. `HairBias` / padding ayarlarını dene, Run, Download

Related: [ixelizm/VideoFake](https://github.com/ixelizm/VideoFake) (klasik face-only swap)
