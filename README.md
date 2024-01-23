# ms_peaks
Mass Spectrum Primitives and Functions to Manipulate Raw Mass Spectrum Data Files


## ms_peaks.py

A python library to read and manipulate raw text or mzXML files generated by [at least Mahdi] Mass Spectrometers. Functionality to read raw text and mzXML files is provided by [pyomenms](https://pyopenms.readthedocs.io/en/latest/index.html). 

### Description of primary data type: Peaks

Peaks are a tuple of two numpy arrays, of which the first array contains values of mz and the
second the values of intensity. The data type is not strictly enforced as a class,
but could easily be implemented as such. (Types are loosely defined in Haskell Style)

- Type Peaks = ([mz], [intensity])

- Type mz = [Float]

- Type Intensity = [Int]

### Usage 
`ms_peaks.py` is reasonably well documented. Read it. Also take a look at `examples.py` 

Below are the functions defined within `ms_peaks.py`
```

```

## fmc.py
This library is specfic to for functions associated with C -> 4mC. It is a specifically used in the analysis of Mass Specturm Data in Study of C -> 4mC (in DNA oligo 5'-A-G-C-G-A-3')                                                                                     
