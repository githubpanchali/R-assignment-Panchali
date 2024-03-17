Hi Panchali!

I was able to successfully run your markdown file! One of my biggest critiques would be to clean up your output. In order to run it, I had to remove the chunk name "cars" from all your r code chunks. Also, all your chunks included "summary(cars)" which is irrelevant to your data.

Also, when you include code like str() to analyze your data, it makes your document HUGE! If you really want to include it, leave it as a comment. in addition, if you want, you can include file.size() to get the file sizes in bytes.

I love your plots, made me realize I did them wrong! You can change the text size of your x axis using something like theme(axis.text.x= element_text(size = 3)) in your plot code line. Also for your first plot it does not have an x axis label for some reason.

I also saw your file has a lot of warning text blocks, you can get rid of those by including "warning=FALSE" in your code block name after "r".

Thanks!
Rabsa
