# WebEngineering Module, Graded Exercise

## Commit Proposal

Matriculation Number: <16-967-473>

Mein Ziel ist es eine Website zu entwickeln über meine Fähigkeiten als Informatiker, sowie jene als Person,
also eine Art Online Lebenslauf mit allem was ich bisher im Studium oder vorher gelernt habe + die Möglichkeit
den Lebenslauf in Zukunft zu ergänzen mit dem was ich noch lernen werden.

Die Idee dahinter ist, fall ich mich in Zukunft beginne zu bewerben, habe ich immer etwas in der Hand um
vorzeigen zu können. Das Ziel ist es auch diese Seite nicht einfach so stehen zu lassen, sondern immer wieder
zu verbessern und neu gelernte Methoden damit umzusetzen. Sozusagen ein Projekt welches mich über lange Zeit
begleiten wird.

Wie genau und mit welchen Funktionalitäten ich dieses Projekt umsetzten möchte, kann ich noch nicht genau sagen, 
jedoch werde habe ich die nächsten Tage Zeit mir genauere Gedanken zu machen.

## Project confirmation

confirmed.

Ich nehme das mal auf unter dem Namen "online-cv".
Das wird sicher eine sehr nützliche Anwendung.


## Project delivery <to be filled by student>

Open the CVHome.html File

Um noch Funktionen zu implementieren hat mir die Zeit nicht genügt.
Aber bin sehr zufrieden mit dem Ergebnis.


## Project grading 

Description: mostly valid HTML and good use of semantic tags.
One issue: Bad value http://www.w3.org/1999/html for the attribute xmlns (only http://www.w3.org/1999/xhtml permitted here).
Since the project is a static web page, the only thing that can "work" is
navigation and links to external resources. Links to "contact" do not work as there is not contact page.
Links to facebook, linkedin, twitter do not link directly to the authors page as intended (I assume) but the
require logins, which does not make a lot of sense to me in this context.
Links to images are broken (respective directory might have been forgotton to git add, push).
Some content is blind text.

Functionality: navigation.

Engineering:
Git log is sparse but otherwise ok.
No tests. HTML has validity issues with regard to nesting elements (p inside h4 for example).
Comments in html and css ok.
Some duplication between e.g. Home and Resumée.

I award an extra point for the creative use of CSS.

Despite the nice appearance of Home and Resumée, the overall result lacks engineering and 
is not enough for a passing grade.
You could have easily scored much better by providing tests for the navigation, making sure the 
links to external resources and images work, and validating the html.

Total grade: 3.5
