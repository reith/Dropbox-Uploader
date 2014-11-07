This adds new command `pipe` to send data from stdin to Dropbox.  This would be
useful for example when you want fetch a file from web and store it to your
Dropbox but It is too big to fit on your HDD: wget -O - http://some.big/file |
./dropbox_upload.sh pipe file.mirrored

Or if you have some kind of data producer and size of data is not known in advance.

I've tested this on GNU.  Not much fast but maybe solve someone's problem.
