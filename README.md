# པར་གཞི་སྒྲིག་ཆས། Pecha Printer
Program to convert a pdf into a ready to print "Pecha", traditional Tibetan volumes.

### ཕབ་ལེན། Download Installer

* [སྒེའུ་ཁུང་རྟགས་ཅན། Windows](https://github.com/buda-base/pecha-printer/releases/download/v1.3/PechaPrinter_1.3.exe)

## ཚད་མཐོའི་འཇུག་སྤྲོད། Advanced Install
* ཀུ་ཤུ་རྟགས་ཅན་ཆེད། Mac & Linux:
    1. [ཕེ་ཐོན་མ་ལག་ཐོན་རིམ་ 3.7 ཕབ་ལེན་བྱས་ཏེ་འཇུག་སྤྲོད་བྱོས། Install Python 3.7](https://www.saintlad.com/install-python-3-on-mac/)
    2. [པར་གཞི་སྒྲིག་ཆས་ཀྱི་ཁུག་མ་ཕབ་ལེན་བྱོས། Download Pecha Printer](https://github.com/buda-base/pecha-printer/archive/master.zip)
    3. Open Terminal and run `python3 install.py`
    4. Open Terminal and run `python3 pechaprinter.pyw`

## Why use pecha-printer?
- printing one pecha page per paper sheet wastes a lot of paper
- grouping images 3 by 3 in photoshop is difficult and time consuming
![pecha-printer logic (19)](https://user-images.githubusercontent.com/17675331/133734932-a75fb6de-9a67-45a0-9d8b-4a9a8fcfc981.png)
- A requires a lot of reordering of pecha pages,
- B only requires to combine the 3 piles in order to get a pecha ready for reading!
![pecha-printer logic (17)](https://user-images.githubusercontent.com/17675331/133734679-a3e92478-6685-4aad-b6a3-9c5fec491f90.png)
![pecha-printer logic (18)](https://user-images.githubusercontent.com/17675331/133734712-4b24474e-96fb-42be-965d-8caad1dda1c0.png)


## Development Roadmap
### To do:
- [x] Windows installer
- [ ] Mac installer
- [x] redesign the UI
- [x] localization
- [ ] custom paper size
- [ ] option to binarise all images for unity
- [ ] combine multiple pdfs
- [x] bundle for distribution

### Wish list:
- split pdfs on outline and name files after section names

## License

The code is Copyright 2019 Buddhist Digital Resource Center, and is provided under [Apache License 2.0](LICENSE).
