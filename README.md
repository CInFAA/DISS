# DISS
Digitized Ionogram Scaling Software

The Digitized Ionogram Scaling Software is a MATLAB script that allows the reduction of ionograms in photographic format. Based mainly in DIGION (Titheridge,1998) and taking elements from other scaling softwares, it was thought as a flexible method to extract ionosonde parameters from different kinds of ionosonde, even analogic ones.

In general, it's concept is to have a pixel-data relationship that allows the program to capture critical frequencies and virtual height values whenever the scaler needs it. With cursors and message boxes (and traces in DISS >= 1.2), each ionosonde parameter can be scaled using the scaling rules recommended by the U.R.S.I. Handbook of Ionogram Interpretation and Reduction (Piggot & Rawer,1972). 


[ Features: ]

v. 1.0
-------

- It works almost exactly as DIGION, improving the data output format and including new parameters (foF1 and h'F2)
- Only works with DIGION screenshots of the ionograms.

v. 1.2
-------

- It has similar functionality of v. 1.0, but to ionogram photographs captured by a Raspberry based method used on the Total Solar Eclipse campaign on July 2019.
- New parameters of E sporadic layer were include (h'Es, Type Es, fbEs).
- With a trace, the scaler can select frequencies and their respectives virtual heights in order to use a POLAN executable, allowing the inversion of the ionogram and obtaining electron density profiles and values of hmF2.

v. 2.0
-------

- A more definitive version of the script.
- New parameters of each region (foE2,h'E2,foF3, etc) [F3 parameters aren't fully included yet].
- DIGION data, Raspberry based method (IPS-42), LISN OX ionograms (VIPIR) and analogic ionograms (C series, Old IPS-42, etc) are scalable.
- A couple changes in the GUI and trace method.

