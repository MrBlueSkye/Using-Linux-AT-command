# Using-Linux-AT-command

INSTALL "AT"

apt-get install at
OR
yum install at

USE "AT"

1) Use directly:

#at now + 1 minute
> echo "Hello world"

2) Pipe to "at"

#echo 'echo "Hello world" | at now + 1 minute

VIEW "AT" JOBS

#atq
4       Tue Feb  6 11:58:00 2018 a user1
#


#at -c 4
...
...
...
echo "Hello world"


CANCEL "AT" JOBS

#atrm 4
#atq
#
#


"AT" TIME FORMATS

1) now + x minutes/hours/days/weeks/months/years
2) x AM/PM
3) x AM/PM tomorrow/next week/monday
4) noon/midnight
5) 4:00 PM feb 6
6) 4 PM 02/06/2018


