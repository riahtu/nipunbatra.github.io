Title: Book Review: NumPy Beginner's Guide Second Edition
Date: 2013-06-11 17:15
Author: nipunbatra
Slug: book-review-numpy-beginners-guide-second-edition
Category: Blog

I got an opportunity to review [NumPy Beginner's Guide Second
Edition][]. Since i do most of my scientific analysis in Python, having
a stronger grip on NumPy is very essential. This is also very important
since almost all of Data analysis toolkits in Python leverage NumPy very
heavily. Here are the reviews:

#### Chapter 1  
Talks about installing and other stuff. For someone who has been using
Python and its scientific packages for some time now, most of the stuff
can be ommitted. However, for new comers it may be very helpful to see
how to use the executables, installing from source and different
techniques mentioned here. It pretty early introduces IPython which is
important.

<!--more-->

#### Chapter 2  
Starts with a gentle introduction to ndarray. The pop quiz about how
size of an array is stored is important as it tells the user how to deal
with it when performing operations based on size. Something new which i
learnt was that we can specify the dtype even with arange function. This
might be very handy when we know beforehand the maximum number expected.
The introduction to record data type is very helpful and again something
which i was not very confident about earlier.  
The section on indexing and slicing is very well explained and the
analogy of room makes it much more accessible even to new audience.  
The section on manipulating array shapes is good, but i feel it is not
highligting well enough if these methods are in place or not. This can
avoid a lot of commonly occuring confusions.  
Felt that the section on stacking could be improved by explaining more
about depth stacking and in general usage from real world examples could
make the understanding more concrete.  
A newcomer might be unhappy that he doesn't get to play with the code
snippets in IPython notebook. That would surely have been very helpful.

#### Chapter 3  
For some reason the code in the beginning of this #### Chapter is not run in
IPython. Something which may be worked upon in the future releases. For
instances, after saving the csv to disk, a simple !cat file.csv would
have shown that the write was successful. The section on CSV introduces
the stock price data, which is a very good dataset to illustrate the
concepts, but the source of the dataset and how to obtain it is not
mentioned. Might be useful to include the same in future release. Using
the unpack parameter in reading CSV is something which i hadn't used
before and is definitely a value addition. Earlier i used to read stuff
into bag arrays and then index them to get specific columns. When the
sorting example is provided msort is being used. Again it shows that how
many NumPy tricks are hidden. The example on stock returns though shows
a good use of NumPy's methods, but looks a little inaccessible to me
without plots.  
I liked the example on dealing with dates. One reason why i found it
very useful is that since i use Pandas a lot, which builds on top of
NumPy and has similar functions, so getting to understand how they
happen at NumPy level is useful. The function apply\_along\_axis is
another important function about which i did not know before and find it
to be very useful. The exmaple on using linalg is very helpful, although
an accompanying plot would have been more illustrative. The factorial
example to illustare cumprod() is about the best which can come to mind.

#### Chapter 4  
#### Chapter 4 begins with a good example of estimating correlation between
two companies' stock prices. Since i play with time series a lot, this
example looks helpful and even clears some statistical concepts. The
second example on polynomial fitting reminds of the days when i used to
fiddle around with Matlab GUI doing curve fitting. The same thing can be
done very easily using NumPy. The third example illustrates the use of
sign() which again i feel would be very useful for stuff like SVM and
Neural Nets. The section on Vectorizing is important and can be expanded
more to include more examples.

#### Chapter 5  
Golden Ratios example to illustrate the concept of matrices is actually
very good. Revisited Lissajous curves after a long time, alas the
example wasn't descriptive enough! It was an interesting bend to study
about square wave generation. Maybe something on lines of animating it
would have been much cooler! The methods for bit manipulation are
helpful in illustrating how functions are broadcasted.

#### Chapter 6  
Solving linear systems is easy in NumPy. I thought that i would have to
resort to some specialized libraries for the same. The definition of
eigen values is goofed up, maybe something which should be corrected in
next release. Now SVD techniques are useful, but without a motivating
example it may get difficult to grasp such concepts. Was a pleasant
surprise to read about FFT in the book. But felt that this topic could
either have been ommitted or described in more details. Distributions
and their handling was a warm welcome.

#### Chapter 7  
Saw the \>\>\> prompt. Maybe for sake of consistency, only IPython
should be used. A very good use case of search sorted is presented,
talking about inserting after seeing correct position. Extract function
was another new function which i saw and found very useful. Would have
been interesting if the author drew parallels with smart indexing and
where method. I decided to give the remaining #### Chapter a skip, since i
didn't see immediate benefits in my data analysis.

#### Chapter 8  
This #### Chapter seems to be very important especially while writing large
functions where manual inspection may not be possible. Also very
importantly the #### Chapter talks about how floating point arithmetic won't
be exact. The small example explaining TDD is very helpful and useful
for people willing to contribute to open source projects.

#### Chapter 9  
I feel the #### Chapter came in a little late. I would have liked a little
more description about the different components-axis, figure, canvas
etc. The scatter plot example is very interesting and helpful. Having
used fill\_between before i can only recommend that it be included in a
lot of books. Thankfully this books shows a clear descriptive example.
Surprisingly for me the annotations plot in the book does not show
annotations! Come 3D plotting.  
The image talking about the function of z in terms of x and y is
blurred and would best be replaced in forthcoming issues.

#### Chapter 10  
The #### Chapter starts on a good note, showing that in a practical world,
one may need to look beyond NumPy and need to see how to integrate the
outside world with it. Apart from learning NumPy, i also learnt a bit of
stats along the way. For instance the KS test was useful to learn about.
There are some examples from different domains. Just had a quick look.
Would get back when needed.

#### Chapter 11  
I am not fully convinced about using PyGame. Had used it a few years
back for Graphics course, but there are serious contenders out there.
The example from scikit-learn was interesting. Maybe pointing to SVM GUI
example from scikit-learn would have been a good choice as well.

  [NumPy Beginner's Guide Second Edition]: http://www.packtpub.com/numpy-mathematical-2e-beginners-guide/book