---
layout: meta-pattern
title: Accessibility
categories: meta-patterns
tags:
- basic guidelines
description: General guidelines for making your site and service accessible
---

<h4>How do I improve the accessibility of my service?</h4>
<p>Imagine accidentally sitting on your glasses. Could you work without them? Would you be able to find and read information on the web? Now imagine breaking your arm: could you do everything you need to on your computer without a mouse or keyboard? Finally, imagine waking up tomorrow to discover you're blind: could you still do your job?Web accessibility is about making sure that we can all use websites and web applications, regardless of our abilities.</p>
<p>To improve accessibility your site needs:</p>
<ul>
<li>clear content, straightforward language and a clear, simple layout</li>
<li>good navigation and the ability to know where you are within a site</li>
<li>meaningful and clear hyperlinks</li>
</ul>
<p>Accessibility is not a bolt-on activity or after-thought, but a core part of our design activities. The way to achieve accessibility objectives is through a process of inclusive design: Inclusive Design is neither a new genre of design, nor a separate specialism.</p>
<p>The following guidelines are grouped according to the 3 main phases of the design life cycle:</p>
<ol>
<li>Research</li>
<li>Design</li>
<li>Evaluation</li>
</ol>
<p>The design requirements are summarised as an <a href="//www.ebi.ac.uk/seqdb/confluence/download/attachments/16584495/accessibility_infographic.png?version=1&amp;modificationDate=1325852128000">Accessibility infographic</a> (see also here <a href="http://webaim.org/resources/designers/" rel="nofollow">http://webaim.org/resources/designers/</a>)</p>
<h5>Research</h5>
<h6>Define the target audiences</h6>
<p>The needs of target audiences ought to take precedence over the needs of other audiences. Defining a number of target audiences does not mean that everyone else is excluded; it just means that the requirements, design and testing activities will focus on these user groups as the most likely users of the web product.</p>
<h6>Analyse the needs of the target audiences</h6>
<p>Desk research into the general needs of the the website's or application's target audiences, taking special note of the general needs of disabled and older people.</p>
<h5>Design</h5>
<table>
<tbody>
 <tr>
  <th>Design aspect to improve accessibility</th>
  <th>Description</th>
 </tr>
 <tr>
  <td>Provide appropriate alternative text</td>
  <td>
  <ul>
   <li>Every non-text element needs a text alternative (alt text) that provides an equivalent to the image content.</li>
   <li>Alt text should present the content and function, not necessarily a description, of an image.</li>
   <li>If an image has no relevant content or function, is decorative, or the alternative text is provided in nearby text, then the image should have an empty alternative text value (alt="").</li>
   <li>If an image is a link (or hotspot), the alt text must describe the link's function.</li>
   <li>Avoid words like "picture of," "image of," or "link to."</li>
   <li>Use the fewest number of words necessary.</li>
   <li>See: <a href="http://webaim.org/techniques/alttext/" rel="nofollow">http://webaim.org/techniques/alttext/</a> <a href="http://webaim.org/techniques/alttext/" rel="nofollow">http://webaim.org/techniques/alttext/</a></li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Ensure content is well structured and clearly written</td>
  <td>
  <ul>
   <li>Use the simplest language appropriate for your content.</li>
   <li>Organize your content using true headings (e.g. &lt;h1&gt;) and lists.</li>
   <li>Use empty (white) space to improve readability.</li>
   <li>Use illustrations, icons, etc. to supplement text.</li>
   <li>Check spelling, grammar and readability.</li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Help users navigate to relevant content</td>
  <td>
  <ul>
   <li>Provide a link that allows the user to skip over navigation to the main content in the page (<a href="http://webaim.org/techniques/skipnav/" rel="nofollow">http://webaim.org/techniques/skipnav/</a> <a href="http://webaim.org/techniques/skipnav/" rel="nofollow">http://webaim.org/techniques/skipnav/</a>)</li>
   <li>Use true headings to organize content.|</li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Provide headers for data tables</td>
  <td>
  <ul>
   <li>Identify all data table headers using the &lt;th&gt; element.</li>
   <li>Provide an appropriate scope attribute: &lt;th scope="col"&gt; for column headers or &lt;th scope="row"&gt; for row headers.</li>
   <li>If appropriate, add a table &lt;caption&gt; for the data table.</li>
   <li>See: <a href="http://webaim.org/techniques/tables/" rel="nofollow">http://webaim.org/techniques/tables/</a> <a href="http://webaim.org/techniques/tables/" rel="nofollow">http://webaim.org/techniques/tables/</a></li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Do not rely on colour alone to convey meaning</td>
  <td>
  <ul>
   <li>The use of colour can enhance comprehension, but do not use colour alone to convey information. Be especially cautious of red/green colour combinations.</li>
   <li>Make sure that colour contrast is strong, especially between text and background.</li>
   <li>See: <a href="http://www.webaim.org/articles/visual/colorblind/" rel="nofollow">http://www.webaim.org/articles/visual/colorblind/</a> <a href="http://www.webaim.org/articles/visual/colorblind/" rel="nofollow">http://www.webaim.org/articles/visual/colorblind/</a></li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Ensure users can complete and submit all forms</td>
  <td>
  <ul>
   <li>Put form labels adjacent to or near their controls, so the labels are associated visually.</li>
   <li>Use the &lt;label&gt; element to associate labels and controls.</li>
   <li>Group similar elements (such as checkboxes or radio buttons) together using &lt;fieldset&gt;.</li>
   <li>Clearly identify required form elements. Don't make a field required if it is not necessary. Ensure all directions and cues are readily accessible.</li>
   <li>If there are errors in a form that has been submitted, alert the user in an accessible way (especially to a screen reader user) and make it easy to fix the incorrect information and resubmit the form.</li>
   <li>See: <a href="http://webaim.org/techniques/forms/" rel="nofollow">http://webaim.org/techniques/forms/</a> <a href="http://webaim.org/techniques/forms/" rel="nofollow">http://webaim.org/techniques/forms/</a></li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Ensure links make sense out of context</td>
  <td>
  <ul>
   <li>Avoid phrases like "Click here", "Here", "More", "More information", "Read more", and "Continue."</li>
   <li>URLs as link text should usually be avoided, unless the URL is relevant content. In terms of bioinformatics, we can interpret this as link on names, not accession numbers. For example, "<ins>Protein binding</ins> (GO:0005515)" is better than "<ins>GO:0005515</ins> (Protein binding)" for:</li>
   <li>Screen readers: hearing "protein binding" is more informative than hearing "GO:0005515" for people who are blind, partially-sighted or dyslexic</li>
   <li>Search engines: Google, Bing and other search engines give extra weight to the words used in links, so people searching for "protein binding" or "binding" will be more likely to find your page</li>
   <li>Training courses: it's easier and less error-prone to say "click protein binding" than "click go-colon-zero-zero-zero-five-five-one-five".</li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Other accessibility checks</td>
  <td>
  <ul>
   <li>Ensure that the page is readable and usable when fonts are enlarged 200-300%.</li>
   <li>Provide a descriptive page &lt;title&gt;.</li>
   <li>When using scripting, ensure events are available with both mouse and keyboard. Make all scripted content and page updates/changes available to screen readers.</li>
   <li>Limit pop-up windows and notify users when pop-ups are used.</li>
   <li>Provide a descriptive title for all frames (e.g., &lt;frame title="navigation"&gt;).</li>
   <li>Follow HTML and CSS coding standards.</li>
  </ul>
  </td>
 </tr>
</tbody>
</table>
<h6>Recommended extra checks</h6>
<ul>
<li>Ensure accessibility of non-HTML content
<ul>
 <li>HTML content will almost always be more accessible than content in any other format.</li>
 <li>PDF, Microsoft Word and PowerPoint files, OpenOffice.org, and Adobe Flash provide basic accessibility features.</li>
 <li>Provide accessible alternatives when non-HTML content cannot be made fully accessible.</li>
 <li>Test the accessibility of non-HTML content in assistive technologies.</li>
</ul>
</li>
<li>Caption and/or provide transcripts for media
<ul>
 <li>Videos and live audio must have captions and a transcript. A transcript is sufficient for archived audio.</li>
 <li>Captions should be synchronized, equivalent and accessible.</li>
 <li>See: <a href="http://webaim.org/techniques/captions/" rel="nofollow">http://webaim.org/techniques/captions/</a> <a href="http://webaim.org/techniques/captions/" rel="nofollow">http://webaim.org/techniques/captions/</a></li>
</ul>
</li>
</ul>
<h5>Evaluation</h5>
<table>
<tbody>
 <tr>
  <th>Methods to evaluate accessibility</th>
  <th>Description</th>
 </tr>
 <tr>
  <td>WAVE web accessibility evaluation tool</td>
  <td>Test your website or unpublished HTML automatically:[<a href="http://wave.webaim.org/" rel="nofollow">http://wave.webaim.org/</a>|<a href="http://wave.webaim.org/]">http://wave.webaim.org/]</a></td>
 </tr>
 <tr>
  <td>Disable styles and linearise tables</td>
  <td>
  <ul>
   <li>Styles can be disabled with the "Web Developer toolbar" extension for Firefox.</li>
   <li>Ensure the reading order is logical.</li>
   <li>Ensure content is still understandable and usable.</li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Check alternative text</td>
  <td>
  <ul>
   <li>Ensure alt text is succinct, but accurate and useful.</li>
   <li>Using the Firefox Web Developer toolbar, select&amp;
   <ul>
    <li>"Display &nbsp;Alt Attributes." Is the alt text equivalent?</li>
    <li>"Replace &nbsp;Images With Alt Attributes." Does the alternative text make &nbsp;sense?</li>
   </ul>
   </li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Verify color and contrast</td>
  <td>
  <ul>
   <li>Color contrast:[<a href="http://webaim.org/resources/contrastchecker/" rel="nofollow">http://webaim.org/resources/contrastchecker/</a>|<a href="http://webaim.org/resources/contrastchecker/]">http://webaim.org/resources/contrastchecker/]</a></li>
   <li>Color-blindness: <a href="http://colorfilter.wickline.org/" rel="nofollow">http://colorfilter.wickline.org/</a> <a href="http://colorfilter.wickline.org" rel="nofollow">http://colorfilter.wickline.org</a></li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Test content scaling</td>
  <td>
  <ul>
   <li>Enlarge the font in your web browser to 200-300%. Is the page readable and usable? Is horizontal scrolling minimized?</li>
   <li>Zoom the web page in your browser (enlarge fonts and images). Is text in images readable? Is contrast sufficient?</li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Check keyboard accessibility</td>
  <td>
  <ul>
   <li>Navigate the site using only the keyboard (Tab, Shift + Tab, Enter, etc.). Is all functionality available?</li>
   <li>Is a "skip navigation" link available? (see webaim.org/techniques/skipnav/)</li>
   <li>Make sure the navigation order is logical.</li>
   <li>Is keyboard focus apparent?</li>
  </ul>
  </td>
 </tr>
 <tr>
  <td>Form accessibility and usability</td>
  <td>
  <ul>
   <li>Click on the form label. If the field gains focus, it is properly labeled.</li>
   <li>Ensure that you can complete all forms without a mouse.</li>
   <li>Are error recovery mechanisms present and easy-to-use? [Source:[<a href="http://webaim.org/resources/evalquickref/" rel="nofollow">http://webaim.org/resources/evalquickref/</a>|<a href="http://webaim.org/resources/evalquickref/]]">http://webaim.org/resources/evalquickref/]]</a></li>
  </ul>
  </td>
 </tr>
</tbody>
</table>
<h6>Recommended further reading</h6>
<ul>
<li>Screen reader testing: focus on navigation, forms, and dynamic content. See the WebAIM tutorials on JAWS, the most popular screen reader (<a href="http://webaim.org/articles/jaws/" rel="nofollow">http://webaim.org/articles/jaws/</a> <a href="http://webaim.org/articles/jaws/" rel="nofollow">http://webaim.org/articles/jaws/</a>), and NVDA, a free and open-source screen reader (<a href="http://webaim.org/articles/nvda/" rel="nofollow">http://webaim.org/articles/nvda/</a> <a href="http://webaim.org/articles/nvda/" rel="nofollow">http://webaim.org/articles/nvda/</a> )</li>
<li>Cognitive walkthrough on early designs or prototypes (to identify any potential accessibility problems with the visual or interaction design) and finished code (to identify any potential accessibility problems with the coding of those designs), using the same assistive technologies, browser settings and operating system settings as your target audiences.</li>
<li>User testing with representative users from the website or application's disabled and older target audiences attempting to achieve tasks based on user goals. This should be conducted on early designs or prototypes, and finished code.</li>
<li>Manual validation against the WCAG 2.0 checklist (<a href="http://webaim.org/standards/wcag/checklist/" rel="nofollow">http://webaim.org/standards/wcag/checklist/</a> <a href="http://webaim.org/standards/wcag/checklist/" rel="nofollow">http://webaim.org/standards/wcag/checklist/</a>)</li>
<li>Automatic validation of HTML (<a href="http://validator.w3.org/" rel="nofollow">http://validator.w3.org/</a> <a href="http://validator.w3.org" rel="nofollow">http://validator.w3.org</a>) and CSS (<a href="http://jigsaw.w3.org/css-validator" rel="nofollow">http://jigsaw.w3.org/css-validator</a> <a href="http://jigsaw.w3.org/css-validator" rel="nofollow">http://jigsaw.w3.org/css-validator</a>)</li>
</ul>
<h6>To learn more about accessibility</h6>
<ul>
<li>British Computer Society's Accessible Technology: A guide for IT professionals (<a href="http://www.bcs.org/upload/pdf/accessible-technology.pdf" rel="nofollow">http://www.bcs.org/upload/pdf/accessible-technology.pdf</a> <a href="http://www.bcs.org/upload/pdf/accessible-technology.pdf" rel="nofollow">http://www.bcs.org/upload/pdf/accessible-technology.pdf</a>)</li>
<li>W3C's Web Accessibility Initiative (<a href="http://www.w3.org/WAI/" rel="nofollow">http://www.w3.org/WAI/</a> <a href="http://www.w3.org/WAI/" rel="nofollow">http://www.w3.org/WAI/</a>)</li>
<li>British Standards Institute BS 8878:2010 Web accessibility – Code of practice (<a href="http://shop.bsigroup.com/en/ProductDetail/?pid=000000000030180388" rel="nofollow">http://shop.bsigroup.com/en/ProductDetail/?pid=000000000030180388</a> <a href="http://shop.bsigroup.com/en/ProductDetail/?pid=000000000030180388" rel="nofollow">http://shop.bsigroup.com/en/ProductDetail/?pid=000000000030180388</a>) and video about the importance of accessibility standards (<a href="http://www.youtube.com/user/BSIBritishStandards#p/a/u/2/awldEoQ-aNQ" rel="nofollow">http://www.youtube.com/user/BSIBritishStandards#p/a/u/2/awldEoQ-aNQ</a> <a href="http://www.youtube.com/user/BSIBritishStandards#p/a/u/2/awldEoQ-aNQ" rel="nofollow">http://www.youtube.com/user/BSIBritishStandards#p/a/u/2/awldEoQ-aNQ</a>)</li>
<li>WebAIM (<a href="http://webaim.org/" rel="nofollow">http://webaim.org/</a> <a href="http://webaim.org/" rel="nofollow">http://webaim.org/</a>)</li>
<li>HTML5 accessibility (<a href="http://html5accessibility.com/" rel="nofollow">http://html5accessibility.com/</a> <a href="http://html5accessibility.com/" rel="nofollow">http://html5accessibility.com/</a>)</li>
<li>Cambridge University's Inclusive Design Toolkit (<a href="http://www.inclusivedesigntoolkit.com/" rel="nofollow">http://www.inclusivedesigntoolkit.com/</a> <a href="http://www.inclusivedesigntoolkit.com/" rel="nofollow">http://www.inclusivedesigntoolkit.com/</a>)</li>
</ul>
<h5>Downloads</h5>
<p><a href="//www.ebi.ac.uk/seqdb/confluence/download/attachments/16584495/accessibility_infographic.png?version=1&amp;modificationDate=1325852128000">Accessibility infographic</a> (see also here <a href="http://webaim.org/resources/designers/" rel="nofollow">http://webaim.org/resources/designers/</a>)</p>
