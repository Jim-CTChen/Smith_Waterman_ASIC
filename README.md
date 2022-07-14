# Smith_Waterman_ASIC

The aim of this project is to implement a Smith-Waterman accelerator with 256 PEs.

This is the final project of 109-1 NTUEE special project under Prof. Yi-Chang Lu's supervision.

## Hardware
Hardware design reference from [1].

![Hardware design](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/8a0a7483-1708-4931-9f38-512efc5d22ad/Untitled.png)

In order to handle longer sequence input, rather than simply making the PE array longer, I add an FIFO at the end of PE array, reducing the cost of the area of PE.

![fig 8. Illustration of PE array movement with line buffer attached.](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/d56e1934-f141-41cc-b962-943fcca4d7ec/ezgif.com-gif-maker.gif)
Illustration of PE array movement with line buffer attached.

## Reference
[1] Zhang, Peiheng, Guangming Tan, and Guang R. Gao. "Implementation of the Smith-Waterman algorithm on a reconfigurable supercomputing platform." Proceedings of the 1st international workshop on High-performance reconfigurable computing technology and applications: held in conjunction with SC07. 2007.
