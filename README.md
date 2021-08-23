# Chest X-ray

## Associated paper
Lee et al. "Fully Automatic Registration Methods for Chest X-ray Images." (minor review).
If you use this dataset in your research, please cite our publication.

#### Download
The clinical chest X-rays dataset collected from Wan Fang Hospital along with the manual annotations could be downloaded from the [zip](
https://drive.google.com/file/d/1cOfIw6VybRQQllXWtuv5ryxKEDAlK1jv/view?usp=sharing) file.

#### File structure
```
Chest X-ray/
|
|--Data/
│   ├── CR002/
│   │   ├── 4a-49
│   │   |   ├── bunwarpj
│   │   |   |   ├── source
│   │   |   |   |   ├── 4a-49-Bunwarpj-overlap.png
│   │   |   |   |   ├── 4a-49-Bunwarpj-Registered Source.png
│   │   |   |   |   ├── 4a-49-Bunwarpj-Source.psd
│   │   |   |   |   ├── 4a-49-Bunwarpj-target.png
│   │   |   |   |   ├── Registered Source Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   |   ├── target
│   │   |   |   |   ├── 4f-4e-BunwarpJ-overlap.png
│   │   |   |   |   ├── 4f-4e-BunwarpJ-registered target.png
│   │   |   |   |   ├── 4f-4e-BunwarpJ-target.png
│   │   |   |   |   ├── 4f-4e-BunwarpJ-target.psd
│   │   |   |   |   ├── Registered Target Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   ├── CWR
│   │   |   |   ├── source
│   │   |   |   |   ├── 4a-49-CWR-overlap.png
│   │   |   |   |   ├── 4a-49-CWR-Registered Source.png
│   │   |   |   |   ├── 4a-49-CWR-Source.psd
│   │   |   |   |   ├── 4a-49-CWR-target.png
│   │   |   |   |   ├── Registered Source Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   |   ├── target
│   │   |   |   |   ├── 4f-4e-CWR-overlap.png
│   │   |   |   |   ├── 4f-4e-CWR-registered target.png
│   │   |   |   |   ├── 4f-4e-CWR-target.png
│   │   |   |   |   ├── 4f-4e-CWR-target.psd
│   │   |   |   |   ├── Registered Target Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   ├── Median
│   │   |   |   ├── source
│   │   |   |   |   ├── 4a-49-Median-overlap.png
│   │   |   |   |   ├── 4a-49-Median-Registered Source.png
│   │   |   |   |   ├── 4a-49-Median-Source.psd
│   │   |   |   |   ├── 4a-49-Median-target.png
│   │   |   |   |   ├── Registered Source Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   |   ├── target
│   │   |   |   |   ├── 4f-4e-Median-overlap.png
│   │   |   |   |   ├── 4f-4e-Median-registered target.png
│   │   |   |   |   ├── 4f-4e-Median-target.png
│   │   |   |   |   ├── 4f-4e-Median-target.psd
│   │   |   |   |   ├── Registered Target Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   ├── 4b-4a
│   │   ├── 4c-4b
│   │   │     ⋮
│   │   └── 52-51     
│   ├── CR003/
│   │   ├── 5a-59
│   │   |   ├── bunwarpj
│   │   |   |   ├── source
│   │   |   |   |   ├── 5a-59-Bunwarpj-overlap.png
│   │   |   |   |   ├── 5a-59-Bunwarpj-Registered Source.png
│   │   |   |   |   ├── 5a-59-Bunwarpj-Source.psd
│   │   |   |   |   ├── 5a-59-Bunwarpj-target.png
│   │   |   |   |   ├── Registered Source Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   |   ├── target
│   │   |   |   |   ├── 5a-59-BunwarpJ-overlap.png
│   │   |   |   |   ├── 5a-59-BunwarpJ-registered target.png
│   │   |   |   |   ├── 5a-59-BunwarpJ-target.png
│   │   |   |   |   ├── 5a-59-BunwarpJ-target.psd
│   │   |   |   |   ├── Registered Target Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   ├── CWR
│   │   |   |   ├── source
│   │   |   |   |   ├── 5a-59-CWR-overlap.png
│   │   |   |   |   ├── 5a-59-CWR-Registered Source.png
│   │   |   |   |   ├── 5a-59-CWR-Source.psd
│   │   |   |   |   ├── 5a-59-CWR-target.png
│   │   |   |   |   ├── Registered Source Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   |   ├── target
│   │   |   |   |   ├── 5a-59-CWR-overlap.png
│   │   |   |   |   ├── 5a-59-CWR-registered target.png
│   │   |   |   |   ├── 5a-59-CWR-target.png
│   │   |   |   |   ├── 5a-59-CWR-target.psd
│   │   |   |   |   ├── Registered Target Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   ├── Median
│   │   |   |   ├── source
│   │   |   |   |   ├── 5a-59-Median-overlap.png
│   │   |   |   |   ├── 5a-59-Median-Registered Source.png
│   │   |   |   |   ├── 5a-59-Median-Source.psd
│   │   |   |   |   ├── 5a-59-Median-target.png
│   │   |   |   |   ├── Registered Source Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   |   |   ├── target
│   │   |   |   |   ├── 5a-59-Median-overlap.png
│   │   |   |   |   ├── 5a-59-Median-registered target.png
│   │   |   |   |   ├── 5a-59-Median-target.png
│   │   |   |   |   ├── 5a-59-Median-target.psd
│   │   |   |   |   ├── Registered Target Image.bmp
│   │   |   |   |   ├── Target Image.bmp
│   │   ├── 5b-5a
│   │   ├── 5c-5b
│   │   │     ⋮
│   │   |── 59-58   
```

## License
This dataset is released under a creative commons license, which allows for personal and research use only. For a commercial license please contact Prof Ching-Wei Wang. You can view a license summary here:  
http://creativecommons.org/licenses/by-nc/4.0/


## Contact
Prof. Ching-Wei Wang  
  
cweiwang@mail.ntust.edu.tw; cwwang1979@gmail.com  
  
National Taiwan University of Science and Technology
