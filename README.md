# getting limo
I'm sorry, but I like to use my toy language. You can rewrite it in python, if you want to.
To execute it with limo, get it on github: [limo](https://github.com/mokrates/limo)

# wtf?

People were wrong on the [facebook](https://www.facebook.com/groups/journalofscientificshitposting/posts/3562273530653324?comment_id=3562857307261613&reply_comment_id=3565074887039855), so duty called.

![dutycalls](https://imgs.xkcd.com/comics/duty_calls_2x.png "Duty calls")

# plotting the german

	$ limo numberwords-distrib-deutsch.limo > gscatter.dat
	$ gnuplot
	set ylabel "alphabetical position"
	plot 'gscatter.dat' with points pt 7

![Plotforgerman](german.png "plot for german")

# plotting the english

	$ limo numberwords-distrib-english.limo > escatter.dat
	$ gnuplot
	set ylabel "alphabetical position"
	plot 'escatter.dat' with points pt 7

![Plotforenglish](english.png "plot for english")
