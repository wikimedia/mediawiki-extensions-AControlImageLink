Prevents [[File:Something.pdf|thumb]] from rendering on the pages if all of the following is true:
1) "pdf" is listed in $wgAControlImageLinkRestrictedExtensions array: $wgAControlImageLinkRestrictedExtensions = [ 'pdf' ],
2) File:Something.pdf has <accesscontrol> tag,
3) Article that includes [[File:]] syntax either doesn't have <accesscontrol> tag,
or its <accesscontrol> tag is different from <accesscontrol> on File:Something.pdf.

If thumbnailing was prevented, an image redlink will be shown instead of thumbnail.
