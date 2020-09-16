# Introduction

&lt;!-- --&gt;&lt;!--  
function msoCommentShow\(anchor\_id, com\_id\)  
{  
	if\(msoBrowserCheck\(\)\)   
		{  
		c = document.all\(com\_id\);  
		a = document.all\(anchor\_id\);  
		if \(null != c && null == c.length && null != a && null == a.length\)  
			{  
			var cw = c.offsetWidth;  
			var ch = c.offsetHeight;  
			var aw = a.offsetWidth;  
			var ah = a.offsetHeight;  
			var x  = a.offsetLeft;  
			var y  = a.offsetTop;  
			var el = a;  
			while \(el.tagName != "BODY"\)   
				{  
				el = el.offsetParent;  
				x = x + el.offsetLeft;  
				y = y + el.offsetTop;  
				}  
			var bw = document.body.clientWidth;  
			var bh = document.body.clientHeight;  
			var bsl = document.body.scrollLeft;  
			var bst = document.body.scrollTop;  
			if \(x + cw + ah / 2 &gt; bw + bsl && x + aw - ah / 2 - cw &gt;= bsl \)   
				{ c.style.left = x + aw - ah / 2 - cw; }  
			else   
				{ c.style.left = x + ah / 2; }  
			if \(y + ch + ah / 2 &gt; bh + bst && y + ah / 2 - ch &gt;= bst \)   
				{ c.style.top = y + ah / 2 - ch; }  
			else   
				{ c.style.top = y + ah / 2; }  
			c.style.visibility = "visible";  
}	}	}  
function msoCommentHide\(com\_id\)   
{  
	if\(msoBrowserCheck\(\)\)  
		{  
		c = document.all\(com\_id\);  
		if \(null != c && null == c.length\)  
		{  
		c.style.visibility = "hidden";  
		c.style.left = -1000;  
		c.style.top = -1000;  
		} }   
}  
function msoBrowserCheck\(\)  
{  
	ms = navigator.appVersion.indexOf\("MSIE"\);  
	vers = navigator.appVersion.substring\(ms + 5, ms + 6\);  
	ie4 = \(ms &gt; 0\) && \(parseInt\(vers\) &gt;= 4\);  
	return ie4;  
}  
if \(msoBrowserCheck\(\)\)  
{  
	document.styleSheets.dynCom.addRule\(".msocomanchor","background: infobackground"\);  
	document.styleSheets.dynCom.addRule\(".msocomoff","display: none"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","visibility: hidden"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","position: absolute"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","top: -1000"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","left: -1000"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","width: 33%"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","background: infobackground"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","color: infotext"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","border-top: 1pt solid threedlightshadow"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","border-right: 2pt solid threedshadow"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","border-bottom: 2pt solid threedshadow"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","border-left: 1pt solid threedlightshadow"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","padding: 3pt 3pt 3pt 3pt"\);  
	document.styleSheets.dynCom.addRule\(".msocomtxt","z-index: 100"\);  
}  
// --&gt;  
&lt;!--  
 /\* Font Definitions \*/  
 @font-face  
	{font-family:"Cambria Math";  
	panose-1:2 4 5 3 5 4 6 3 2 4;  
	mso-font-charset:0;  
	mso-generic-font-family:roman;  
	mso-font-pitch:variable;  
	mso-font-signature:3 0 0 0 1 0;}  
@font-face  
	{font-family:Calibri;  
	panose-1:2 15 5 2 2 2 4 3 2 4;  
	mso-font-charset:0;  
	mso-generic-font-family:swiss;  
	mso-font-pitch:variable;  
	mso-font-signature:-469750017 -1073732485 9 0 511 0;}  
@font-face  
	{font-family:"Noto Sans Symbols";  
	mso-font-alt:Calibri;  
	mso-font-charset:0;  
	mso-generic-font-family:auto;  
	mso-font-pitch:auto;  
	mso-font-signature:0 0 0 0 0 0;}  
 /\* Style Definitions \*/  
 p.MsoNormal, li.MsoNormal, div.MsoNormal  
	{mso-style-unhide:no;  
	mso-style-qformat:yes;  
	mso-style-parent:"";  
	margin-top:0cm;  
	margin-right:0cm;  
	margin-bottom:8.0pt;  
	margin-left:0cm;  
	text-align:justify;  
	line-height:107%;  
	mso-pagination:widow-orphan;  
	font-size:11.0pt;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:Calibri;  
	mso-fareast-theme-font:minor-latin;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:Arial;  
	mso-bidi-theme-font:minor-bidi;}  
