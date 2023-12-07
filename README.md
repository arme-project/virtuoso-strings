# ARME *Virtuoso Strings*

The *Virtuoso Strings* dataset contains scores, onset annotations and audio recordings of a professional string quartet. It is part of a larger collection of recordings captured through the [Augmented Reality Music Ensemble (ARME)](https://arme-project.co.uk/) project, with [audio recordings](./audio/) :violin:, and [onset annotations](./annotations/) :memo:.

## Links

:microscope: [Paper preprint](https://ismir2023program.ismir.net/lbd_312.html) [[pdf](https://ismir2023program.ismir.net/lbd_312.html)]  
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

```ruby
instrument_name:  VN1, VN2, VA, VC
                  'First violin, second violin, viola, violoncello'
  ensemble_type:   Q, T, D, S
                  'Quartet, duet, trio, solo'
       composer:   JH, AM, LB, ED
                  'Joseph Haydn, Amadeus Mozart, Ludwig van Beethoven, Ernő Dohnányi'
         leader:   VN1, VN2, VA, VC, VN0, A, B
                  'Assigned leadership or no leadership, parts A/B in duets'
      condition:  NR, DP, SP
                  'Normal, deadpan, speed'
    take_number:  1-12

example_filename: VN1-Q-JH-VN1-NR-12
```

## How to read directory names?

```ruby
ensemble_type:  Q, T, D, S
                'Quartet, duet, trio, solo'
     composer:  JH, AM, LB, ED
                'Joseph Haydn, Amadeus Mozart, Ludwig van Beethoven, Ernő Dohnányi'
       leader:  VN1, VN2, VN0, XX_YY
                'First, second violinist, no leadership or XX in duets'
    condition:  NR, DP, SP
                'Normal, deadpan, speed'

  example_dir:  Q-JH-VN1-NR 
```

## Roadmap and Contributing
We plan to continue to improve the existing onset annotations. Annotation is a lengthy and error-prone process, and as this is an ongoing research project, all contributions are most welcome.

Any questions please feel free to contact us or refer to the supporting publication. 

## References
If you use this dataset in your research, feel free to cite these papers:


| **[1]** | **[Tomczak M., M.S. Li, M. Di Luca, Virtuoso Strings: A Dataset of String Ensemble Recordings and Onset Annotations for Timing Analysis, Extended Abstracts for the Late-Breaking Demo Sessions of the 24th International Society for Music Information Retrieval (ISMIR) Conference, 2023.](https://ismir2023program.ismir.net/lbd_312.html)**|
| :---- | :--- |

## Acknowledgments
This project is kindly funded by Engineering and Physical Sciences Research Council (EPSRC) grant with reference [EP/V034987/1](https://gow.epsrc.ukri.org/NGBOViewGrant.aspx?GrantRef=EP/V034987/1). 

## License
This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).
