# Mile High Roundup

Roundup-specific codebase for The Denver Post.

## Release notes 0.2

+ Add `<p>&nbsp;</p>` above `<h2>` tags to provide on-demand whitespace.
+ Because of the more visible link styling, try to link fewer word per sentence. Only real complaint from non-Outlook users yesterday.

## Release notes 0.1

+ Using cerberus, created new Outlook-friendly format that is cross-compatible with Gmail, iOS mail.
+ New image rules & format
   + Photos _must_ be resized or configured by URL to 580px
   + New format:
```
<center>
<p style="text-align: center;margin:0;padding:0;"<a href="[ARTICLE LINK]" style="text-decoration:none !important;"><img src="[IMAGE LINK]" aria-hidden="true" width="580" alt="alt_text" border="0" style="height: auto; background: #ffffff; font-family: sans-serif; width:100%;font-size: 15px; line-height: 100%; color: #555555;"></a></p>
<p class="credit">[CREDIT]</p>
<p class="cutline">[CUTLINE]</p>
</center>
```

