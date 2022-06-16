<h1>Metadata-Extraction-Project</h1>

<h2>Description</h2>
Project consists of a look at some unix tools for gaining meta information from pdfs and images. This project is being conducted following Tryhack.me's Digital Forensics Introduction course. https://tryhackme.com/room/introdigitalforensics
<br />


<h2>Languages and Utilities Used</h2>

- <b>Terminal</b> 
- <b>Pdfinfo</b>
- <b>Exiftool</b>

<h2>Environments Used </h2>

- <b>Ubuntu</b> 

<h2>Walk-Through:</h2>



<p align="center">
Run ls for a visual of what you're working with: <br/>
<img src="https://i.imgur.com/zOS4a9E.png" height="80%" width="80%" alt="LS Info"/>
<br />
<br />
Run Pdfinfo:  <br/>
<img src="https://i.imgur.com/7gYLb6Y.png" height="80%" width="80%" alt="PdfInfo"/>
<br />
<br />
Running PdfInfo lets us gain some information on the origin of the pdf, now lets run exiftool to extract metadata from the Image as well <br/>
<br />
Run Exiftool <br/>
<img src="https://i.imgur.com/jhKEUqf.png" height="80%" width="80%" alt="LS Info"/>
<br />
<br />
<br />
Exiftool is able to extract a large amount of data from images, using grep can help you find specific data from the tool <br/>
Example using Grep:  <br/>
<img src="https://i.imgur.com/i3YhQv3.png" height="80%" width="80%" alt="PdfInfo"/>
<br />
<br />
 <h2>Summary</h2>
There is a lot of data to be extracted from pdfs and images. Using the grep command can help you sort through the data as long as you know the specific parameter you're searching for, keep in mind they are case sensitive. 
<br />
 
 
 
 
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
