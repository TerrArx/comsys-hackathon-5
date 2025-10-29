# comsys-hackathon-5
A hackathon project developed for COMSYS Hackathon 5 on gender classification and face recognition using deep learning by Team **f2f**

## Team Members
- [Idries Ahamed K A](https://github.com/1drie5)  
- [Nabil Ahmed](https://github.com/TerrArx)  
- [SK Faizanuddin](https://github.com/SKfaizan-786)  

## Problem Statement

### Task A: Gender Classification
- **Type:** Binary Classification  
- **Goal:** Classification of Face Potraits as male or female.  
- **Dataset Structure:**  
```
Task_A/
├── train/
│   ├── male/
│   └── female/
└── val/
    ├── male/
    └── female/
```

### Task B: Face Recognition
- **Type:** Multi-Class Classification  
- **Goal:** Match input face (or distorted variant) to correct identity.  
- **Dataset Structure:**  

```
Task_B/
├── train/
│   └── <Person Name>/
│       ├── <person>.jpg
│       └── Distortion/
│           ├── <person>_blurred.jpg
│           ├── <person>_foggy.jpg
│           └── ...
├── val/
│   └── <Person Name>/
        ├── <person>.jpg
        └── Distortion/
            ├── <person>_lowlight.jpg
            └── ...
```

- **Labeling Rule:**  
- Match = 1 (same identity)  
- Non-match = 0 (different identity)  

## Dataset
[FACECOM – Google Drive](https://drive.google.com/drive/folders/1h9PqzIF1Kq-9p8r69ifZvo9ie_EmB1Ym?usp=sharing)

## License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.
