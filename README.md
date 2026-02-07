# universal-erpnext-letterhead

How to achieve universal Print Customization (for regular print formats):


1. Upload 2 files. 1 for watermark, the other with all the margins header, footer and everything (i.e. printing background), except the white background should be transparent.

2. Create a LetterHead and a Print Style with the given codes. For the letterhead, only use the header section. Make sure you replace the url("YOUR_WATERMARK_LINK") and <img src="YOUR_PRINTING_BG_LINK"> with the right links.

3. Goto Print Settings and set the new Print Style as the default Print Style.

4. If needed, modify the padding in the Print Style's “your text safe area” section to align the text box with your printing background. You can do the same for the watermark by modifying the /* tweak position */ section of the LetterHead.

5. Once all is done, you're good to go.

Note: For custom HTML-based print formats, you'll need to put the CSS code separately on the Custom CSS section of the Print Format. 