p.MsoCommentText, li.MsoCommentText, div.MsoCommentText  
	{mso-style-noshow:yes;  
	mso-style-priority:99;  
	mso-style-link:"Comment Text Char";  
	margin-top:0cm;  
	margin-right:0cm;  
	margin-bottom:8.0pt;  
	margin-left:0cm;  
	text-align:justify;  
	mso-pagination:widow-orphan;  
	font-size:10.0pt;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:Calibri;  
	mso-fareast-theme-font:minor-latin;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:Arial;  
	mso-bidi-theme-font:minor-bidi;}  
span.MsoCommentReference  
	{mso-style-noshow:yes;  
	mso-style-priority:99;  
	mso-ansi-font-size:8.0pt;  
	mso-bidi-font-size:8.0pt;}  
a:link, span.MsoHyperlink  
	{mso-style-priority:99;  
	color:\#0563C1;  
	mso-themecolor:hyperlink;  
	text-decoration:underline;  
	text-underline:single;}  
a:visited, span.MsoHyperlinkFollowed  
	{mso-style-noshow:yes;  
	mso-style-priority:99;  
	color:\#954F72;  
	mso-themecolor:followedhyperlink;  
	text-decoration:underline;  
	text-underline:single;}  
span.CommentTextChar  
	{mso-style-name:"Comment Text Char";  
	mso-style-noshow:yes;  
	mso-style-priority:99;  
	mso-style-unhide:no;  
	mso-style-locked:yes;  
	mso-style-link:"Comment Text";  
	mso-ansi-font-size:10.0pt;  
	mso-bidi-font-size:10.0pt;}  
.MsoChpDefault  
	{mso-style-type:export-only;  
	mso-default-props:yes;  
	font-family:"Calibri",sans-serif;  
	mso-ascii-font-family:Calibri;  
	mso-ascii-theme-font:minor-latin;  
	mso-fareast-font-family:Calibri;  
	mso-fareast-theme-font:minor-latin;  
	mso-hansi-font-family:Calibri;  
	mso-hansi-theme-font:minor-latin;  
	mso-bidi-font-family:Arial;  
	mso-bidi-theme-font:minor-bidi;}  
.MsoPapDefault  
	{mso-style-type:export-only;  
	margin-bottom:8.0pt;  
	text-align:justify;  
	line-height:107%;}  
@page WordSection1  
	{size:612.0pt 792.0pt;  
	margin:72.0pt 72.0pt 72.0pt 72.0pt;  
	mso-header-margin:36.0pt;  
	mso-footer-margin:36.0pt;  
	mso-paper-source:0;}  
div.WordSection1  
	{page:WordSection1;}  
 /\* List Definitions \*/  
 @list l0  
	{mso-list-id:471291547;  
	mso-list-template-ids:1766208184;}  
@list l0:level1  
	{mso-level-number-format:bullet;  
	mso-level-text:-;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:Arial;  
	mso-fareast-font-family:Arial;  
	mso-hansi-font-family:Arial;  
	mso-bidi-font-family:Arial;}  
@list l0:level2  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Courier New";  
	mso-fareast-font-family:"Courier New";  
	mso-hansi-font-family:"Courier New";  
	mso-bidi-font-family:"Courier New";}  
