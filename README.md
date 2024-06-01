This code followed this tutorial: https://www.youtube.com/watch?v=P1PCS6puIyA

NOTE: The html.json user snippet template is within the Visual Studio code IDE. I was unable to upload that separately without errors. The code for that is below:

{

	"Flask Tutorial: template extending layout.html": {
		"prefix": "flextlayout",
		"body": [
			"{% extends \"layout.html\" %}",
			"{% block title %}",
			"$0",
			"{% endblock %}",
			"{% block content %}",
			"{% endblock %}"
		],
	
		"description": "Boilerplate template that extends layout.html"
	},
}
