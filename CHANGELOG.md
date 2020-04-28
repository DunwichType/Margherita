# Margherita Typeface Changelog


###1.008
Made adjustments to improve legibility on screens.t

Acute and caron are no longer flipped components. Mac OS was rendering the flipped components lighter than they really are because the outlines of the components were going in the wrong direction.

Grave in circumflexcomb_gravecomb and circumflexcomb_gravecomb.case has been moved to the right 

Acute in ohornacute and Ohornacute has been moved to the left
Hook in in ohornhookabove and Ohornhookabove has been moved to the left
Tilde in in ohorntilde and Ohorntilde has been narrowed and moved to the left
Raised tilde in brevecomb_tildecomb, brevecomb_tildecomb.case, circumflexcomb_tildecomb, and circumflexcomb_tildecomb.case.

Decomposed tilde in brevecomb_tildecomb, brevecomb_tildecomb.case, circumflexcomb_tildecomb, and circumflexcomb_tildecomb.case. This is due to the tilde flying away in Mac OS as weight increased.

Mark positions and widths have been adjusted in ğ ǧ ĝ ģ ġ 

Increased distance of ť<character> kerns

Reduced height (not position) of caron in ť

Moved caron in ď ľ to the right

arches in h n m r shaped glyphs now use the “serifs and crossbars” stem because assigning them their own stem value was making them too heavy in bold and black weights.

removed interpolation instruction from ə Ə because it made the bar too heavy

The heavy horizontal stroke of g now uses the serifs and crossbars stem. Renders lighter but still drops down too far on Windows. I don’t think this can be fixed.

###1.007

Webfonts now use WOFF2 format.

Webfonts and TTF fonts now use manual hints. This significantly reduces file size compared to the autohinted fonts.

Made the following changes to improve screen rending at small sizes:

• Lowered crossbar of H in Ħ and increased the weight of the bar to match H.

• Added TT instructions to Æ

• Fixed TT instructions in Œ

• Fixed TT instructions in ð so top doesn’t drop below cap height

• Lowered top of arches, moved bar and increased its weight in đ and ħ

• Added TT instructions to ₹

• Raised tilde in brevecomb_tildecomb and brevecomb_tildecomb.case so they don’t smudge together in Windows.

• Removed interpolation hints in M, a, x, v

• Added anchors to serifs on C, G, S, ¥, 

• Removed all triple hints.

• Removed diagonal hint from 3.

• Added instructions to ×