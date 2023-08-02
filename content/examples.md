+++
math = false 
meta = false
author = "Elliot"
date = "2022-01-20"
title = "Examples"
subtitle = "An overview"
toc = true
+++

<p><span class="newthought">In his later books<label for="sn-in-his-later-books" class="margin-toggle sidenote-number"></label></span><input type="checkbox" id="sn-in-his-later-books" class="margin-toggle"/><span class="sidenote"><a href="http://www.edwardtufte.com/tufte/books_be"><em>Beautiful Evidence</em></a></span>, Tufte starts each section with a bit of vertical space, a non-indented paragraph, and the first few words of the sentence set in small caps. For this we use a span with the class <code>newthought</code>, as demonstrated at the beginning of this paragraph. Vertical spacing is accomplished separately through <code>&lt;section&gt;</code> tags. Be consistent: though we do so in this paragraph for the purpose of demonstration, do not alternate use of header elements and the <code>newthought</code> technique. Pick one approach and stick to it.</p></p>

<p><label for="mn-figure-1" class="margin-toggle">&#8853;</label><input type="checkbox" id="mn-figure-1" class="margin-toggle"/><span class="marginnote"><img src="https://edwardtufte.github.io/tufte-css/img/rhino.png" alt="Image of a Rhinoceros"/>F.J. Cole, “The History of Albrecht Dürer’s Rhinoceros in Zooological Literature,” <em>Science, Medicine, and History: Essays on the Evolution of Scientific Thought and Medical Practice</em> (London, 1953), ed. E. Ashworth Underwood, 337-356. From page 71 of Edward Tufte’s <em>Visual Explanations</em>.</span> But tight integration of graphics with text is central to Tufte’s work even when those graphics are ancillary to the main body of a text. In many of those cases, a margin figure may be most appropriate. To place figures in the margin, just wrap an image (or whatever) in a margin note inside a <code>p</code> tag, as seen to the right of this paragraph.</p>
<p>If you need a full-width figure, give it the <code>fullwidth</code> class. Make sure that’s inside an <code>article</code>, and it will take up (almost) the full width of the screen. This approach is demonstrated below using Edward Tufte’s English translation of the Napoleon’s March data visualization. From <em>Beautiful Evidence</em>, page 122-124.</p>
<figure class="fullwidth">
  <img src="https://edwardtufte.github.io/tufte-css/img/napoleons-march.png" alt="Figurative map of the successive losses of the French Army in the Russian campaign, 1812-1813" />
</figure>
<p>One obstacle to creating elegant figures on the web is the difficulty of handling different screen sizes, especially on the fly. Embedded <code>iframe</code> elements are particularly troublesome. For these instances we provide a helper class, <code>iframe-wrapper</code>, the most common use for which is probably YouTube videos, e.g.</p>


<figure>
  <label for="mn-exports-imports" class="margin-toggle">&#8853;</label><input type="checkbox" id="mn-exports-imports" class="margin-toggle"/><span class="marginnote">From Edward Tufte, <em>Visual Display of Quantitative Information</em>, page 92.</span>
  <img src="https://edwardtufte.github.io/tufte-css/img/exports-imports.png" alt="Exports and Imports to and from Denmark & Norway from 1700 to 1780" />
</figure>        

{{< blockquote cite="www.shawnohare.com" footer="Shawn" >}}
  There is nothing more beautiful than an elegant mathematical proof.
{{< /blockquote >}}

{{< epigraph pre="Author Writer, " cite="Math is Fun" link='https://www.google.com' >}}
This is an example of an epigraph with some math
$ \mathbb N \subseteq \mathbb R $
to start the beginning of a section.
{{< /epigraph >}}

### (what am I up to [now](https://maya.land/now/)?)

After a certain amount of analysis paralysis,{{< sidenote >}}Some sidenote{{< /sidenote >}} I decided I could announce my structure intentions here and iterate.

## Types

### Evergreen Content

This is what I would like to do most of. {{< marginnote >}}Some marginnote{{< /marginnote>}} My site inspiration comes from old stuff I remember from Back In The Day, and then more contemporarily, [Marijn](https://marijnflorence.neocities.org/) and [Kicks Condor](https://kickscondor.com/)<sup id="fnref:1" role="doc-noteref">[1](https://maya.land/site-structure/#fn:1)</sup>. For now, let’s make a list:

*   [alcohol](https://maya.land/alcohol/)
*   [astrology](https://maya.land/astrology/)
*   [bones](https://maya.land/bones/)
*   [books](https://maya.land/books/)
*   [college advice](https://maya.land/college-advice/)
*   [comics](https://maya.land/comics/)
*   [compound](https://maya.land/compound/)
*   [crochet](https://maya.land/crochet/)
*   [fine art](https://maya.land/fine-art/)
*   [goblin manifesto](https://maya.land/goblin/)
*   [gouache](https://maya.land/gouache/)
*   [heraldry](https://maya.land/heraldry/)
*   [incense](https://maya.land/incense/)
*   [the internet](https://maya.land/internet/)
*   [latin](https://maya.land/latin/)
*   [laugh rule](https://maya.land/laugh-rule/)
*   [now listening](https://maya.land/now-listening/)
*   [notetaking](https://maya.land/notetaking/)
*   [paper and notebooks](https://maya.land/paper/)
*   [pens](https://maya.land/pens/)
*   [perfume](https://maya.land/perfume/)
*   [premodernity](https://maya.land/premodern/)
*   [reenchanted time](https://maya.land/reenchanted-time/)
*   [russian](https://maya.land/russian/)
*   [screenshot garden](https://maya.land/screenshot-garden/)
*   [seattle](https://maya.land/seattle/)
*   [spaced repetition systems](https://maya.land/spaced-repetition/)
*   [tarot](https://maya.land/tarot/)
*   [technical notes](https://maya.land/technicalities/)
*   [thirty year plan](https://maya.land/thirty-year-plan/)
*   [videogames](https://maya.land/videogames/)
*   [words](https://maya.land/words/)
*   [zines](https://maya.land/zines/)

### [Updates to Evergreen Content (“updates”)](https://maya.land/updates/)

When I make a change worth checking out on evergreen content, I intend to make a very short note of it as a “post” “update”. This is for RSS purposes, really.

## [Chronological Content (“posts”)](https://maya.land/posts/)

### [Dependent Content (“responses”)](https://maya.land/responses/)

The sort of thing one might send a [Webmention](https://indieweb.org/Webmention) for with a particular recipient in mind.

### [Independent Chronological Content (“monologues”)](https://maya.land/monologues/)

I’m not sure how much of this I want to do, to be frank. But it will have its own category so that if you are not interested in dependent content you can subscribe without it.</div>