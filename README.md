Mirage
-----

An experimental extracted repo of the mirage theme files, useful for including as a submodule in your own DSpace git repo

Folder
--

###[dspace]/xmlui/webapp/themes


based on 
---

https://repositories.tdl.org/uh-ir

Links
---

https://wiki.duraspace.org/display/DSDOC18/Mirage+Configuration+and+Customization

###[dspace]/config/webapp/themes/news-xmlui.xml

```xml
<?xml version="1.0" encoding="UTF-8" ?>
<document xmlns="http://di.tamu.edu/DRI/1.0/" xmlns:i18n="http://apache.org/cocoon/i18n/2.1" version="1.1">
	<body>
		<div id="file.news.div.news" n="news" rend="primary">
			<head>DSpace Repository</head>
			<p>DSpace is a digital service that collects, preserves, and distributes digital material. Repositories are important tools for preserving an organization&apos;s legacy; they facilitate digital preservation and scholarly communication.</p>
			<p></p>
			<p></p>
			<p></p>
		</div>
	</body>
	<options/>
	<meta>
		<userMeta/>
		<pageMeta/>
		<repositoryMeta/>
	</meta>
</document>
```
###dspace.cfg settings

#---------------------------------------------------------------#
#----------------XMLUI THEME CONFIGURATIONS---------------------#
#---------------------------------------------------------------#
# These configs are only used by the XML User Interface         #
#---------------------------------------------------------------#

xmlui.theme.twiter.username=royopa
xmlui.theme.facebook.username=royopa
xmlui.theme.youtube.username=royopa