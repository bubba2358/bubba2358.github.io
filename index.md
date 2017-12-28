## 1) Ready Go
##### Synopsis + some first consideration about Python
I wanted to start programming again after a long period of time so, based on what a couple of friends told me, i thought **Python** could be my language of choice. After a couple of weeks of fiddling around i was able to grasp the basics despite the fact that Python in 2017 co-exists in *two versions* (2 and 3) that differ in some aspects and sintaxes and this can be quite confusing especially when you try to learn from old examples. Anyway, the first thing i noticed looking at some documentation is that Python as a scripting language, is not particularly 'fresh'. It reminds me of *Perl* (my first love) and this can infact sound quite old-fashioned. But as you dig deeper you discover the infinite galaxy of **packages** (python libraries) that make the real difference. There are literally thousands of them available for doin pretty much anything. Also the community is huge and there's a lot of documentation around. 
Then i want to place a big disclaimer here so to be clear for ever: **i'm not** a professional coder neither a mathmatician so everything you find here is **not** meant to be a tutorial or exhaustive or just *right*. This is a diary of a guy learning Python, researching and cataloguing stuff that maybe in the future would be useful to someone.
That said, let's move on some more interesting stuff. So about the Python (two) versions. Python 2.x comes preinstalled on OSX but i decided to embrace the new and install the new version 3.6 something. This is strongly suggested in mostly every article i've read so why not.
> ##### How to install on OSX  https://pypi.python.org/pypi
> ##### Python Official https://pypi.python.org/pypi
> ##### Python Online Book Beginner https://pypi.python.org/pypi
> ##### Python Online Book Med https://pypi.python.org/pypi

## 2) The scripting Language
I'm not gonna talk much about the learning process. Basically the core of the sintax is the same as most languages except for the **indentation** thing that was quite peculiar to me. In Python you declare 'blocks' simply with a ':' and mandatory indentation:

```python
if isAwesome:
  if isHuge:
    return True
```
Other things to keep in mind:
1. Everything is an **object**
2. List are *arrays* but more flexible (can contain different type of stuff as for point n1)
3. Tuples are non mutable lists
4. List comprehension seems very powerful. More on this later


## 3) Spotify
##### Gotta love the API
Month ago, way before i started this, i was browsing the Spotify website and i casually saw that they released a API for their database. This came back to me yesterday as i was looking at some Python packages. Of course there was one for Spotify. It is called **Spotipy** and basically does the job of translating between Python and the Spotify web server who speaks plain http. 


