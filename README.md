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
							  
							  

							PAPER#3
Title: Automated Mobile Apps Testing From Visual Perspective

		"Authors"
(i) Fend Xue 
(School of Compuer Science and Engineering
Nothwestern Polytechnical University)

Conference Name: ISSTA (Sat 18-wed 22 july 2020).

Publish Date: Sat 18 Jul 2020 10:20 - 10:40 at Zoom - Doctoral Symposium

							"Summary"			
This research paper is all about the current implementation of 
automated mobile apps testing generally relies on internal program
information, such as readng code or GUI layout files.
This paper proposes an approach of automated mobile apps
testing from a completely visual perspective.

According to this research paper, unlike desktop software, mobile apps 
are usually large in number, diverse in type, with frequent version.
These features of mobile apps make testing more difficult, and it
is even more urgent to seek effective automated testing approaches to 
solve the current mobile apps testing.
 
In this paper the main automated testing techniques for mobile apps are
divided into the following three levels.

					'The first level techniques'
it includes follwing testing techniques:
(i) Script-based testing: it enables the automatic execution of test
cases defined by manually editing scripts. The test automation
frameworks, such as Espresso, XCTest, Appium, can
convert scripts into event streams and input AUT (App Under
Test) to simulate test execution.  

(ii) Record-replay testing: records the manually executed test
cases and then plays them back for reuse of test execution.
according to this research paper multiple tools are used to enhanse it,
(a) 'RERAN' captures the low-level event stream including GUI events and sensor events, 
then replays them for test execution.
(b) 'SARA' uses the proposed self-replay and adaptive replay mechanisms 
to achieve a high record-replay success rate for single and cross devices.
(c) 'LIRAT' combines image processing technology to achieve cross-platform 
record-replay testing 

					'The second level techniques'
According to this research paper this level  based on the first level
and focus more on automating test case generation and optimization.

it includes multiple types of testings:
(i) Random testing: it uses a random strategy to explore and test
apps. Although random, it automatically generates test inputs.
In this regards in paper a tool named Monkey, a native testing tool 
for Android, sends randomly selected GUI events and system events 
for testing.
 
(ii) Model-based testing: it automates testing by modeling apps
behavior and using model generated test cases.
i.e: MobiGUITAR: dynamically traverses AUT to build model and then
generates test cases. 
AMOGA: takes a static-dynamic approach to statically obtain the association 
between GUI elements and events from the source code, and then dynamically
and orderly explores AUT to generate model. 
These models are usually represented by a finite state machine.
	
(iii) Search-based testing: it uses leverages heuristic named algorithms 
to generate test cases and optimize test sequences. 
in this regards a scientist named AGRippin founded by genetic and hill 
climbing algorithms facilitates efficient and effective test case generation. 
another scientist named Sapienz introduces Pareto multi-objective approach to 
reach better test coverage with fewer test cases.

(iv) Transfer-based testing: it is dedicated to cross-platform and
cross-app use of test cases. TestMig uses similar comparison
of GUI controls and events to realize the migration of test cases
from IOS to Android. AppTestMigator and CraftDroid enable test cases 
to run on multiple apps with similar functions through matching the 
semantically similar of functions	

					'The Third level techniques'
according to this paper the third level techniques further introduce the 
following feature of learning:

(i) Traditional model learning-based testing:
it is based on the traditional finite state machine modeling to add a 
learning mechanism to achieve dynamic construction and generate onthe-fly
test inputs. In this regard a scientist named SwiftHand employs an improved L*
named algorithm to refine model during test execution. 
another scientist DroidBot dynamically updates the model through the adapter 
module and the brain module.

(ii) Deep learning-based testing:
it applies deep neural network technology to train an end-to-end 
test model. in this regrad a scientist named Humanoid 
designs a deep neural network model to generate human-like
inputs by learning user interaction with apps. 
DL-Droid proposed a deep learning system to detect malicious Android
apps through dynamic analysis using stateful input generation.

(iii) Reinforcement learning-based testing:
it develops a reinforcement learning mechanism for mobile apps to
automatically learn to obtain a test model by a trial-and-error
way. exploit Q-learning algorithm to explore AUT and
build test model.

All these automated testing techniques have significantly
promoted the development of mobile apps testing.	

					'Research Methodology' 
He used all  the above discussed methods as a Research Methodology that 
evaluates the following results. 

						   'RESULTS'
After reading throughly this research paper I concluded
follwing:
Based on computer vision technology, they propose an automated mobile 
apps testing approach from user perspective,which provides a new idea for the
current mobile apps testing automation.
This vision-based testing approach can provide a test capability similar to 
manual testing to a certain extent, thereby alleviating the contradiction 
between the huge test requirements of mobile apps and the relatively lack of
testers.

						   "THE END"
