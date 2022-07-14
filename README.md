# Smith_Waterman_ASIC

The aim of this project is to implement a Smith-Waterman accelerator with 256 PEs.

This is the final project of 109-1 NTUEE special project under Prof. Yi-Chang Lu's supervision.

## Hardware
Hardware design reference from [1].

![](https://i.imgur.com/73tj2i3.png)


In order to handle longer sequence input, rather than simply making the PE array longer, I add an FIFO at the end of PE array, reducing the area cost of adding more PEs

![](https://i.imgur.com/FZjoWSR.gif)

Illustration of PE array movement with line buffer attached.

## Reference
[1] Zhang, Peiheng, Guangming Tan, and Guang R. Gao. "Implementation of the Smith-Waterman algorithm on a reconfigurable supercomputing platform." Proceedings of the 1st international workshop on High-performance reconfigurable computing technology and applications: held in conjunction with SC07. 2007.
