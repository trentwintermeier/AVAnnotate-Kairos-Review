---
layout: default
title: Transcript
permalink: transcript
---

<center>
  <h2>
  Transcript
  </h2>
</center>

<head>
  <!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-VE0VSZDWME"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-VE0VSZDWME');
</script>

<link rel="stylesheet" type="text/css" href="style.css">
</head>


  
## Introduction

<div style="text-align: justify">
   AVAnnotate is a digital tool created by Dr. Tanya Clement and Brumfield Labs which allows users to create exhibits of annotated audio artifacts. In this software review, I utilize the affordances of AVAnnotate, along with the webtext-format of Kairos, to think about the rhetorical and pedagogical benefits that AVAnnotate provides to scholars and instructors interested in the intersection of digital technology and audio material. I draw on my personal experience of being a Graduate Research Assistant for AVAnnotate to do this work. However, to not separate my affiliation with the tool and project from this review, I use an audio recording review and annotations to develop my perspective on the potential for the software.
<br><br>
The format of this review, then, includes six sections that are organized according to different aspects of AVAnnotate. Each section includes a portion of the review that I’ve recorded and uploaded to the Internet Archive and created a IIIF manifest for with AVAnnotate. The six sections are: <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/infrastructure">infrastructure</a>, <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/audio">audio</a>, <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/annotation">annotation</a>, <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/context">context</a>, <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/collaboration">collaboration</a>, and <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/application">application</a>. Following these sections, I also include a short <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/conclusion">concluding note</a> and a <a href="https://trentwintermeier.github.io/AVAnnotate-Kairos-Review/transcript">transcript</a> of the audio files associated with each section. In the annotations of the audio in each section, I comment and expand on (as necessary) how the information in the review relates to my experience as a GRA. For instance, if in the audio recording I say that “I believe AVAnnotate is a tool that allows for sustainable collaboration on audio artifacts,” then an annotation may state that “I helped with the production of a collaborative digital edition, and this informs my perspective.” Each section of this webtext is designed to support an ethical and accountable review.
<br><br>
The above format also serves to illustrate one of the major interventions of AVAnnotate: the software provides a space for students and researchers to practice collaborative listening as a rhetorical response to the concerns of audio artifact accessibility. In allowing users to annotate audio and create digital exhibits, AVAnnotate teaches users, as a collective, to actively listen to and use sound to develop access to knowing and information. I find in this review that the software’s infrastructure, collaborative components, annotation, audio file hosting, and context curation is essential to this major intervention. 
<br><br>
To navigate this webtext, please click on the hyperlinked pages on the left or in the second paragraph above. Each of these pages include a transcript, playable audio, and time-stamped annotations with a layer column. Feel free to work across and through each section by either: reading the transcript; listening to the audio; filtering through the annotations; or by using the layer as a categorical indicator. 
</div>
<br>

## Infrastructure

<div style="text-align: justify">
AVAnnotate allows users to create digital exhibits of annotations for audio materials, which promotes access to the information associated with these files. According to Dr. Tanya Clement and Brumfield labs, the developers of the project and software, AVAnnotate is built using Jekyll and GitHub Pages. This “architecture,” which works with minimal computing principles, contributes to goals of sustainable access (Clement & Brumfield Labs, 2022). In other terms, the software intervenes in issues of artifact access by developing a software that creates static pages which can exist separately from AVAnnotate. 
<br>
  <br>
When a user creates a project with AVAnnotate, they log in with their GitHub account, which is required to begin using the software. The user’s GitHub account is vital to the success of sustainable access as the static site will be created via a GitHub repository and hosted via GitHub Pages. This process allows for the creation of a static site which can exist without AVAnnotate. Part of the benefit of using Jekyll and GitHub is the ability for these projects to out-live the software; exhibits of audio annotations exist on their own in individual user accounts. So, in short, even if AVAnnotate doesn’t exist one day, users will always be able to host their annotations—allowing for permanent access to the information of the audio files in question.
<br>
  <br>
