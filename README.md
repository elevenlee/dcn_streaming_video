dcn_streaming_video
===================

In this programming assignment you will implement a streaming video server and client that communicate control commands via the Real-Time Streaming Protocol (RTSP) and send data using the Real-Time Transfer Protocol (RTP). Your task is to implement the RTSP protocol in the client and implement the RTP packetization in the server.


1. The Streaming Video Client and Server were written under the Ubuntu Linux System (Version 11.10).

2. The Compiler version is GCC 4.6.1.

3. I have written a "makefile" document.
   So just type "make" command under current directory to compile source code. (Both Video Client and Video Server)
   Type "make clean" under current directory to remove object and execution files.

4. The format of running Streaming Video Server is as below:

   ./VideoServer <port number>

   The <port number> argument is necessary;

5. The format of running Streaming Video Client is as below:

   ./VideoClient <server name/ip address> <service/port number> <video file name>

   (1) The <server name/ip address> argument is necessary;
   (2) The <service/port number> argument is necessary;
   (3) The <video file name> argument is necessary;

6. Something about GTK Program
   Before compiling and running the Streaming Video Client, you must install GTK+ on the system.
   If you do not know how to install GTK+, please see http://www.gtk.org/
   Otherelse, if the program report "cannot show pixbuf ..." warning information, you should install "gtk2-engines-pixbuf" libarary.

That's all, and enjoy my project.

Thanks!
Shen Li
