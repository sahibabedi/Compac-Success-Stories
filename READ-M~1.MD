# How to put this online

Three files. No image folders. Every photo is built into the HTML itself,
so nothing can go missing and nothing travels alongside them.

```
index.html                              the case studies list
drum-pulper-open-gear/index.html        Drum Pulper case study
size-reducing-mill-bearings/index.html  Size Reducing Mill case study
```

Double click any of them to check it looks right. The images will be there.

---

## To publish

Upload all of it to GitHub keeping the folders exactly as they are, then
point `success-stories.compactech.co.in` at the top level.

Your addresses become:

- `success-stories.compactech.co.in`
- `success-stories.compactech.co.in/drum-pulper-open-gear/`
- `success-stories.compactech.co.in/size-reducing-mill-bearings/`

Then delete this file. It is notes for you, not part of the website.

---

## Afterwards

**The share preview picture.** All three files have one commented out line
near the top marked SHARE PREVIEW. Tell me the live address and I will fill
them in, or follow the note beside it. This is what makes a picture appear
when the link is pasted into LinkedIn or WhatsApp.

**Adding a case study.** Open `index.html`, find a block starting
`<a class="cs rv"`, copy it, and change the link, the principal, the image
and the title. Send it to me if you would rather not.

**The nine cards.** Two are live. Seven are marked "In preparation" and are
not clickable. When one is ready, remove `cs--soon` from its class and the
`<span class="soon-tag">` line, then add the link.

**Principal colours.** Change `data-principal` and `data-filter` on a card to
move it to another principal. The colour follows automatically. All twenty
partners are already set up and every colour was checked for legibility:

`kluber` `festo` `ansell` `chemtrend` `loctite` `oks` `asianpaints` `ppg`
`cumi` `fluidkraft` `gazpromneft` `chemin` `lubeco` `mak` `seko` `surtec`
`tectyl` `tefen` `teroson` `wurth`
