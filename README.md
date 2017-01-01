# TopOpt
A 99 line topology optimization code written in Matlab

Efficient topology optimization in MATLAB using 88 lines of code
The Matlab codes presented in this page are intended for engineering education. Students and newcomers to the field of topology optimization can find the codes here and download them. The codes may be used in courses in structural optimization where students may be assigned to do extensions such as multiple load-cases, alternative mesh-independency schemes, passive areas, etc..



Details of the implementation are discussed in the paper Efficient topology optimization in MATLAB using 88 lines of code, E. Andreassen, A. Clausen, M. Schevenels, B. S. Lazarov and O. Sigmund, Struct Multidisc Optim, Volume 43, Issue 1, p.1 - 16, (2011) .

Modified versions can be obtained by selecting the links below:
Implementation utilizing PDE filter top82.m

Implementation utilizing conv2 Matlab function top71.m

Implementation utilizing Heaviside projection top110.m


Design obtained using: top110(300,100,0.5,3,9,3)
Save the program and start Matlab in the same directory. Run the program by writing for example:

'
top88(120,40,0.5,3.0,3.5,1)

in the Matlab prompt. top88 should be replaced with the corresponding name for the modified versions.