Another major component of access that the software foregrounds is the use of International Image Interoperability Framework (IIIF) manifests, an essential part to the creation of a digital exhibit. “IIIF is a set of open standards for delivering high-quality, attributed digital objects online at scale” (International Image Interoperability Framework) IIIF’s website states, meaning that these manifests contain information about any audio file and promote a standardized way of engaging with this information. Early on in the process of creating a digital exhibit, users will be asked to “import” or “create” a IIIF manifest, as this step allows for an exhibit’s audio to be ingested into Universal Viewer (which is a player for the audio). While understanding what a IIIF manifest is can be confusing, AVAnnotate makes it simple to create, use, and disseminate this information in a short link, promoting wide access to not only audio files but the annotations associated with them.
<br>
  <br>
After working with AVAnnotate, the use of Jekyll, GitHub Pages, and IIIF are, to me, the most essential contributors to sustainable access that the software offers. Other softwares, tools, and applications frequently require a very complex and “heavy” infrastructure, which inhibits the sustainability of projects and exhibits created in these platforms. These types of projects include large storage systems that miss out on the benefits of sites such as GitHub, which allow for repositories and data to be retained by the user. AVAnnotate does not store any of this data or information; in fact, the software doesn’t allow for storage or hosting of audio files or an interface to create annotations, which I will explain in more detail in later sections. This sort of distributed core that the software offers maintains both the goals and functionality of AVAnnotate as a project devoted to sustainability and access.
</div>
<br>

## Audio 

<div style="text-align: justify">
One of the most confusing, yet essential, aspects of AVAnnotate is the ingestion of audio material. Because the software doesn’t store the audio files which require access—due to the minimal computing framework explained in the prior section—artifacts must be hosted somewhere online that is accessible by a URL ending in “.mp3.” In short, AVAnnotate’s requirement of a IIIF manifest means that the manifest must “point” somewhere online to say that “the audio file is here.” This doesn’t work if it’s hosted on your private drive. This also doesn’t work if the audio file is inaccessible due to privacy concerns, which frequently is the case with libraries, archives, and museums which have playable audio but an incorrect URL. I’d like to spend time on this subject in this review as access to information is significantly impacted by where audio is coming from and how it is hosted online.
<br>
  <br>
There are two sides to the access of information in audio files which concern AVAnnotate: First, there is the access to the audio file, but inaccessible information within the audio file. This is the simpler version of the two. By using IIIF, AVAnnotate allows for users which have access to an audio file or a URL ending with “.mp3” to create a manifest which links to the file. Again, if this is already hosted online somewhere, easy—just use the software to create a manifest. This can be done by creating a project and clicking “Create Item Manifest.” However, if one has access to only the audio file—say your own personal recording on your computer’s hard drive—a link must be created for this audio. This is where AVAnnotate suggests using the Internet Archive (or Box)—a database which allows users to host a variety of data, including audio. By hosting an audio file here, users can create their own link ending with “.mp3,” and then uploading this to AVAnnotate to create a manifest.
<br>
  <br>
The issue that I find, here, is that the software relies heavily on the Internet Archive to host data in a way which is supported by AVAnnotate’s infrastructure. Without the Internet Archive—or similar services—AVAnnotate offers just an annotation software. This ignores the intervention into access that I have identified as the crux of this software’s potential. In this same vein, and to my second point, there is also the issue of inaccessibility to the audio file, but access to the information in the file. Opposite to what I’ve just explained, having audio digitized by a library but not being able to access the .mp3 file prevents the dissemination of information through AVAnnotate. If there is no .mp3 file, then a IIIF manifest can’t be created, and the Universal Viewer can’t ingest nor play the audio which has been annotated. 
<br>
  <br>
Say, for instance, a library has an audio file which has been digitized, is available (can be listened to) online, but the file can’t be downloaded or the mp3 can’t be accessed. This is frequently the case for LAMs that restrict the dissemination of material. Such an audio file can’t be integrated into AVAnnotate and this impedes the software’s ability to create a digital exhibit showing both the audio and annotations in one place. In this example, the library may be sustaining the file, but actually using that file and being able to find one bit of information in minutes to hours of audio can be nearly impossible. So, while AVAnnotate’s minimal computing framework offers the tools for successfully communicating information about audio files, there is a significant chance for hindrance due to ownership, privacy, and rights associated with certain files. As a user, navigating this complexity isn’t easy, and it makes the act of sustainability and access that much more difficult. 
</div>
<br>

