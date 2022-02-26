## The main aim of this circuit is to take the attendance and display when requested

Abstract - This research work has application for attendance system of employer's and students in general. The system will facilitate institutions! organization to make attendance individual in time along with data information thumb impression will be taken as a signature for the system entry. Main design and challenge in this system is the design of database architecture and its business logic.
###### I. AIMS AND OBJECTIVE
The aim of this system is to implement in C#.net set of reliable techniques for fingerprint image enhancement and
minutiae extraction. The performance of these techniques will be evaluated on a fingerprint data set.
In combination with these development techniques, statistical experiments can then be performed on the fingerprint data set. The results from these experiments can be used to help us better understand what is involved in determining the statistical uniqueness of fingerprint minutiae.

The main aim that this system would test whether attendance by fingerprint is enough for identification. It is expected that the work in this system will reach the stage of being able to fully test hypothesis.
###### II. BACKGROUND/CONTEXT
Fingerprints are the oldest form of biometric identification. Modem fingerprint based identification is used in forensic science, and in biometric systems such as civilian identification devices. Despite the widespread use of
fingerprints, there is little statistical theory on the uniqueness of fingerprint minutiae. A fingerprint is formed from an impression on a surface of composite curve segments. A ridge is defined as a single curved segment, and a valley is the region between two adjacent ridges. The minutiae, which are the local discontinuities in the ridge flow pattern, provide the details of the ridge-valley structures, like ridge endings and bifurcations. There are 50 to 150 minutiae on a single fingerprint image. Features such as the type, direction, and location of minutiae
are taken into account when performing minutiae extraction. The work of F.Galton defined a set of Galton Features for fingerprint identification, which since then, has been refines and extended to include additional types of fingerprint features. However, most of these features are not used in automatic fingerprint identification systems. Instead the set of minutiae types are restricted into only two types, ridge endings and bifurcations, as other types of minutiae can be expressed in terms of these two features types. Ridge endings are the points where the ridge curves terminates, and bifurcations are where a ridge splits from a single path to two paths at a Y-junction.
###### Problem
There are some problems which face by fingerprint recognition or identification security. We can catch a cold by
touching a biometric system (fingerprint).
• Twins have identical biometric traits (identical fingerprints, irises ... ). This is the same clones.
• Stolen body parts can be reused.
• Biometric features can be reconstructed from the template
• Making a fake finger is easy.

###### ABOUT:
1) Finger print identification is based on the fact that no two persons will have the same finger print in this world. 

2) This is because of the peculiar genetic code of DNA in each person. 

3) Finger print module differentiates between two fingers based on the ridges and valleys on finger print. 

4) Inside the finger print module a DSP processor is present to implement and analyze the algorithm.

5) Main heart of the circuit is finger print module. 

6) This sends commands to the controller when ever finger print is matched. 

7) Microcontroller receives these commands from the finger print module and uses the internal EEPROM to store the attendance. 

8) Keypad is used to send the requests to the controller either enroll the new one or to save the attendance or to exit.


###### LCD DISPLAY displays the messages related to the commands received.