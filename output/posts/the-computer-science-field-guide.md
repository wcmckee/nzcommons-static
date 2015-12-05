<html><body><strong><h4>by Tim Bell and Marcus Stenfert Kroese</h4></strong>

Imagine as a high school teacher needing to teach a subject that you have barely heard of, has never been taught before in schools, and it counts towards a student’s graduating assessment!



This happened to many teachers in 2011, when New Zealand became one of the first countries in the English-speaking world to offer Computer Science as a formal topic in high school. As in many other countries, prior to this, computing had been taught in a way that viewed students as <i>users</i> rather than <i>developers</i>. However, due to New Zealand being an early adopter, there were very few resources available for teachers, and those that were available were disparate, generally being pitched at a level that was too high (e.g. university courses) or too low (e.g. the CS Unplugged activities for primary school children).



In response to this, the <a title="Computer Science Research Group at Canterbury University" href="http://cosc.canterbury.ac.nz/research/RG/CSE/" target="_blank">Computer Science Education Research Group</a> at the University of Canterbury (also known as the "Department of Fun Stuff") started work on the <a title="Computer Science Field Guide" href="http://csfieldguide.org.nz" target="_blank">Computer Science Field Guide</a>, an online "textbook" to serve as a resource for high school students and a guide for teachers. The demand for the resource was so high that it was already getting heavy use while it was still being developed, to the point that we now just call it a "beta" release, and are constantly working to improve it.



The online book has been designed to be engaging and give a quirky approach to the topics, making good use of genuinely interactive activities to enable students to experience the concepts first-hand. It generally uses a constructivist approach, where we aim to lead students through experiences that enable them to construct concepts in their own minds, rather than us simply giving them information. We have developed short videos for the start of each chapter to raise some of the questions that the topic addresses, usually in a humorous way, and presented by a Computer Science student so that the material is authentic and approachable -- for example:



<iframe src="https://www.youtube.com/embed/Hwqmu6pvr6g" width="560" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>



Following in the footsteps of its sister site <a title="Computer Science Unplugged" href="http://csunplugged.org/" target="_blank">Computer Science Unplugged</a>, which is intended for primary-aged students, the CS Field Guide does not require <i>any</i> programming of the students. This is to prevent learning programming being a barrier for students to engage with the exciting and surprising ideas in Computer Science; in fact, for some students, finding out what Computer Science is will be a motivator to learn to program.



The guide is licensed under a Creative Commons Attribution-NonCommercial-ShareAlike licence, so users are welcome to take copies and modify them. The material is produced using the open-source <a title="Sphinx" href="http://sphinx-doc.org/" target="_blank">Sphinx</a> system, which was originally designed for writing Python documentation, and works from plain-text source files using the reStructuredText format (although we are in the process of changing to a more manageable format). The interactives are written using JavaScript and HTML5, and the videos are released on vimeo.com so that teachers can download them. All of these components are released with the Creative Commons licence so that the entire book can be reconstructed independently. Many people have contributed to different parts of the guide with videos, interactive activities, images and ideas, although most of the writing has been done by just a few people, which has kept it more consistent and coherent.



The guide is currently presented as a website, and the various components are carefully configured to work on as many systems as possible, especially bearing in mind that some schools operate using very old computer labs or old versions of software, while others may primarily use tablets, which places a lot of restrictions on the technologies that can be used effectively. Often if a teacher encounters something that won't work, they need to apply for new software to be installed, and even if it's approved it may take some time, so our goal is to put in as few barriers as possible.



The system we're using can also generate pdf and ebook (epub and mobi) versions of the text. Teachers appreciate being able to print a copy (although this obviously loses the video and interactive components). The ebook versions are still under development as our priority has been to fill out the online web version first.



<a href="/wp-content/uploads/2015/05/imagebitcomparer.png"><img class="size-medium wp-image-526" src="/wp-content/uploads/2015/05/imagebitcomparer-300x172.png" alt="Computer Science Field Guide, licensed CC BY-NC-SA" width="300" height="172"></a> Computer Science Field Guide, licensed CC BY-NC-SA



<b>Why have the resource open?</b>



There were several reasons for choosing to keep the resource as open as possible:<strong><strong> </strong></strong>

