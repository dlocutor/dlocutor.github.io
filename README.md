## Topics

Cloned local DLOC .. 

You can use the [editor on GitHub](https://github.com/dlocutor/dlocutor.github.io/edit/master/README.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### NETCOMP Reference

#### Manipulating Media

Great [site](https://www.linuxuprising.com/2019/11/ffmpeg-extract-audio-from-video-in.html) overview.

strip audio from video:<br>

	ffmpeg -i input.mp4 -c copy -an no-sound-output.mp4
	
extract audio from video .. we want the audio<br>	

	ffmpeg -i myvideo.mp4 -vn -acodec copy audio.ogg	

#### CLI Marathon & Discoveries

[ncdu article](https://www.cyberciti.biz/open-source/install-ncdu-on-linux-unix-ncurses-disk-usage/?utm_source=dlvr.it&utm_medium=twitter)

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/dlocutor/dlocutor.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
