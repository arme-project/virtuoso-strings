# ARME *Virtuoso Strings*

The *Virtuoso Strings* dataset contains scores, audio recordings, and onset annotations of a strig quartet performing the Haydn's string quartet Op. 74 No. 1 Finale. It is part of a larger collection of recordings captured through the [Augmented Reality Music Ensemble (ARME)](https://arme-project.co.uk/) project, with [audio recordings](./audio/) :violin:, and [onset annotations](./annotations/) :memo:.

## Links

:microscope: [Paper preprint](http://128.84.21.203/abs/2211.08848) [[pdf](http://128.84.21.203/pdf/2211.08848)]  
:computer: Supporting [website](https://arme-project.co.uk/demos/virtuoso-strings)  
:musical_score: Musical [scores](/docs/scores/)  
:musical_note: Audio [recordings](https://github.com/arme-project/virtuoso-strings/releases)  
:memo: Onset [annotations](/annotations/)  
:bar_chart: Annotation [experiments](https://github.com/arme-project/haydn-annotation-dataset)  

## Looking around
* [`audio`](/audio/): mono WAV sampled at 44.1 kHz 16-bit resolution
* [`annotations`](/annotations/): txt files with single column onset annotations
* [`docs`](/docs/scores/): pdf musical scores

## How to read filenames?

```JS
instrument_name:  VN1, VN2, VA, VC
                  - first violin, second violin, viola, violoncello
musician:         RC, JB, NR, PG
                  - Roger Coull, Philip Gallaway, Jonathan Barritt. Nicholas Roberts
ensemble_type:    Q, D, T, S 
                  - quartet, duet, trio, solo
composer:         JH, AM, LB, ED 
                  - Joseph Haydn, Amadeus Mozart, Ludwig van Beethoven, Ernő Dohnányi
leader:           VN1, VN2, VA, VC, VN0 
                  - leader or no leader
condition:        NR, DP, SP, WH
                  - normal, deadpan, speeds, whole piece
take_number:      1-12

example filename: VN1_RC_Q_JH_VN1_NR_12
```

## Roadmap and Contributing
In the future we plan to release more recordings and continue improving the existing onset annotations. Onset annotation is a lengthy and error-prone process, and as this is an ongoing research project, all contributions are most welcome.

Any questions please feel free to contact us or refer to the supporting publication. 

## Citation
If you use this dataset in your research, feel free to cite this paper:

```bibtex
@article{tomczak2022annotation,
  title={Annotation of Soft Onsets in String Ensemble Recordings}, 
  author={Tomczak, Maciej and Li, Min Susan and Bradbury, Adrian and Elliott, Mark and Stables, Ryan and Witek, Maria and Goodman, Tom and Abdlkarim, Diar and Di Luca, Massimiliano and Wing, Alan and Hockman, Jason},
  journal={arXiv preprint arXiv:2211.08848},
  year={2022}
}
```

## Acknowledgments
This project is kindly funded by Engineering and Physical Sciences Research Council (EPSRC) grant with reference [EP/V034987/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/V034987/1). 

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
