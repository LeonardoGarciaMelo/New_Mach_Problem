The Mach-Zehnder Interferometer (MZI) is an optical device that uti-lizes beam splitters and mirrors to create interference between paths of lightor quantum particles.
Basically, the solution consists in creating a new Mach-Zehnder interferometer, using a matrix created by me, in a quantum circuit.
The solution has two functions. The first one is the beam_splitter, which represents the beam_splitter matrix.
The second one is the mz_interferometer, which represents the quantum circuit that a photon has to travel through the Interferometer. This function returns the probability of a phothon be detected by three meters, A,B and C, but it returns an array with lenght 2.
This occurs because the first object is the probability of A or C detect the photon, and the second object of the array, is the probability of B detects
