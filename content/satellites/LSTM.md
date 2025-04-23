Sources : 
- [SentiWiki - Instrument](https://sentiwiki.copernicus.eu/web/lstm#LSTM-LSTMInstrument)
- [SentiWiki](https://sentiwiki.copernicus.eu/web/lstm)

| **Channel** | **Wavelength** |
| :---------: | :------------: |
|    VNIR0    |    0.490 μm    |
|    VNIR1    |    0.665 μm    |
|    VNIR2    |    0.865 μm    |
|    VNIR3    |    0.945 μm    |
|    SWIR1    |    1.380 μm    |
|    SWIR2    |    1.610 μm    |
|    TIR1     |    8.600 μm    |
|    TIR2     |    8.900 μm    |
|    TIR3     |    9.200 μm    |
|    TIR4     |   10.900 μm    |
|    TIR5     |   12.000 μm    |


## From [SentiWiki](https://sentiwiki.copernicus.eu/web/lstm#LSTM-Geometryoftheproposedwhiskbroomconcept)

The L1b sampling in the Along Track (ALT) direction is determined by the instrument's angular sampling along the detector line, while the Across Track (ACT) sampling is governed by the scan's angular velocity combined with the detector's frame time. At the sub-satellite point (SSP), the native sampling distance (L1b) is smallest in both directions, increasing along the scan until it reaches its maximum at the swath edges. "Square pixels," defined as having equal angular sampling in both the ACT and ALT directions, occur at nadir. However, for other swath positions, the sampling distance is greater in the ACT direction compared to the ALT direction.

| **Band**  | **Pixel pitch** | **Nominal focal length** |
| :-------: | :-------------: | :----------------------: |
| VNIR-SWIR |      15 μm      |         265,2nm          |
|    TIR    |      25 μm      |          442nm           |
This leads to a nominal SSD of :

|             **Position**             | **Spacial Sampling Distance** |
| :----------------------------------: | :---------------------------: |
|               at Nadir               |            36.83 m            |
| at swath border in the ACT direction |            48.86 m            |
| at swath border in the ALT direction |            42.09 m            |
