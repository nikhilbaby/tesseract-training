# Tesseract Training for New Fonts

This repository has the scripts for installing and training Tesseract 4+. 

### Folder Structure
The project has the following structure:
```angular2
.
|-- README.md
|-- fonts                       // This is where you place the font
|-- install_tesseract.sh        // Script for installing Tesseract
|-- ouput                       // Checkpoints and model saved here
|-- train                       // Training Data is placed here
`-- training.sh                 // Script for Training Tesseract

```

### System Configurations
- Instance type   : `t2.large` 
- Storage         : `40GB`
- Operating System: `Ubuntu 18`

### Steps for Running the Project

1. Run `./install_tesseract.sh`
2. Place the font in the `fonts` folder
3. Run `./training.sh`

