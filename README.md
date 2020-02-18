# CTF Title

## Challange: 1

In this challange first i performed Nmap on given ip address for checking how many ports are opened and which services were running on port.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/1.png)

Only two ports are open and services running on that which was http and ssh after that I opened ip address in browser and it showed wordpress directory but it was not accessible.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/2.png)

I ran wpscan on the host and It showed host was not running on WordPress.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/3.png)

Then after i ran dirb on host for check any of files or directory publically accessible or not.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/4.png)

After that i got a directory which contain folders. here you can see. 

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/5.png), ![](https://github.com/pritessh/NS-CTF-2/blob/master/images/6.png)

In this folder too many files and one file which was contain flag that was FLAG_Use_Me_Wisely.txt

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/7.png)

I opened file and got first flag with hint.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/8.png)


## Challange: 2

It was a stegenogaphy challange so first i downloaded an image.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/9.png)

Image was showed like that.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/10.png)

I used [Steganographic Decoder](https://futureboy.us/stegano/decinput.html) to get the hidden information from image after that i uploaded image & entered flag as a password according to hint.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/11.png)

And i got second flag.

![](https://github.com/pritessh/NS-CTF-2/blob/master/images/12.png)
