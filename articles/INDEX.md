# Index

> All your notes are belong to us

### Emerging Structure

> See [[INDEX#The MAP of MOC|The MAP of MOC]]

- [[INDEX]]
- [[Interests]] 
- [[Business]]
- [[PKM]] & [[Lists]]
- [[Ideas]]

## Top of Mind

	What is currently top of mind for me
	
![[Top of Mind]]

##### Saved Searches

- `-/\[\[[\\d\- ]+\]\]/`: No Outgoing Links (Orphans)
- `/^([a-zA-Z0-9._%-]+@[a-zA-Z0-9.-]+\.[a-zA-Z]{2,6})*$/`: Find emails
- `content:`: Searches document content only
- `tag:`: Searches tags only
- `path:`: Searches based on a specific path
- `path:-"Journal"`: No Daily notes

---

#### Tag Definitions & Groupings

- #📥️ ==Seed box | items that i am / will be actively working on==
- #🌱️ ==Seedlings | distilled from literature notes==
- #🌞️ ==Incubator | items not yet ready for planting or in need of planting==
- #🌲️ ==Evergreen | forest notes==
- #✏️ [[✏️]]==Workbench Note | Tagging salient points for consolidation on the workbench== 

---

- #✅️ ==Items that have tasks that i need to complete==
- #🗺️ ==Maps of Content (the emerging organizational structure)==
- #⚙️ ==General utilities i use in this system==
- #❗️ ==IMPORTANT==
- #🏷️ [[🔗️☁️]] ==Tag Notes==



### Types of Content

- `@`: Person 

---

- `{`: Books, eBooks, or Audio Books 
- `!`: Tweets
- `%`: Podcasts / Audio media
- `+`: YouTube Videos
- `(`: Web Articles or Publications, Newspapers, etc.
- `^`: Research Paper

#### Simple Drawing Creation

https://excalidraw.com/

###### Build Index of Links & Counts

```bash
egrep -ohsr --exclude-dir='.*' "\[\[[A-Za-z0-9 _@ÄÖÜäöüß\'\!\?\.\(\)\-]+\]\]" -- * | sed -e 's/[[:space:]]#/#/' | sort | uniq -c | sort -r -t# -k2  > "🔗️☁️.md"
```


## The MAP of MOC

```mermaid

graph LR;
	INDEX --> Interests
		Interests --> Statistics
		Interests --> Programming
			Programming --> Vim
			Programming --> Bash
			Programming --> Python
			Programming --> R
			Programming --> C++
			Programming --> LaTeX
			Programming --> Groff
	INDEX --> Business
		Business --> YouTube
	INDEX --> PKM
	INDEX --> Lists	
	INDEX --> Ideas

	click INDEX "obsidian://vault/Knowledge/INDEX"
	click Interests "obsidian://vault/Knowledge/Interests"
			click Statistics "obsidian://vault/Knowledge/Statistics"
			click Programming "obsidian://vault/Knowledge/Programming"
				click Vim "obsidian://vault/Knowledge/Vim"
				click Bash "obsidian://vault/Knowledge/Bash"
				click Python "obsidian://vault/Knowledge/Python"
				click R "obsidian://vault/Knowledge/R"
				click C++ "obsidian://vault/Knowledge/C++"
				click LaTeX "obsidian://vault/Knowledge/LaTeX"
				click Groff "obsidian://vault/Knowledge/Groff"
			click Business "obsidian://vault/Knowledge/Business"
				click YouTube "obsidian://vault/Knowledge/YouTube"
			click PKM "obsidian://vault/Knowledge/PKM"
			click Lists "obsidian://vault/Knowledge/Lists"
			click Ideas "obsidian://vault/Knowledge/Ideas"
	
```