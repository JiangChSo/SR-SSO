# SR-SSO

This repository contains a reference implementation of SR-SSO: Password-Hardening Threshold Single-Sign-On for Mobile Users against Subverted Implementation.

WARNING: This is an academic prototype, and should not be used in applications without code review.

## How to run
### Dependencies
- Crypto++ 8.6.0
- PBC 0.5.14
- NTL 11.5.1
### Running the repo
Clone this repo. Make sure `g++` and `cmake` have been installed. (Linux) \
Build and run the experiment locally.
```
cd Build
cmake ..
make
./build < ../Param/a.param
```
          
## Here is the implementation of SR-PTSSO.              
If you attempt to run the code, please make sure that pbc and openssl are installed. I would suggest to start with main.c, since it will check whether necessary dependencies exist. The environment can be configured based on the runtime prompts.          
The implementation of SR-PTSSO mainly consists of main2.c and main3.c, where main2.c represents the registration phase in the our scheme, and main3.c shows the login phase. If you have not run this program before, please try to run main2.c at first.           
