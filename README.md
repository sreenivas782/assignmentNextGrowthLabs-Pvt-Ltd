# assignmentNextGrowthLabs-Pvt-Ltd

--------Problem Set I - Regex------

'''
Problem Set I - Regex
Write a regex to extract all the numbers with orange color background from the below text in italics (Output should be a list).
{"orders":[{"id":1},{"id":2},{"id":3},{"id":4},{"id":5},{"id":6},{"id":7},{"id":8},{"id":9},{"id":10},{"id":11},{"id":648},{"id":649},{"id":650},{"id":651},{"id":652},{"id":653}],"errors":[{"code":3,"message":"[PHP Warning #2] count(): Parameter must be an array or an object that implements Countable (153)"}]}

'''

import re

str = '{"orders":[{"id":1},{"id":2},{"id":3},{"id":4},{"id":5},{"id":6},{"id":7},{"id":8},{"id":9},{"id":10},{"id":11},{"id":648},{"id":649},{"id":650},{"id":651},{"id":652},{"id":653}],"errors":[{"code":3,"message":"[PHP Warning #2]count(): Parameter must be an array or an object that implements Countable(153)"}]}'
#search using regex
x = re.findall(':[0-9]+', str)
print([s.strip(':') for s in x])
 
 
 
 OUT PUT ====  ['1', '2', '3', '4', '5', '6', '7', '8', '9', '10', '11', '648', '649', '650', '651', '652', '653', '3']
 
 
 
 -------Problem Set 3--------------------
A----
Basically Long-term scheduling,Medium-term scheduling,Short-term scheduling,Dispatcher


B------
Django:
As a full-stack web framework, Django is best suited for developing large and complex web applications, while Flask is a lightweight, extensible framework that allows you to develop small web applications. Django is also called a ‘framework for fussbudgets with deadlines’ as its framework encourages rapid development and clean, pragmatic design. The agile development process of the framework aims solely on providing quality with rapidness and efficiency. 
Companies Using Django:
Instagram,Coursera,Mozilla,Pinterest,National Geographic,Spotify,Udemy,Zapier, etc.
feature of django:
Fast,Adaptable,Scalable,Portable

Flask:
Flask is also a Python-based microframework that is used for web application development. It was introduced by Armin Ronacher in the year 2011 as a trial method of joining two solutions i.e., Werkzeug (a server framework) and Jinja2 (a template library).Flask is categorized as a micro framework because it does not depend on external libraries to perform the tasks of a framework. It has its tools, technologies, and libraries to support the functionalities of web application development.
companies Using Flask:
Netflix,Airbnb,MIT,Reddit,Lyft,Zillow,Mozilla,MailGui, etc.
features of Flask:
Lightweight,Independent,Integrated Unit Testing,Secure Cookies,Compatible,Flexible and Scalable
Django vs Flask

Flask renders full control and is highly suitable for small projects that necessitate experimentation. 
Django is complicated and requires vast knowledge but it stands out as one of the best frameworks for building sophisticated applications. 








