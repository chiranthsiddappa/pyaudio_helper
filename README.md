# pyaudio-helper

### Dependencies for `pyaudio`

Across the three popular platforms, Windows, macOS, and Linux, `pyaudio`, is 
the underlying framework that `pyaudio_helper` relies upon. Getting `PyAudio` configured is  different for all three OS's. Conda and CondaForge have support for installing `pyaudio` 
on both Linux and Windows. Under Python 3.6 and below PyAudio will install when `pip` installing the scikit-dsp-comm package, as described below. For Python 3.7+ `PyAudio` **first** needs to be installed using `conda install pyaudio` to obtain binary (`whl`) files.

All the capability of the package is available less `PyAudio` and the RTL-SDR radio, without doing any special installations. See the [wiki pages](https://github.com/mwickert/SP-Comm-Tutorial-using-scikit-dsp-comm/wiki) for more information. Just keep in mind that now a Python 3.7+ install on windows must include the installation `PyAudio` as described above.
