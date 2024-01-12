---
layout: item
title: Audio
manifest_name: audio
permalink: audio
external_manifest_url: 

---

<center>
  <h2>
  Audio
  </h2>
</center>
<!-- Add an essay or interpretive material below this line,
using HTML or markdown.  Do not modify this file above this line -->
<head>
  <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-VE0VSZDWME"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-VE0VSZDWME');
</script>

<button onclick="myFunction()">Transcript</button>

<script>
        function myFunction() {
            var x = document.getElementById("myDIV");
            if (x.style.display === "none" || x.style.display === "") {
                x.style.display = "block";
            } else {
                x.style.display = "none";
            }
        }
</script>

<div id="myDIV" style="display: none; text-align: justify">
One of the most confusing, yet essential, aspects of AVAnnotate is the ingestion of audio material. Because the software doesn’t store the audio files which require access—due to the minimal computing framework explained in the prior section—artifacts must be hosted somewhere online that is accessible by a URL ending in “.mp3.” In short, AVAnnotate’s requirement of a IIIF manifest means that the manifest must “point” somewhere online to say that “the audio file is here.” This doesn’t work if it’s hosted on your private drive. This also doesn’t work if the audio file is inaccessible due to privacy concerns, which frequently is the case with libraries, archives, and museums which have playable audio but an incorrect URL. I’d like to spend time on this subject in this review as access to information is significantly impacted by where audio is coming from and how it is hosted online.
<br><br>
There are two sides to the access of information in audio files which concern AVAnnotate: First, there is the access to the audio file, but inaccessible information within the audio file. This is the simpler version of the two. By using IIIF, AVAnnotate allows for users which have access to an audio file or a URL ending with “.mp3” to create a manifest which links to the file. Again, if this is already hosted online somewhere, easy—just use the software to create a manifest. This can be done by creating a project and clicking “Create Item Manifest.” However, if one has access to only the audio file—say your own personal recording on your computer’s hard drive—a link must be created for this audio. This is where AVAnnotate suggests using the Internet Archive (or Box)—a database which allows users to host a variety of data, including audio. By hosting an audio file here, users can create their own link ending with “.mp3,” and then uploading this to AVAnnotate to create a manifest.
<br><br>
The issue that I find, here, is that the software relies heavily on the Internet Archive to host data in a way which is supported by AVAnnotate’s infrastructure. Without the Internet Archive—or similar services—AVAnnotate offers just an annotation software. This ignores the intervention into access that I have identified as the crux of this software’s potential. In this same vein, and to my second point, there is also the issue of inaccessibility to the audio file, but access to the information in the file. Opposite to what I’ve just explained, having audio digitized by a library but not being able to access the .mp3 file prevents the dissemination of information through AVAnnotate. If there is no .mp3 file, then a IIIF manifest can’t be created, and the Universal Viewer can’t ingest nor play the audio which has been annotated.
<br><br>
Say, for instance, a library has an audio file which has been digitized, is available (can be listened to) online, but the file can’t be downloaded or the mp3 can’t be accessed. This is frequently the case for LAMs that restrict the dissemination of material. Such an audio file can’t be integrated into AVAnnotate and this impedes the software’s ability to create a digital exhibit showing both the audio and annotations in one place. In this example, the library may be sustaining the file, but actually using that file and being able to find one bit of information in minutes to hours of audio can be nearly impossible. So, while AVAnnotate’s minimal computing framework offers the tools for successfully communicating information about audio files, there is a significant chance for hindrance due to ownership, privacy, and rights associated with certain files. As a user, navigating this complexity isn’t easy, and it makes the act of sustainability and access that much more difficult.
  <br><br>
</div>

<link rel="stylesheet" type="text/css" href="style.css">
</head>
