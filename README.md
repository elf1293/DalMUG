This repository contains the content for the dalmug.org website.

To add a blog post you need to simply create a new file within the `/_posts/` directory and it has to be named YEAR-MM-DD-Name-of-Post.md. For example `2017-10-27-Comparative-Metagenomics-of-Blastocystis.md`. Note that the "Name-of-Post" is important and is the title used for that blog post. 

Once you make the new .md file you need to place:
```
---
published: true
post_snippet: INSERT_TEXT_HERE
---
```

At the top of the file (or you can replace ```published:true``` with ```published:false``` if you want to simply save it as a draft and wait to publish it later). For [example](
https://raw.githubusercontent.com/LangilleLab/DalMUG/master/_posts/2017-10-27-Comparative-Metagenomics-of-Blastocystis.md).

The text following ```post_snippet``` is the preview of the post that will be shown on the Blog page under the post title.

Formatting is done using Markdown. 
This [Markdown Cheatsheet](http://www.jekyllnow.com/Markdown-Style-Guide/) might come in handy.

Lastly, instead of editing directly on github, you can use [http://prose.io](http://prose.io) which provides a nicer web-based user interface for editing. 
