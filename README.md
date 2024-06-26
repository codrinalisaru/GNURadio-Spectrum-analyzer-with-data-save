# GNURadio-Spectrum-analyzer-with-data-save

This application was part of my dissertation thesis and it uses the RTL-SDR device, a cheap, popular and versatile SDR device.

The application is basically a combination of the other 3 applications I created, also available here on Github. So, either you use them separately, or you use this application which is the sum of all three apps above mentioned.  

Application features:
- spectrum exploration in the frequency range of 100kHz - 6GHz, depending on the used device;
- type of receiver selection in the user interface: Spectrum analyzer with or without data recording, Mono/Stereo FM receiver with or without data recording, AM/NBFM receiver with or without data recording;
- device gain set from the interface;
- volume set, central frequency selection, frequency step selection, displayed bandwidth selection, squelch parameter set, all from the user interface;
- real time display of the spectrum, spectrogram and received signal in time domain;
- the option to save the signals in wav format, for each receiver type;
- the option to choose the sampling frequency and the number of bits per sample for saving the wav file.

What you need in order to use this application: RTL-SDR device, GNU Radio software installed. 
If you want to find out more information about the RTL-SDR device, you can take a look here: https://usermanual.wiki/Document/The20Hobbyists20Guide20To20RTLSDR2020Carl20Laufer.399886352/view

Full documentation of the project in Romanian:

https://electronicaplicata.wordpress.com/2023/12/03/software-defined-radio-sdr-pentru-incepatori-aplicatii-si-explicatii/
