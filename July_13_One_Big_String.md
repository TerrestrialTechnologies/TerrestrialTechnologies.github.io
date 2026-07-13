# July_13_One_Big_String

Last night I was working on my (very conditional) autocomplete functionality for the WAREZ WORKS project- 
And it all started with a question. why "\n"? so I went down a rabbit hole and discovered that "\n" 
actually just signifies a new line. it tells the computer to separate the previous thing from the next.
This led to what I can only describe as an uncomfortable realization. The computer itself doesn't understand
new lines. it's all one big continuous string. everything is one long and unbroken line at the deepest level. 
This anxiety led me to ask ChatGPT and confirm I wasn't just being poetic about computers and their "behaviors." 

  ChatGPT confirmed this- that the "\n" is just telling the computer that's where a line break happens. That is-
that would be where a computer understands an action must be performed. that action is a new line. In the context 
of my little project, it was being used to offer a condition, to tell the computer that the long txt file needed to
be separated per element. it would not naturally do this. ChatGPT went a step further, bringing the proverbial flying 
knee to my face that was the obvious- and informed me that if you go all the way down to the metal, it's just one long 
string of data-- 

  A packet doesn't know it's a packet. a router doesn't know what's being sent is a .pdf. Hell, past a certain point, it's 
just morse code- an electrical signal being switched on and off in rapid succession. Positive, Off, Negative, Off. And in 
the eternal words of Kurt Vonnegut-- "so it goes..." after slapping my own forehead over being reminded that binary exists, 
and after a night of fitful, fittingly stupid sleep- I woke up and drove to my internship. All was well for maybe 15 minutes.
My tired brain doing what a tired brain does- that is- not much. 

  I was listening to korean pop on the drive and musing about syllabic languages in my own head. Then my brain does what it 
always does, and thought entirely too much about the thing that had plagued me the night prior. I realized that a lot of things
we (perhaps on a global scale) separate as different objects are actually continuous systems with boundaries imposed on them 
later on. Think about it; A text file is a stream of characters. A language is one stream of historical changes, A network
packet is one stream of bytes. Even calculus concerns itself with understanding behavior within a continuous system, instead of
perhaps just excaminig discrete points (put a pin in the mention of calculus. It will come up again.) 

  I started thinking about languages and writing systems as well. Alphabets break language into smaller units than syllabaries, 
Those then break languages into smaller units than syllabaries, than entire words, than whole concepts...etc. In a weird way, 
Understanding often seeems to involve increasing resolution and examining finer details. zooming in, as it were. This is where 
the calculus comparison comes back. to find a prime- we have to decompose. decomposition is for mathematical reasons that I
have yet to fully internalize consistend with zooming in on a specific point. understanding the whole thing from a single point-
a single snapshot of the horse race rather than the whole thing. 

All of this spawned from a single line of JavaScript tucked inside of an html file: 

" data.split("\n") "

Sometimes the most interesting unifying lessons can come from a bug fix instead of a textbook or youtube tutorial. 
