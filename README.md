# lambada-align
Automatic membrane protein orientation and alignment

LAMBADA automates the adjustment of 3D membrane protein structures with lipid bilayers.

:: FEATURES ::
- Automatic orientation of the protein according to its hydrophobic surface profile
- Automatic alignment of the membrane
- Output of the combined membrane protein system ready for protein embedding 

:: NEWS ::
2012-09-28 The first release of LAMBADA is available for download.


:: INSTALLATION & QUICK START ::
1. Download the LAMBADA archive from the project download website.
2. Unpack the LAMBADA archive
   > tar -xvzf lambada.tar.gz
    (LAMBADA should work already now by typing perl lambada/lambada.)
3. Copy the folder to your lib directory
   > cp -r lambada/ ~/lib/
4. Make LAMBADA executable (e.g. chmod 755 ~/lib/lambada/lambada)
   > chmod 755 ~/lib/lambada/lambada
5. Set a soft link to the LAMBADA executable in your bin directory
   > ln -s ~/lib/lambada/lambada ~/bin/lambada

Run LAMBADA by typing:
> lambada -f1 protein.gro -f2 membrane.gro

Get the program help by typing:
> lambada -h


:: DOCUMENTATION ::
We provide installation instructions and a manual on this program's project page.

Example applications of LAMBADA in combination with the protein embedding procedure can be found on the project page of InflateGRO2.



:: REFERENCES ::
If you use LAMBADA for publication, please cite
Schmidt, T. H. & Kandt, C. LAMBADA & InflateGRO2: Efficient Membrane Alignment and Insertion of Membrane Proteins for Molecular Dynamics Simulations. Biophysical Journal 102, 173a (2012). http://dx.doi.org/10.1016/j.bpj.2011.11.938 

Electronic documents should include a direct link to the LAMBADA hosting page:
    https://github.com/THSchmidt/lambada-align

For geeks we provide a QR Code, referencing to this Google Project page:
    QR Code 72dpi
    QR Code 300dpi 


:: RELATED PROJECTS ::
After using the LAMBADA protein orientation you can use our new version of the commonly used embedding routine InflateGRO2:
    https://github.com/THSchmidt/inflategro2 

The InflateGRO2 project page includes a full tutorial for the system setup of a set of membrane proteins with representative structural characteristics, using both LAMBADA & InflateGRO2. 
