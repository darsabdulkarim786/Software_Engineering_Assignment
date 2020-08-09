# Software_Engineering_Assignment

							 PAPER#1
Title: Testing of Mobile Applications in the wild:
A large-Scale Empirical Study on Andriod Apps.

	   	"Authors"
(i) Fabianco Pecorelli 
(ii) Gemma Catolino
(iii) Filomena Ferruci
(iv) Andrea De Lucia 
(v) Fabio Palomba

Conference Name:International Conference on Program Comprehension (13-15 July 2020).

Publish Date: Mon 13 Jul 2020 15:00 - 15:12 at ICPC - Session 1: Tests Chair(s): Dario Di Nucci

							          "Summary"			
This research paper is all about the testing methods 
of mobile applications, a large-scale empirical study on
the design and effectiveness of test cases manually written
by developers and their goal of the empirical study is to check quality,
and effectiveness of test cases written by mobile developers.
According to this paper Software testing is one of the most relevant and 
well-established methods to control for source code quality and to 
enable the understandability of the functionalities being implemented 
in a system. This activity is even more pressing in the context of
mobile computing, where continuous releases of an app have
the high risk of introducing defects and decrease software reliability.
At the same time, the unique characteristics of mobile apps.
In this research paper an example is elaborated by researcher that 
the fact that users can interact via touch-screen and a number of
sensors, present brand new challenges for developers when testing
the source code of their applications.	
Their empirical study clearly reports that mobile applications are
not sufficiently tested, while GUI-related classes and storage of the
considered apps remain mostly untested. As for the test code design, 
They discovered that most of them are affected by some form of test methods, 
Finally, all the effectiveness measured are low, meaning that tests are likely
to have a poor fault detection capability.


					      'Research Methodology' 
They started to accumulate informtion that are gathered in 
this research paper from GITHUB repositories of open source apps,
clonned apps locally and performed an exhaustive search through their 
packages in order to extract classes having “Test” as prefix or suffix—note 
that search to classes explicitly using the JUnit framework.

						          'RESULTS'
In this paper, researcher investigated the characteristics of test suites 
written by developers of mobile applications under three perspectives:
(1) whether and to what extent these apps are tested and which kind of 
    tests are developed.
(2) what is the design quality of the test suites, in terms of code.
(3) what is the effectiveness of tests, the main results of this research 
    paper highlight that 59% of the considered apps have at least one test suite.
    
						          "THE END"
							  
							  
							  
       							PAPER#2

Title: A Human Study of Comprehension and Code Summarization.

		"Authors"
(i) Sean Stapleton
(ii) Yashmeet Gambhir
(iii) Alexander LeClair
(iv) Zachary Eberhart
(v) Westly Weimer
(vi) Kevin Leach
(vii) Yu Huang

Conference Name: International Conference on Program Comprehension (13-15 July 2020).

Publish Date: Tue 14 Jul 2020 02:00 - 02:15 at ICPC - Session 4: Summalization Chair(s): Venera Arnaoudova

							"Summary"
This research paper is all about the comprehension of human being
of source code provided written by other developers, or developed 
using other styles,Source code comments play an invaluable role in
facilitating program comprehension, Short, descriptive summary comments 
preceding subroutines have been shown to significantly improve programmers’ 
ability to answer questions about source code.

Their recent work has shown that developers consider comments to be the most important 
documentation artifacts for software maintenance tasks, other than the source code itself. 
Welldocumented source code manifestly affects developer productivity
both when investigating an existing software project for the first
time and when maintaining existing large codebases.

They included that recent advances in deep learning led to summary generation techniques
that convert functions or methods to simple english strings that describes the code behaviour.
This paper contained information about techniques for summarization 
that are assessed using BLEU score, which measure natural language 
properties in translational models and second is ROUGE score, which
measure overlap with human written text. 

According to this paper these techniques failed to capture that how machine-generated code
summaries actually effect human comprehension or developer productivity .
for getting actual results they conducted a human study involving
both university student and professional developers, in number they 
were n=45, they assigend java methods and summaries and asked for establishing
programs. In addition, participants completed coding tasks given
summaries as specification. for a given method, some participents
were shown human-written text and some were shown machine-generated text.

They found that participants performed significantly better using
human-written summaries versus machine-generated summaries, they also
found that participants performance showed no correlation with the BLEU and ROUGE
techniques to assess the quality of machine-generated summaries.

These resluts realized the researchers for revised metrics to assessed
and guide automatic summarization techniques.

					 'Research Methodology' 
Their methodology shwon is research paper for measuring the impact of code summaries on developer productivity. 
They designed IRB-approved human study involving 45 undergraduate and graduate computer science 
students and industrial software developers.
Participants were asked to complete two tasks in an anonymous
online survey. First, they were shown methods written in Java alongside corresponding summaries 
and asked to answer comprehension questions. 
Second, participants were given partially-completed Java
classes including summaries for all the methods in these classes and
asked to complete a method in the class with respect to a held-out
test suite. By measuring time taken and answer accuracy, they can
develop a model of developer comprehension as a function of type
and quality of the code summary used.

							'Results'
They got finally, first, that human-written summaries help developers comprehend code 
significantly better than do machine-generated summaries. Second, 
developer perception of summary quality, whether human-written or machine-generated, 
did not significantly correlate with developer comprehension—developers cannot assess
which summaries are most helpful.
They found that BLEU and ROUGE scores were significantly uncorrelated (i.e., ρ = 0.151
with p = 0.0004 for ROUGE and ρ = 0.140 with p = 0.0008 for
BLEU) with developer comprehension—developers do not benefit from summaries with higher-valued BLEU or ROUGE scores.
This indicates a need for new metrics for measuring automatic
summarization techniques.
					  
						    "THE END"							  
							  
							  
