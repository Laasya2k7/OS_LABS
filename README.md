cp ~/Desktop/OS_Lab/Lab3_Submission/q1/* .
cd ~/Desktop
pwd
ls
git clone https://github.com/Laasya2k7/OS_LABS.git
cd ~/Desktop/OS_Lab
git status
find Lab3_Submission -type f
mkdir -p Final_Lab
cp xv6-public-clean Final_Lab/Lab3_Q1
cd Final_Lab/Lab3_Q1
cp ~/Desktop/OS_Lab/Lab3_Submission/q1/{proc.c,proc.h,Makefile,fcfstest.c} .
make clean
make
make qemu-nox
