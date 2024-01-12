---
layout: item
title: Infrastructure
manifest_name: infrastructure
permalink: infrastructure
external_manifest_url: 

---

<center>
  <h2>
  Infrastructure
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
AVAnnotate allows users to create digital exhibits of annotations for audio materials, which promotes access to the information associated with these files. According to Dr. Tanya Clement and Brumfield labs, the developers of the project and software, AVAnnotate is built using Jekyll and GitHub Pages. This “architecture,” which works with minimal computing principles, contributes to goals of sustainable access (Clement & Brumfield Labs, 2022). In other terms, the software intervenes in issues of artifact access by developing a software that creates static pages which can exist separately from AVAnnotate.
<br><br>
When a user creates a project with AVAnnotate, they log in with their GitHub account, which is required to begin using the software. The user’s GitHub account is vital to the success of sustainable access as the static site will be created via a GitHub repository and hosted via GitHub Pages. This process allows for the creation of a static site which can exist without AVAnnotate. Part of the benefit of using Jekyll and GitHub is the ability for these projects to out-live the software; exhibits of audio annotations exist on their own in individual user accounts. So, in short, even if AVAnnotate doesn’t exist one day, users will always be able to host their annotations—allowing for permanent access to the information of the audio files in question.
<br><br>
Another major component of access that the software foregrounds is the use of International Image Interoperability Framework (IIIF) manifests, an essential part to the creation of a digital exhibit. “IIIF is a set of open standards for delivering high-quality, attributed digital objects online at scale” (International Image Interoperability Framework) IIIF’s website states, meaning that these manifests contain information about any audio file and promote a standardized way of engaging with this information. Early on in the process of creating a digital exhibit, users will be asked to “import” or “create” a IIIF manifest, as this step allows for an exhibit’s audio to be ingested into Universal Viewer (which is a player for the audio). While understanding what a IIIF manifest is can be confusing, AVAnnotate makes it simple to create, use, and disseminate this information in a short link, promoting wide access to not only audio files but the annotations associated with them.
<br><br>
After working with AVAnnotate, the use of Jekyll, GitHub Pages, and IIIF are, to me, the most essential contributors to sustainable access that the software offers. Other softwares, tools, and applications frequently require a very complex and “heavy” infrastructure, which inhibits the sustainability of projects and exhibits created in these platforms. These types of projects include large storage systems that miss out on the benefits of sites such as GitHub, which allow for repositories and data to be retained by the user. AVAnnotate does not store any of this data or information; in fact, the software doesn’t allow for storage or hosting of audio files or an interface to create annotations, which I will explain in more detail in later sections. This sort of distributed core that the software offers maintains both the goals and functionality of AVAnnotate as a project devoted to sustainability and access.
  <br><br>
</div>

<link rel="stylesheet" type="text/css" href="style.css">
</head>