## Annotation

<div style="text-align: justify">
After finding usable audio and creating a manifest, annotating such audio is the next step. I’ve found this step to be really simple and thought provoking as it offers the first part of a unique practice of listening which the software offers. The only requirements for annotating with AVAnnotate is access to and minimal knowledge of Excel spreadsheets or Google Sheets. Since AVAnnotate doesn’t offer a way to annotate within the software, annotation happens with other tools. This is similar to how GitHub repositories, Jekyll, and IIIF are integrated—Clement and Brumfield Labs referred to this as “glue code—code that sticks a bunch of things together to make something useful” (2022). Thus, instead of building in annotation as part of the software, AVAnnotate “out sources,” in a sense, this functionality. It’s pretty simple, and it’s much better than learning or downloading another spreadsheet software, as I already own and am familiar with both Excel and Google Sheets.
<br>
  <br>
The spreadsheet is organized in five columns, with only three being mandatory.  The first vertical column is the first time stamp, the first time in the audio where the annotation begins. That goes in column A in the format of hh:mm:ss. And the next column, column B, includes the time where that annotation stops, in the same hh:mm:ss format. If, for example, I wanted to annotate part of an audio recording of someone who speaks from minute 1 to minute 2, I would put in column A “00:01:00” and column B “00:02:00.” Or, if I wanted to make a “point” annotation, I could put just the beginning of that speaker at “00:01:00” in column A and “00:01:00” in column B. This practice of making timestamps is really helpful for certain audio as it creates a different process and purpose to listening. In just the time stamping, I’ve found that I’m more focused on what and where a sound is, and focusing less on what that sound means. The time stamping required by AVAnnotate asks users to locate, but not define, certain moments in audio recordings. Such an act creates a conceptual break that is not often experienced in common practices of listening. 
<br>
  <br>
The next column, C, is designed for the annotation of the prior time stamps. This section is where I believe AVAnnotates offers the most valuable flexibility and engagement with access to information. This annotation can be almost anything. Column C can be a transcription, observation, image (using Markdown), symbols, or general thoughts—really, users can write anything in this section. I understand this to be extremely beneficial and important for how access is communicated in digital spaces. Indeed, transcription is helpful for quickly searching an audio file, assisting users with auditory disabilities, creating metadata, and more. However, having the opportunity to include ideas, thoughts, visuals, and links according to certain portions of audio is a different practice of making meaning for sustainable access to information. In my personal experience of annotation, I’ve found two things: First, AVAnnotate becomes a unique tool for knowledge dissemination when the possibilities of digital annotation are exercised to their full potential. Being able to communicate with images and external data creates new ways to experience information according to goals of access. In other words, communicating for sustainable access through digital annotation develops new and different ways of knowing audio. And second, to this same point, the act of listening for the use of sound is a unique experience offered by AVAnnotate. The software teaches users to engage with sound differently by emphasizing what sound can do for access, and how we, as annotators, participate in what this sound means. 
<br>
  <br>
Further, the last two columns, D and E, are for “Layers” and “Index,” respectively. The former is a form of categorization of the annotation is column C. The “Index” column is, simply, for an index which can be added to the project. I’ve found these both to be helpful additions to the software, but only if the user knows what their annotations are doing/ what they are for. In other words, having all of these columns requires up-front conceptual work by the user in that they need to decide the purpose of their project’s annotations. Even if the sole purpose of an AVAnnotate exhibit is to promote sustainable access to an audio artifact, each annotation requires decisions about what is highlighted and what isn’t. Is access to information about context important to this audio? A transcript of one or multiple speakers? The background noises or quality of the audio? Having layers and an index requires users to acknowledge how they are making meaning with the software—which is beneficial but difficult work. 
</div>
<br>

## Context