@list l0:level3  
	{mso-level-number-format:bullet;  
	mso-level-text:▪;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l0:level4  
	{mso-level-number-format:bullet;  
	mso-level-text:●;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l0:level5  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Courier New";  
	mso-fareast-font-family:"Courier New";  
	mso-hansi-font-family:"Courier New";  
	mso-bidi-font-family:"Courier New";}  
@list l0:level6  
	{mso-level-number-format:bullet;  
	mso-level-text:▪;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l0:level7  
	{mso-level-number-format:bullet;  
	mso-level-text:●;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l0:level8  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Courier New";  
	mso-fareast-font-family:"Courier New";  
	mso-hansi-font-family:"Courier New";  
	mso-bidi-font-family:"Courier New";}  
@list l0:level9  
	{mso-level-number-format:bullet;  
	mso-level-text:▪;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l1  
	{mso-list-id:1017390847;  
	mso-list-template-ids:1606082076;}  
@list l1:level1  
	{mso-level-number-format:bullet;  
	mso-level-text:-;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:Arial;  
	mso-fareast-font-family:Arial;  
	mso-hansi-font-family:Arial;  
	mso-bidi-font-family:Arial;}  
@list l1:level2  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Courier New";  
	mso-fareast-font-family:"Courier New";  
	mso-hansi-font-family:"Courier New";  
	mso-bidi-font-family:"Courier New";}  
@list l1:level3  
	{mso-level-number-format:bullet;  
	mso-level-text:▪;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l1:level4  
	{mso-level-number-format:bullet;  
	mso-level-text:●;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l1:level5  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Courier New";  
	mso-fareast-font-family:"Courier New";  
	mso-hansi-font-family:"Courier New";  
	mso-bidi-font-family:"Courier New";}  
@list l1:level6  
	{mso-level-number-format:bullet;  
	mso-level-text:▪;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l1:level7  
	{mso-level-number-format:bullet;  
	mso-level-text:●;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
@list l1:level8  
	{mso-level-number-format:bullet;  
	mso-level-text:o;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Courier New";  
	mso-fareast-font-family:"Courier New";  
	mso-hansi-font-family:"Courier New";  
	mso-bidi-font-family:"Courier New";}  
@list l1:level9  
	{mso-level-number-format:bullet;  
	mso-level-text:▪;  
	mso-level-tab-stop:none;  
	mso-level-number-position:left;  
	text-indent:-18.0pt;  
	mso-ascii-font-family:"Noto Sans Symbols";  
	mso-fareast-font-family:"Noto Sans Symbols";  
	mso-hansi-font-family:"Noto Sans Symbols";  
	mso-bidi-font-family:"Noto Sans Symbols";}  
ol  
	{margin-bottom:0cm;}  
ul  
	{margin-bottom:0cm;}  
--&gt;  


The InforMEA Initiative purchased the PoolParty software in its “Enterprise Server” version which offers thesaurus management and automated tagging of content on the InforMEA level as well as for individual MEAs.

PoolParty main purposes are:

-       Maintenance and enhancement of vocabularies, in particular the InforMEA Thesaurus, also known as Law and Environment Ontology \(LEO\), and all affiliated vocabularies from individual MEAs

-       Administrate mappings between keywords used at MEA level to the common InforMEA Thesaurus

-       Administrate mappings between keywords of external information resources \(e.g. ECOLEX\) that feed or are harvested into InforMEA Portal

-       Administrate any other metadata and mappings relevant for faceted search in InforMEA portal \(e.g. Document types\)

-       Provide auto-tagging features in InforMEA back end and/or at MEA level

-       Thesaurus governance editorial workflow supporting a multi-stakeholder approach

-       Provide a glossary of concepts and definitions relevant to environmental law and enhanced with translations in UN languages for reuse in affiliated/envisaged information systems and portals

-       Offer a potential linked open data resource that can be linked to global initiatives such as SDG process

PoolParty provides the basic functionalities of thesaurus management and a consistent approach of auto-tagging. Based on semantic technology, it opens up to further developments in information technology, such as artificial intelligence in context of text mining, and linked open data/big data potentials.

The acquired PoolParty license includes two servers: one test server for staging and development, and one production server for live use. There are no limits on the number of users or projects\[JH1\] \[SR2\] .  

The test server allows to maintain/develop vocabularies and train the extraction models independent from production server and requires a later synchronization procedure to update the live server.

If you are a person without experience in knowledge management or unfamiliar with PoolParty, it is highly recommended that you take at least a quick look at the chapter "PoolParty and Semantic Web Jargon" at the end of this document; otherwise, you can go directly to the next chapter "Best practices and suggestions", where we have summarized, according to our experience,  the main topics you need to take into account to start working with PoolParty.

Nonetheless, feel free to go deeper inside the subject. Please use the following options:

-       Free tutorial provided by PoolParty at [https://www.PoolParty.biz/academy](https://www.poolparty.biz/academy)

-       Comprehensive introduction at [https://help.PoolParty.biz/pp7/PoolParty-quick-start-guide](https://help.poolparty.biz/pp7/poolparty-quick-start-guide)

-       Individual training in the context of expected editorial work with InforMEA team

Besides, the PoolParty manual is linked to the interface and accessible online. It provides screenshots, tutorials and explanations per chapter. Aspects can be easily retrieved with full-text search functionality that guides you to the respective chapter.

For easy reference, this document includes links to the respective chapters within the manual. For access to PoolParty, please contact Kelly Kabiru and indicate relevant project and editorial work you plan to do.

