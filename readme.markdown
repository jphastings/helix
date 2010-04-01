Helix
=====
I built a script to help create the poem I wrote called helix
you can find it at [helix.byJP.me](http://helix.byJP.me).

You can build your own similarly styled poem using this script - 
I'm releasing the artwork that is the poetry and this script that generates it under a
[Creative Commons licence](http://creativecommons.org/licenses/by-nc-sa/3.0/), this
means that you can reproduce my version or your own as much as you like under these conditions

 * You aren't making money from it
 * You reference the original work (at [helix.byJP.me](http://helix.byJP.me))
 * You share *your* work under this same licence

Of course, if you'd like to contravene any of these you only need to ask me — this licence is
just a catch-all!

I would also really appreciate it if you told me about your work!
[this.was.byjp.me](http://this.was.byjp.me) lists other people's work based on my own and I'd
love to put a link to your works on there.

Installation
------------

You will need a standard ruby installation -- that's it!

On Mac OS X and linux, you're probably ready to go, windows users may need to [download ruby](www.ruby-lang.org/en/downloads/)

Once ruby is up and running, you need to do some editing:

You need to create a `thoughts.txt` file, one 'thought' per line. My code only copes with 100 slots
at the moment, so I'd probably have about 25 if I were you.

The file `random.txt` needs to be filled with random words you like (one per line), I'd make about
30 or so.

At the top of `thoughts.rb` you can change `num_random = 4` to any integer, the greater the number
the more dense the non-thought slots will be. `tags` should be an array of unique integers, these
are the slots that will be filled with your thoughts, you need to have at least as many tags as you
do thoughts, elsewise you won't see your final thoughts in the piece. Finally, `slots` is the number
of slots that will be created. You can't have more than 99!

All done! Just open up a prompt and run the script:

    $ ruby thoughts.rb

You'll have all the files you need created for you :) Have fun!

To Do
-----

I need to do some tests with the new version of MooTools and make the script download MooTools from their
site, rather than keeping it in my script -- its probably against their licence!