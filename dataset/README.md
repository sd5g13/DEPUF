This directory includes all source data produced by simulating differential emulatable PUF (DEPUF) in SPICE. Each DEPUF is constructed using a 65-nm CMOS technology node. Feel free to use these data to construct machine learning models and to perform machine learning attacks to predict the challenge/response behavior.

# Filename definition:
CRPx_y+z.csv indicates the width, the number of booster stages and the number of represser stages as x, y and z, respectively.

File with "crc" indicates the source data produced by DEPUF cascaded with a cyclic redundancy check (CRC) code as a hash function.

# Source data format:
I: challenge(input) bit

O: response(output) bit

Value of challenge/response bit is represented by binary, while "?" indicates uncertain state, which can be either 0 or 1 randomly deteremind by the environment.
