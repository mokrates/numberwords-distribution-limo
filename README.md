# getting limo
I'm sorry, but I like to use my toy language. You can rewrite it in python, if you want to.
To execute it with limo, get it on github: [limo](https://github.com/mokrates/limo)

# plotting the german

	$ limo numberwords-distrib-deutsch.limo > gscatter.dat
	$ gnuplot
	plot 'gscatter.dat' with points pt 7

![Plotforgerman](german.png "plot for german")

# plotting the english

	$ limo numberwords-distrib-english.limo > escatter.dat
	$ gnuplot
	plot 'escatter.dat' with points pt 7

![Plotforenglish](english.png "plot for english")
