# YouTDL_python
Here is a YouTube downloader in Python3 using the PyTube3 library. The older pytube library has been deprecated so we need to use the pytube3 library which only works with Python3 but not with Python2.

Importing and Installing the Libraries
-In windows command line, type this commnand to download pytube3 library

`pip install pytube3`

So, we start our program with the following command:

`from pytube import YouTube`

Accepting Input from User
Our next step would be to ask the user to provide us with the link of the youtube video which we need to download. User will then provide us with the link of the video he intends to download.

`link = input(“Enter the link: “)`

`yt = YouTube(link)`


So, we have accepted input from the user and passed on the link to our YouTube class. 
It will help us reveal all the information about the video and also will let us download it in our machine.

Isn't this FUN!!

Now, we have the link, we have passed it into the YouTube class. Now, we can play with the link and reveal all sorts of information about the video like its title, number of views, ratings, description, length of the video and various other things.

`#Title of video`
`print(“Title: “,yt.title)`
`#Number of views of video`
`print(“Number of views: “,yt.views)`
`#Length of the video`
`print(“Length of video: “,yt.length,”seconds”)`
`#Description of video`
`print("Description: ",yt.description)`
`#Rating`
`print("Ratings: ",yt.rating)`

Now, when we will run this above code, we will see various details about the youtube video whose link we have provided as input to our program. Also, there are numourous other functions present in the official documentation of pytube3.


We have used the link for the official trailer of "Spider-Man NO WAY HOME" here. You can use any link as per your choice.