<div style="text-align: justify">
The “difficult work” that I have just described in terms of organizing columns and annotations is supported by the separate pages that teach users the importance of publishing digital annotations. The purpose of this “Create Page” function is to offer space for contextual information, such as an essay and images. In sum, this function supports further engagement with any artifact as a knowledge and meaning making practice. I really enjoy the integration in these pages in AVAnnotate because it asks users to purposefully situate their goal of working with sound and audio. These pages teach users to ask “why these annotations” and “why this audio” in creative and unique ways. This is especially helpful for students working with audio and sound as it exceeds mere listening and then annotating that experience; these pages require deeper engagement with the intersection of listening and annotating, and what this means in the larger context of the project. Creating contextual pages is more than supplementary, in this sense—it prompts users to think, consider, and reflect in a meaningful way.
<br>
  <br>
When users create and title a page, it gets published in their GitHub repository with the other published parts of the project, like the annotations and audio items which have been uploaded. Due to this, the pages must be written in GitHub, which means using Markdown. This requirement can be a learning curve for some users, and it also can hinder the productive benefits of the tool as a resource for teaching. Not all users may come to use AVAnnotate with coding experience or knowledge of Markdown. It’s not the most difficult language, but it’s a shift from using Word or Google Docs to write and integrate images and audio. So, unlike the other functions of the software, creating pages can be where users get stuck, and this can discourage their engagement with the annotations they’ve created. Missing out on this opportunity to make sense of their exhibit severely inhibits the purpose of the software as a tool for sustainable access. Because while audio and annotations together may be a type of intervention into accessibility issues, excluding contextual pages doesn’t fully grasp the opportunities of the software. This is why I believe these pages are essential to AVAnnotate as a tool for teaching users how to thoughtfully engage with the sustainability and accessibility of their annotated artifact as a source of information and knowledge.
<br>
  <br>
However, I’d also argue that the use of Markdown is essential to the conceptual framework of AVAnnotate. As a software for creating exhibits of annotations digitally, developing context in any other way would not be in accordance with AVAnnotate as a tool for teaching. The use of the “Create Pages” function—not alone but in combination with the rest of the software—develops the software as a mechanism for conceptualizing interventions in digital environments. In other words, the requirement of coding attunes users to their own role in sustaining an artifact in a digital space. It’s not that a word processing software would be “too easy”; the point is, the added difficulty of Markdown teaches users to be hyper aware of what constitutes the intervention that they’re creating. In a sense, creating contextual pages is an ethic of accountability as users construct, piece by piece, the significance of what they are promoting sustainability and accessibility to. While AVAnnotates response to the degradation of audio artifacts is surely rhetorical, what the software asks of users is also part of this rhetorical intervention.
<br>
  <br>
For such a reason, I believe that AVAnnotate is an essential tool for teaching rhetoric and writing, especially as these classrooms focus on sound, archival practices, and digital technologies. This software teaches students how to develop rhetorical interventions in digital and sonic spaces with a focus on how they, as individuals and a collective, are responsible for how they compose access. Pages, while they seem like a small part of a project and the software as a whole, make AVAnnotate a tool for teaching students about the importance of rhetoric and writing. 
</div>
<br>

## Collaboration

<div style="text-align: justify">
Speaking to the pedagogical and technological aspects of AVAnnotate, the software’s infrastructure encourages collaboration among learners interested in sustainable access to audio materials. Due to the software being built using Jekyll and GitHub pages—and also using IIIF—users have the opportunity to “fork” any public project and edit it or add to it. Also, AVAnnotate allows for users to “fork” projects together, creating a larger exhibit out of smaller projects. Essentially, the software’s infrastructure allows for projects to be infinitely collaborative.
<br>
  <br>
Say, for instance, 10 students wanted to create an exhibit of 10 different audio materials, context pages, and total projects built with AVAnnotate. These are all separate, but public, GitHub repositories. These students could fork all of their repositories to a single GitHub account and create a larger exhibit which links to each single project. I’ve found this process to be relatively easy with minimal understanding of GitHub’s functionality. The only issue is that once a project is forked the original owner can’t change their project. In other words, any updates won’t translate to the forked repository in the larger exhibit. This would require forking, again, the updated repository of a larger project and repeating the process of integrating it into the larger exhibit. However, barring this issue, collaborating on a large, multi-user project is simple and fruitful. AVAnnotate’s allowance of this type of communication creates an easy way for students to collaborate on topics of sustainability and access. Such a form of collaboration is truly innovative when working with this type of material.
<br>
  <br>
