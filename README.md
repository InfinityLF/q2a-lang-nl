q2a-lang-nl
===========

Dutch translation Question2Answer

http://www.question2answer.org

Based on prior translations of R. van der Veen

Installatie instructies (in Dutch)
===========

1. Plaats het mapje 'nl' in de map /qa-lang
2. Selecteer NL als taal in de admin-interface onder 'general'

Quick fix for the Snow v1.3 theme
===========
A quick fix for the voting boxes being too small due to the Dutch language. Make sure you have voting on questions enabled on the question page itself only.

Add the following to the bottom of styles.css:

.qa-q-view .qa-voting {
	height:80px;
	margin-bottom:5px;
}
.qa-a-list-item .qa-voting {
	height:80px;
	margin-bottom:5px;
}
.qa-q-view .qa-netvote-count-data {
	font-size:28px;
	margin-top:20px;
}
.qa-a-list-item .qa-netvote-count-data {
	font-size:28px;
	margin-top:20px;
}
.qa-a-selection {
	top:110px;
}
