# Beta-per-eV
Visualization tool to observe how plasma parameters match from different instruments with overlapping energy channels.

This will take data from a RBSPICE and HOPE cdf data file, and compute the Beta/eV for each energy channel.
As we believe that HOPE flux data is off by a factor of 3, this is plotted along with the nominal data.
In the background, the Beta is calculated starting from the lowest energy level. For every subsequent energy level, the total Beta is integrated over the energies up to and including the one in question.