Another opportunity for collaboration that AVAnnotate’s infrastructure offers is collaboration on a single project via GitHub. GitHub allows for unlimited collaborators on a repository, which means that anyone with a GitHub account can be added to an exhibit someone has created with AVAnnotate. By “pulling,” viewing, and “pushing,” editing, an owner’s repository, individuals can make changes to a AVAnnotate project in GitHub. Once a repository is shared, it becomes available in a user’s AVAnnotate “My Projects” page, just under “Shared Projects.” This allows each collaborator to edit the GitHub repository via GitHub or AVAnnotate’s interface. So, if there are two collaborators with separate annotation sets, each can upload their own set without having to send files to one another. 
<br>
  <br>
The last collaborative function of AVAnnotate that I think is critical is the use of IIIF manifests. As mentioned in an earlier section, AVAnnotate requires creation or integration of a IIIF manifest for each audio artifact being annotated. At the bottom of each page, and even this page, is the created IIIF manifest. This can be used by anyone with access to this page by copying and pasting the manifest into a view such as Universal Viewer or Aviary Viewer—both of which are tools for viewing IIIF manifests and are available for free. AVAnnotate’s prioritization and requirement of IIIF manifests makes the software foremost a tool for collaboration. Any user with this manifest can not only listen to the associated artifact in a viewer but use the manifest to create their own AVAnnotate project with the same artifact. This is a really exciting function of AVAnnotate which is supported by IIIF. At the software’s core, AVAnnotate is creating opportunities for collaboration on sustainability and accessibility of audio material. Its technological infrastructure supports the teaching and learning of where collaboration intersects with access. 
</div>
<br>

## Application

<div style="text-align: justify">
  Integrating AVAnnotate into the classroom meets pedagogical objectives for instructors working with audio and visual material. In this section, I illustrate how AVAnnotate may be used for analysis— specifically, the goal being to develop an argument which considers if feedback and other qualities of shortwave radio are significant and meaningful features of this type of audio recording. Such an assignment requires students to consider the purpose and history of shortwave radio, how the quality of such recordings is a product but also an essential attribute of such recordings, how these waves travel, the reliability of this form of communication, and what transmission means.
 <br> <br>
The exhibit below breaks down this work in two ways: student groups and color-coded annotations. The student groups illustrate how annotation sets can be uploaded from multiple student groups into a single AVAnnotate project. Plus, the recording's annotations are two different colors to represent "for" (green) or "against" (red) the above argument. Green annotations argue that the sonic features of shortwave radio are significant as they construct meaningful transmissions. Red annotations argue that the same sonic features are not significant and, in fact, are inhibitive to transmissions.
</div>
<br>

## Conclusion

<div style="text-align: justify">
AVAnnotate functions best as a tool for teaching users how to use digital technologies for creation of rhetorical interventions into concerns about sustaining access to knowledge in audio artifacts at risk of obsolescence. At the software’s infrastructural core, it is devoted to supporting engagement with these artifacts in a way that teaches users how to become better listeners who are attuned to how their own practices affect the communication of essential information. And while this does require a small learning curve for users and enhancements to the software on AVAnnotate’s end, there are still many unique and fruitful opportunities that this tool provides for a variety of learning communities. In this conception of AVAnnotate, the software is not just a route to creating digital exhibits of audio annotations; AVAnnotate is an opportunity to become more responsible users of sound. By promoting collaborative listening devoted to the sustainable access of knowledge, AVAnnotate offers a rhetorical resource for artifactual degradation foregrounded by our digital age. 
</div>
<br>

## Acknowledgements

<div style="text-align: justify">
Thank you to editors Ashanka Kumari and Jonathan Marine for their helpful feedback and suggestions. Huge thanks to Ben and Sara Brumfield for helping with the Universal Viewer and for answering all of my endless questions! And thanks to Casey Boyle for reviewing an early copy of this software review. 

## References

Clement, T., Brumfield, B., & Brumfield, S. (2022). The AudiAnnotate Project: Four Case Studies in Publishing Annotations for Audio and Video. DHQ: Digital Humanities Quarterly, 16(2).
<br><br>
International Image Interoperability Framework. "Home." <a href="https://iiif.io/">
