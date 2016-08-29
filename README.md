# psy111

this repo holds my ~~deepest darkest secrets~~ notes for PSY111-01 Foundations of Psychology at [SIUe](http://siue.edu), taught by Associate Professor [Dr. Gregory Everrett](https://www.siue.edu/education/psychology/bios/everettbio.shtml)

the textbook used is [Psychology Eleventh Edition in Modules](https://www.amazon.com/Psychology-Modules-David-G-Myers/dp/1464167524)

---
## Directory Structure

each folder in the repository follows the following format

```
e{number}_notes
|_slides/
| |_*.ppt(x)
|_*.md
```

the `e{number}` designates which exam it is (there are four of them).
inside the `slides/` dir are the slides that Dr. Everett has made available on Blackboard.
---
## File Formatting

### File
the beginning of each notes file is as follows:
```markdown
## {Intro Slide Title}
attached: {related files as links}
```

the `.md` files in the root of `e{number}` are the notes that are taken from lectures, and also transcriptions of the slides.
the `.md` files are the filenames of the slides, all lowercase.

### Slides
within the `.md` files, slides are denoted by
```markdown
---
## {Slide Title}
* first
  * first sub
* second
* ...
```

### Points
points that emphasized by Everrett in lecture are **bold** if bold in slides, or _italics_ if defined in lecture or in slides
  * italics are wrapped in `_` (underscores)
  * bolds are wrapped in `**` (double asterisk)

if a point defines the slide title, then the first point is `_def_ - {definition}`

### Extra Notes
if a point is made in lecture that is not in the slides, the notation is
```markdown
* _TN_ -
  * {information}
```

### Remember...
in lecture and slides, Everrett will emphasize a point often. but if there is a slide entitled _Remember..._ that content is linked to, in [`remember.md`][r].
the format for _Remember_ links is:
```markdown
[Remember](#remember)
```
and in [`remember.md`][r], the list follows
```markdown
n) Remember [n](/{filename}.md#remember)
```
where `n` is the number of the `n`th remember for the exam coverage

[r]: (/e1_notes/remember.md)
