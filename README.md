# How AI Works — Historia visual e interactiva de la IA/ML (traducción al español)

[![HTML5](https://img.shields.io/badge/HTML5-Canvas-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![License: Apache 2.0](https://img.shields.io/badge/Code-Apache_2.0-blue.svg)](https://www.apache.org/licenses/LICENSE-2.0)
[![License: CC BY 4.0](https://img.shields.io/badge/Content-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
![GitHub Forks](https://img.shields.io/github/forks/EncyclopediaWorld/howaiworks?style=flat)
[![GitHub stars](https://img.shields.io/github/stars/EncyclopediaWorld/howaiworks?style=social)](https://github.com/EncyclopediaWorld/howaiworks)
[![GitHub downloads](https://img.shields.io/github/downloads/EncyclopediaWorld/howaiworks/total?color=brightgreen&label=Downloads)](https://github.com/EncyclopediaWorld/howaiworks/releases)
[![Demos](https://img.shields.io/badge/Interactive_Demos-50-fb923c)](section1.html)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=EncyclopediaWorld.howaiworks)

> **50 modelos · 1805–2024 · 8 secciones · demos interactivas en canvas**
>
> De los Mínimos Cuadrados de Gauss a la generación de vídeo de Sora — cada hito explicado con visualizaciones “hands-on”.

**Aviso (fork público):** este repositorio es un *fork* no oficial con traducción al español. **No está afiliado, patrocinado ni avalado** por EncyclopediaWorld ni por el autor original. (Ver `BRAND_GUIDELINES.md`).

🔗 **Autor (obra original):** Dr. Yushun Dong (Florida State University)

🏷️ **Licencia:** código bajo Apache 2.0 · contenido bajo CC (ver detalle en la sección “Licencia”)

---

## Visión general

**How AI Works** es un sitio web estático y autocontenido que recorre la historia completa de la inteligencia artificial y el *machine learning* mediante **50 demos interactivas de modelos** que abarcan más de 200 años. Cada modelo incluye:

- 📄 **Enlace al paper** — enlace directo a la publicación original
- 🔗 **Linaje del modelo** — referencias cruzadas que muestran cómo cada modelo evoluciona a partir de otros y conduce a los siguientes
- 🎮 **Demo interactiva** — visualización en canvas con la que puedes hacer clic, pasar el ratón y explorar
- 📐 **Fórmula clave** — la ecuación (o arquitectura) central en una sola línea

Sin frameworks. Sin paso de *build*. Sin dependencias. Solo abre `index.html` en un navegador.

---

## Historial de estrellas

[![Star History Chart](https://api.star-history.com/svg?repos=EncyclopediaWorld/howaiworks&type=Date)](https://star-history.com/#EncyclopediaWorld/howaiworks&Date)

---

## Secciones y modelos

### Sección I — Raíces matemáticas (1805–1957)
| Año | Modelo | ID |
|------|-------|----|
| 1805 | Regresión lineal (mínimos cuadrados) | `#model-linreg` |
| 1812 | Teorema de Bayes | `#model-bayes` |
| 1847 | Regla de la cadena (cálculo) | `#model-chainrule` |
| 1906 | Cadenas de Markov | `#model-markov` |
| 1957 | Perceptrón | `#model-perceptron` |

### Sección II — Primeras máquinas de aprendizaje (1960–1967)
| Año | Modelo | ID |
|------|-------|----|
| 1960 | ADALINE | `#model-adaline` |
| 1963 | Clasificador Naive Bayes | `#model-naivebayes` |
| 1967 | K vecinos más cercanos (KNN) | `#model-knn` |

### Sección III — Reconocimiento de patrones y árboles (1980–1995)
| Año | Modelo | ID |
|------|-------|----|
| 1980 | Neocognitrón | `#model-neocognitron` |
| 1986 | Árbol de decisión (ID3/C4.5) | `#model-dtree` |
| 1995 | Random Forest (bosque aleatorio) | `#model-randomforest` |
| 1995 | SVM (Support Vector Machine / máquina de vectores de soporte) | `#model-svm` |
| 1997 | AdaBoost | `#model-adaboost` |

### Sección IV — Auge de las redes neuronales (1986–1997)
| Año | Modelo | ID |
|------|-------|----|
| 1986 | Retropropagación (backpropagation) | `#model-backprop` |
| 1985 | Máquina de Boltzmann | `#model-boltzmann` |
| 1989 | CNN / LeNet | `#model-cnn` |
| 1990 | RNN (red neuronal recurrente) | `#model-rnn` |
| 1997 | LSTM | `#model-lstm` |
| 1998 | GMM + algoritmo EM | `#model-gmm` |

### Sección V — Fundamentos del *deep learning* (2006–2011)
| Año | Modelo | ID |
|------|-------|----|
| 2006 | Deep Belief Network (DBN) | `#model-dbn` |
| 2006 | Autoencoder disperso (sparse autoencoder) | `#model-sparse-ae` |
| 2008 | Autoencoder con *denoising* | `#model-dae` |
| 2001 | GBDT (árboles potenciados por gradiente) | `#model-gbdt` |
| 2003 | NNLM (Neural Language Model) | `#model-nnlm` |

### Sección VI — Explosión del aprendizaje profundo (2012–2015)
| Año | Modelo | ID |
|------|-------|----|
| 2012 | AlexNet | `#model-alexnet` |
| 2014 | Dropout | `#model-dropout` |
| 2013 | Word2Vec | `#model-word2vec` |
| 2013 | VAE (autoencoder variacional) | `#model-vae` |
| 2014 | GAN (Generative Adversarial Network / red generativa adversaria) | `#model-gan` |
| 2014 | Seq2Seq + atención | `#model-seq2seq` |
| 2015 | ResNet (red residual) | `#model-resnet` |
| 2015 | Normalización por lotes (batch normalization) | `#model-batchnorm` |

### Sección VII — La revolución Transformer (2016–2019)
| Año | Modelo | ID |
|------|-------|----|
| 2016 | XGBoost | `#model-xgboost` |
| 2016 | WaveNet | `#model-wavenet` |
| 2017 | Transformer | `#model-transformer` |
| 2018 | ELMo | `#model-elmo` |
| 2018 | GPT-1 | `#model-gpt1` |
| 2018 | BERT | `#model-bert` |
| 2018 | StyleGAN | `#model-stylegan` |
| 2019 | GPT-2 | `#model-gpt2` |
| 2019 | T5 | `#model-t5` |

### Sección VIII — Modelos fundacionales y era AGI (2020–2024)
| Año | Modelo | ID |
|------|-------|----|
| 2020 | GPT-3 | `#model-gpt3` |
| 2020 | ViT (Vision Transformer) | `#model-vit` |
| 2021 | CLIP | `#model-clip` |
| 2020 | Modelos de difusión | `#model-diffusion` |
| 2022 | ChatGPT (RLHF) | `#model-chatgpt` |
| 2023 | LLaMA | `#model-llama` |
| 2023 | GPT-4 | `#model-gpt4` |
| 2024 | Claude (IA constitucional) | `#model-claude` |
| 2024 | Sora | `#model-sora` |

---

## Mapa de linaje de modelos

El sitio incluye hiperenlaces cruzados entre secciones que muestran cómo evolucionaron los modelos:

```
Least Squares ─→ ADALINE ─→ Backpropagation ─→ CNN/LeNet ─→ AlexNet ─→ ResNet ─→ ViT
                                                    │
Bayes ─→ Naive Bayes ─→ GMM+EM ──────────────────→ VAE ─→ Diffusion Models
                                                    │
Markov ─→ RNN ─→ LSTM ─→ Seq2Seq+Attention ─→ Transformer ─→ GPT/BERT/T5
                                                    │
Chain Rule ─→ Backprop ─→ DBN ─→ Sparse AE ─→ DAE ─────────→ Diffusion
                                                    │
Perceptron ─→ Boltzmann ─→ DBN ──────────────────→ AlexNet ─→ ResNet
                                                    │
Decision Tree ─→ Random Forest ─→ AdaBoost ─→ GBDT ─→ XGBoost
                                                    │
NNLM ─→ Word2Vec ─→ ELMo ─→ GPT-1 ─→ GPT-2 ─→ GPT-3 ─→ ChatGPT ─→ Claude
                                    │
                               BERT ─→ T5

Transformer ─→ ViT ─→ CLIP ─→ Stable Diffusion / DALL-E
         │
         ├─→ GPT-1 → GPT-2 → GPT-3 → ChatGPT → Claude
         ├─→ BERT → T5
         └─→ Sora (DiT = Diffusion + Transformer)

GAN ─→ StyleGAN ─→ (surpassed by) Diffusion Models ─→ Sora
```

> Nota: en esta traducción se mantienen muchos nombres de modelos en inglés por ser la convención más extendida; cuando ayuda, se añade la traducción o aclaración entre paréntesis.

---

## Detalles técnicos

### Arquitectura

- **Sitio estático puro** — HTML + CSS + JS, sin herramientas de *build*
- **Demos en canvas** — todas las visualizaciones usan la API HTML5 `<canvas>`
- **Utilidades compartidas** — `shared.js` aporta `createCanvas()`, `addControls()`, `addHint()` y utilidades matemáticas
- **Tema oscuro** — `styles.css` con propiedades CSS para colores de acento por sección
- **Responsive móvil** — todos los canvas escalan vía CSS (`width: 100%`)

### Estructura de archivos

```
.
├── index.html
├── section1.html
├── section2.html
├── section3.html
├── section4.html
├── section5.html
├── section6.html
├── section7.html
├── section8.html
├── styles.css
├── shared.js
└── README.md
```

**Tamaño total: ~280 KB** (sin imágenes, sin dependencias externas)

### Propiedades CSS (colores de acento)

```css
--a1: #38bdf8   /* Sección I   — azul     */
--a2: #ffd166   /* Sección II  — dorado   */
--a3: #4ecdc4   /* Sección III — turquesa */
--a4: #a78bfa   /* Sección IV  — púrpura  */
--a5: #ff6b6b   /* Sección V   — rojo     */
--a6: #fb923c   /* Sección VI  — naranja  */
--a7: #f472b6   /* Sección VII — rosa     */
--a8: #34d399   /* Sección VIII— verde    */
```

### Clases CSS especiales

- `.paper-link` — botón con estilo para enlaces a papers (icono 📄)
- `.model-lineage` — texto en cursiva para referencias cruzadas con enlaces coloreados
- `.author-line` — crédito sutil de autor/afiliación
- `.ew-logo` — logo SVG embebido
- `.mc-demo` — contenedor del canvas con escalado responsive

---

## Cómo usarlo

1. **Abrir en local:** haz doble clic en `index.html` — funciona *offline*
2. **Desplegar:** sube la carpeta completa a cualquier hosting estático (GitHub Pages, Netlify, Vercel, S3)
3. **Navegar:** haz clic en las tarjetas de sección en la home, o usa la barra superior (I–VIII)
4. **Interactuar:** cada demo incluye pistas, botones e interacción con ratón/clic
5. **Enlace directo:** usa `sectionN.html#model-name` para enlazar directamente a un modelo

---

## Licencia

Este proyecto usa una estructura de doble licencia:

- **Código** (JavaScript, CSS y código embebido en HTML) bajo **Apache License 2.0**. Ver `LICENSE`.
- **Contenido** (texto explicativo, narrativa y material educativo) bajo **CC BY‑NC 4.0** por defecto. Ver `CONTENT_LICENSE.md`.

**Marca / trademark:** el nombre del proyecto, el logo y la identidad visual **no** están cubiertos por las licencias anteriores. Los forks públicos deben renombrar y añadir un aviso claro de “no afiliado / no avalado”. Ver `BRAND_GUIDELINES.md`.

**Uso comercial:** si necesitas derechos comerciales para el contenido o quieres un despliegue/colaboración empresarial, ver `COMMERCIAL.md`.

---

## Créditos

- **Autor:** Dr. Yushun Dong, Florida State University
- **Diseño:** tema oscuro con colores de acento por sección, inspirado en visualización académica
- **Demos:** 50 visualizaciones interactivas con Canvas API “vanilla”
- **Papers:** cada modelo enlaza su publicación original (arXiv, JMLR, NeurIPS, etc.)

---

*Construido como recurso educativo para hacer accesible a todo el mundo la historia y la mecánica de la IA.*
