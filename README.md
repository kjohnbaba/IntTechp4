# InternetTechHW4
Making a Reliable Communication over an Unreliable Network using Python Sockets.
The sender.py program is a UDP sender that must implement the techniques of reliable
delivery that we discussed during lecture to upload a file to the receiver. Specifically, youwill
implement reliability based on stop and wait and cumulative-ACK-based selective repeat. The
receiver.py program is a UDP receiver that is attempting to download a file transmitted by
the sender over a lossy channel that may drop packets, ACKs, or both. We will test reliability by
checking that the receiver’s version of the file matches exactly with the sender’s version of the file