<ul>

	<li>Open Source is natural for the Computer Science community. Programming languages tend to be open source, or at least available at no cost. From a teaching point of view, this means that students can use the resources on any computer and at home without restriction. Teachers and students come to expect Computer Science resources to be free, and any that aren't may be overlooked. The approach we're taking is modeled after (and in cooperation with) the <a title="Runestone Interactive" href="http://runestoneinteractive.com/" target="_blank">Runestone Interactive</a> project, which offers several interactive open-source Computer Science books.</li>

	<li>We have limited resources (both time and money), and don't want the book to be limited by our capacity, yet we needed to get something out quickly.</li>

	<li>It's important for the resource to be adaptable. NZ has been leading the world in Computer Science in high schools, and there is strong interest in our resources, so by making it open it can be readily adapted for overseas contexts where the curriculum may be similar but not exactly the same. This also makes translation simple -- no special permission is required.</li>

	<li>We can use other open resources as part of the guide; for example, some xkcd comics relate well to the topic, and can be used in this context.</li>

	<li>Being open gives teachers security that the resource won't go away or date, since someone else can pick it up if we are unable to continue with it.</li>

</ul>

Teachers have reported copying sections of the guide to their own local school pages, and making selected parts available to students to help them focus; being open gives the flexibility for them to customise it for their students, or simply use it as it is.



<a href="/wp-content/uploads/2015/05/computersciencefieldguide.png"><img class="size-medium wp-image-527" src="/wp-content/uploads/2015/05/computersciencefieldguide-300x153.png" alt="Computer Science Field Guide, licensed CC BY-NC-SA" width="300" height="153"></a> Computer Science Field Guide, licensed CC BY-NC-SA



<b>Challenges</b>



Writing a school "textbook" with shared authorship and open content creates a number of challenges.



One of these is how to deal with "secret" parts of the book. Many textbooks have a teachers' version that includes answers to questions. Teachers appreciate having these answers available so they can be sure they've got things right and then help stimulate discussion about the question. Openness brings the concern that a student might download the teacher version and subvert their own learning by simply reading off answers instead of thinking though the questions. Our approach has been that the teacher version contains a lot of material that teachers value but students would find uninteresting, and the hope is that students won't be interested in delving in to it for the wrong reasons. In end, students need to realise that the goal is for them to learn, rather than to look smart in class or annoy their teacher!



The teacher version is generated from the same source file as the student version, which makes editing and consistency a lot easier than having two versions. The Sphinx system has commands for the conditional use of sections of text; this can be expanded in the future to accommodate other versions, perhaps for slightly different curricula or year levels.



Another challenge is keeping the resource consistent. Authors have a remarkably wide variety of styles, and we have gone for a slightly quirky and constructivist style. Another author might see the constructivism as not giving all the information, and in an open source environment that could come in and "fill in the gaps", inadvertently undermining the pedagogy. Everyone has opinions on how education should be done, and if the material ends up being done "by committee", then it's hard for it to be vibrant and have character. Also, the author needs to understand the audience (in this case, NZ teenagers and their teachers).



To date, diverse authorship hasn't been a major problem, because all the writing has been done within a small close-knit group, but it's possible that other versions may fork from ours. Our hope is that if a new version is better it will flourish, and if not, it will have been a useful experiment!



Translation of open books is also a challenge that we have yet to tackle properly. An open-source textbook can be copied by others who want to add a fork in the content. If the original guide is changed, the copy becomes out of date. The same applies to translations of the guide, since each translation is also a new version, and later updates may need to be re-translated. This is a wide challenge in open publishing -- for example, until recently, Wikipedia simply allowed different translations of articles to appear independently, so inevitably they would get out of sync.



Another challenge is that the software behind a site needs to be open to make the content truly open. In our case, the main text processing is all done by open-source software, but there are elements (such as the video production) that use proprietary software. The sister site, CS Unplugged, has a similar issue, where currently the source of the main book is available in MS Word. The content is open, but users are forced to use proprietary software to edit the document. They could use OpenOffice, but the formatting gets badly messed up. Of course, the document is available as pdf as well, but that can't be edited easily. Ultimately we may revert to a similar system to the field guide, a plain-text markup language as the source, and then many different formats generated from it.



Developing an open source "textbook" has many challenges, but the benefits of getting it to schools quickly and giving teachers confidence that they can have some control over the content (in principle at least) has been worthwhile.



<em>Tim Bell is a professor in the Department of Computer Science and Software Engineering at the University of Canterbury. His main current research interest is computer science education. Marcus Stenfert Kroese is a final-year Software Engineering student at the University of Canterbury. His Honours research is focused on improving the system that the Computer Science Field Guide is built upon.</em></body></html>