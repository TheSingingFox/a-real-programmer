# a-real-programmer
Real Programmers use cat: https://xkcd.com/378/

There are only executables here, because all of the programs have been written directly into gcc:

	cat | gcc -xc -
	
or

	cat | g++ -xc++ -
	
Then type your code, and if you're done, <CR> ^d.
It will compile directly, and your source code is lost forever.

Of course all those programs don't do very much, but they may get longer over time.
