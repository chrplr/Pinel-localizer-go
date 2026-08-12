Implementation of the Pinel localizer in Go
-------------------------------------------

[HTML version](https://chrplr.github.io/Pinel-localizer-go) | [Github repo](https://github.com/chrplr/Pinel-localizer-go)

*Note: This has not been thouroughly tested, please report Issues on the github repo if you encounter any*

This is an implementation of the *Pinel functional localizer* stimulation program described in the following publication:

> Pinel, P., Thirion, B., Meriaux, S., Jobert, A., Serres, J., Le Bihan, D., Poline, J.-B., & Dehaene, S. (2007). Fast reproducible identification and large-scale databasing of individual functional cognitive networks. BMC Neurosci, 8, 91. https://doi.org/10.1186/1471-2202-8-91

This is a port to [gostim2](https://chrplr.github.io/gostim2/) of a Python version available at <https://github.com/chrplr/pinel_localizer>

![](stimulation.png)

## Prerequisites 

* Install [gostim2](https://chrplr.github.io/gostim2/) and m

## Usage

You can either:

* Execute one of the scripts `run*` from the command line, e.g.

   ```bash
   $ cd Pinel-localizer-French
   $ . run_instructions.sh
   $ . run1.sh
   $ . run2.sh
   ...
   ``` 


* or launch the GUI app `gostim2-gui` and select one of the `.tsv` files inside the subfolders and set the stimuli folder. This is how the interface should look like:

![](gui.png)

   You can then press the "Start button".`


# License & Authorship

Author: Christophe Pallier <christophe@pallier.org> (Web site <http://www.pallier.org>)

The stimuli were designed by Philippe Pinel at the [INSERM U562 "Cognitive Neuroimaging Unit"](http://www.unicog.org)

Two different licenses apply:

* **Code** (the `run*.sh` scripts, the `.tsv` protocol files and anything else
  driving the stimulation): [Apache License 2.0](https://www.apache.org/licenses/LICENSE-2.0).
  See [LICENSE](LICENSE) and [NOTICE](NOTICE).

* **Stimulus material** (the `.wav` audio files, the `.bmp` images and the
  accompanying stimulus spreadsheets), designed by Philippe Pinel at INSERM
  U562: [Creative Commons Attribution-ShareAlike 3.0 (CC BY-SA 3.0)](https://creativecommons.org/licenses/by-sa/3.0/).


[![](logo_unicog.png)](http://www.unicog.org)

