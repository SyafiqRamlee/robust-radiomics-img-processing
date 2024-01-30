# Robustness of [18F]-FDG-PET radiomic features to image processing variations

Data repository for the study and manuscript titled "Mitigating the impact of image processing variations on [18F]-FDG-PET radiomic feature robustness: a comprehensive multi-cancer investigation" by Syafiq Ramlee, Roido Manavaki, Luigi Aloj, and Lorena Escudero Sanchez.


## Folder structure

Plots generated for this study have been segregated according to the image processing scheme, cancer type, and algorithm considered, as per the folder structure below:

```
📦 main
├─ discretisation
│  ├─ NSCLC
│  │  ├─ FBW
│  │  └─ FBN
│  ├─ MELANOMA
│  │  └─ as above
│  └─ LYMPHOMA
│     └─ as above
└─ interpolation
   ├─ NSCLC
   │  ├─ linear
   │  ├─ nearest_neighbour
   │  ├─ b_spline
   │  └─ gaussian
   ├─ MELANOMA
   │  └─ as above
   └─ LYMPHOMA
      └─ as above
```


