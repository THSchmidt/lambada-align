![http://lambada-align.googlecode.com/files/lambada_logo.png](http://lambada-align.googlecode.com/files/lambada_logo.png)

# Membrane Protein Orientation and Alignment #

LAMBADA automates the adjustment of 3D membrane protein structures with lipid bilayers.

## Features ##
  * Automatic orientation of the protein according to its hydrophobic surface profile
  * Automatic alignment of the membrane
  * Output of the combined membrane protein system ready for protein embedding


## News ##

_2012-09-28_ The first release of LAMBADA is available for download.


## Quick start ##
  * Download and unpack the LAMBADA archive
  * Copy the folder to your lib directory (e.g. `cp -r lambada/ ~/lib`)
  * Make LAMBADA executable (e.g. `chmod 755 ~/lib/lambada/lambada`)
  * Set a soft link to the LAMBADA executable (e.g. `ln -s ~/lib/lambada/lambada ~/bin/lambada`)

You can run LAMBADA by typing
```bash
lambada -f1 protein.gro -f2 membrane.gro```

Get the program help by typing
```bash
lambada -h```


## Documentation ##

We provide **[installation instructions](Installation.md)** and a **[manual](Manual.md)** on this program's project page.

**[Example applications](http://code.google.com/p/inflategro2/wiki/ExampleApplications)** of LAMBADA in combination with the protein embedding procedure can be found on the project page of [InflateGRO2](http://code.google.com/p/inflategro2/).


## References ##
If you use LAMBADA for **publication**, please cite

> Schmidt, T. H. & Kandt, C. _LAMBADA & InflateGRO2: Efficient Membrane Alignment and Insertion of Membrane Proteins for Molecular Dynamics Simulations._ Biophysical Journal 102, 173a (2012). http://dx.doi.org/10.1016/j.bpj.2011.11.938


**Electronic documents** should include a direct link to the LAMBADA hosting page:

> http://code.google.com/p/lambada-align


For **posters** or nerds we provide a QR Code, referencing to this Google Project Page:

  * [QR Code 72dpi](http://code.google.com/p/lambada-align/downloads/detail?name=lambada_qr72dpi.png)
  * [QR Code 300dpi](http://code.google.com/p/lambada-align/downloads/detail?name=lambada_qr300dpi.png)


## Related projects ##

After using the LAMBADA protein orientation you can use our new version of the commonly used embedding routine InflateGRO2:

> http://code.google.com/p/inflategro2

The InflateGRO2 project page includes a **full tutorial** for the system setup of a set of membrane proteins with representative structural characteristics, using both **LAMBADA** & **InflateGRO2**.