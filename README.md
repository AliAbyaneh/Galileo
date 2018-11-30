# Galileo
Galileo GNSS
Galileo GNSS (Global Navigation satellite system) is European Union navigation system.
In fact, in addition to widely used GPS (US GNSS),
other advanced countries have their own GNSS, for instance, Glonnas is Russia GNSS and BeiDou was created by China.
The purpose of this project is design and implementaion of Galileo E1-B Reciever in HDL-Coder. To do so, I designed a software which simulates
the Galileo I/NAV signal. This simulator generates Galileo messages with the help of RINEX files. Signal simulator was tested and verified with 
GNSS-SDR software, and I reached to about 2 meter accuracy. The reciever consist of three parts, that is, acquisition, track, and navigation. 
Acquisition and track parts are designed completely, the result is verified with the signal simulator, and although I am far behind the schedule,
I am planning to complete the third part
before April. Afterward, I will release the final version of the reciever in this page. 
