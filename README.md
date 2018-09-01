# SJTU_UMJI_VE373_Design_of_Microprocessor_Based_Systems_Final_proj

/*************************************
Copyright reserved by Zekun Du, Yipai Du and Tao Liang

/*************************************
Objectives

Nowadays, wearable devices are more and more popular. This brings a lot of joy and
entertainment to peoples lives. The recent advancements in sensors enable us to acquire
biomedical signals from human bodies and do analysis based on them, thus help to
monitor the physical status of one person and trace ones physical behavior. Motivated by
this new trend, we are going to take advantage of the EMG signal processing technologies
and implement a joyful musical instrument based on PIC32 MCU.
Our project is called EMG based PIC32 musical instrument. It acquires muscle status
with three EMG sensors. The analog signal is sent to the MCU and to the processing,
including AD conversion, filtering and processing, to judge whether the muscle is at
tension or not. With different combinations of the muscles status, we can identify which
music note the user wants to play. The MCU then send the corresponding activate signal
to the loudspeaker. Meanwhile, there are LED lights available to be turned on and off
to add more fun to the music
