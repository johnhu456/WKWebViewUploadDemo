# WKWebViewUploadDemo
This is a demo from [https://github.com/mbarnig/WKWebView](https://github.com/mbarnig/WKWebView). But add upload file function.

In page, clicked the 'choose file' button, then upload a file which name contains Chinese(or non-English characters)， you may found upload failed. Seems like any page use "\<input type='file'>" to upload file would not work right too.  
This may a WKWebView bug?   
Waiting for solution...

Here is a string of Chinese:  
"这是中文"  
you can use this line of Chinese to rename your file and do some tests.

StackOverFlow Quesion:  [https://stackoverflow.com/questions/44303980/wkwebview-upload-file-which-name-contains-chinese-character-results-in-garbled-c](https://stackoverflow.com/questions/44303980/wkwebview-upload-file-which-name-contains-chinese-character-results-in-garbled-c)