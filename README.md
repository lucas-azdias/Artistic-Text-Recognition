# Avaliando Abordagens do Estado da Arte para Reconhecimento de Textos Artísticos

*Evaluating State-of-the-Art Approaches to Artistic Text Recognition*

**ICDAR 2024 Competition on Artistic Text Recognition**

<picture>
    <source
        srcset="https://raw.githubusercontent.com/lucas-azdias/PUCPR-SVG/ea4f6a6f371fa7c4b26b84b4ad8e00db2b830b9b/branco/pucpr-completa.svg"
        media="(prefers-color-scheme: dark)"
        height="80px"
    />
    <source
        srcset="https://raw.githubusercontent.com/lucas-azdias/PUCPR-SVG/ea4f6a6f371fa7c4b26b84b4ad8e00db2b830b9b/cor-primaria/pucpr-completa.svg"
        media="(prefers-color-scheme: light), (prefers-color-scheme: no-preference)"
        height="80px"
    />
    <img
        src="https://raw.githubusercontent.com/lucas-azdias/PUCPR-SVG/ea4f6a6f371fa7c4b26b84b4ad8e00db2b830b9b/cor-primaria/pucpr-completa.svg"
        height="80px"
    />
</picture>

---

## Links relevantes
- [Competição](https://sites.google.com/view/icdar-2024-competition-wordart/)
- [Resultados da competição](https://codalab.lisn.upsaclay.fr/competitions/17182#results)

## Dataset
- [Dataset compilado](https://github.com/lucas-azdias/WordArt-V1.5-Dataset)
- [Dataset treino](https://drive.google.com/file/d/1Lq6xKNbD7Kvs-i1myJPmwBLLG5YnoM9N/view)
- [Dataset teste A (validação)](https://drive.google.com/file/d/15tkLbdXYzIILVWIg4kqjPMJ51p-vD2Ej/view)
- [Dataset teste B (teste)](https://drive.google.com/file/d/1Q7kAqFITGntZAn-HuCh8vQpHTpDkPSAH/view)

## Modelos
- [Modelo PARSeq](https://github.com/baudm/parseq) [(PAPER)](https://arxiv.org/pdf/2207.06966)
- [Modelo SVTRv2](https://github.com/Topdu/OpenOCR/blob/main/configs/rec/svtrv2/readme.md) [(PAPER)](https://arxiv.org/pdf/2411.15858)
- [Modelo MAERec](https://github.com/Mountchicken/Union14M/tree/main?tab=readme-ov-file#5-maerec) [(PAPER)](https://arxiv.org/pdf/2307.08723)

## Métodos aplicados
- [_Ensemble_](https://ieeexplore.ieee.org/document/9893798) [(PAPER)](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9893798)
- [Algoritmo de Needleman–Wunsch](https://www.sciencedirect.com/science/article/abs/pii/S0020025513001485)
- [Comparação de textos pelo alinhamento com Algoritmo de Needleman-Wunsch](https://www.researchgate.net/publication/44276712_Improving_search_in_scanned_documents_Looking_for_OCR_mismatches)
- [Dicionário para correção de erros pós-OCR](https://dl.acm.org/doi/abs/10.1145/3453476) [(PAPER)](https://dl.acm.org/doi/pdf/10.1145/3453476)

## Relacionados
- [Método ViTSTR](https://github.com/kwon-evan/ViTSTR) [(PAPER)](https://arxiv.org/pdf/2105.08582)
