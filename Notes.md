# Three lesson learned:
- Choose dependency wisely
- Avoid doing it all yourself, all at once(Leverage skills and resources of the enterprise)
- Longevity doesn't come easy

##Enterprise Software: 9 Hallmarks of Enterprise Software
- Used by a business
	- Business or pleasure | 
- Fundamentally unique
	- Tailor made | Organizational fignerprint | Enterprise versus off-the-shelf
- Well specified users
	- Small, captive user group | Hinders development iteration | Contrast to consumer markets
- Strick runtime requirements
	- High performance | High reliability | High Scalibility | Emulated in consumer space
- Part of a complex system
	- Highly factored ex: paypal has 2000+ packages, 3000+ service endpoints, 20k service objects
- Design permanence
	- Long or indefinite lifespans | Low or no maintainence | Technical Debt or technological conservatism
- Legacy integration
	- High degree of interoperability | Software and process (Codebase, Policies and Standards)
	- software or hardware that has been nominally superseded but difficult to replace becasue of its wide use.
- Negotiated timelines
	- Large orgaizations run on calendar
	- Large systems run on deadlines
	- Software development schedules
		- Always unpredictable
		- Always accelerating
- Specilization and support
	- Developed by one team or developer | Tested by another | Deployed by third | Operated by third | Supported by sixth

##Matrix: a common organizational structure in which workers report to multiple managers,
ex: a development and product manager. Matrix organizations groups people by specialty,
fostering political intrigue and bureaucratic cliche.


Enterprise is not binary.
The more hallmarks present, the more enterprise the software.
Enterprise does not mean good, nor bad. Hallmarks are stack-agnostic.
It could be good and it's important to recognize it.


What is Python ? Perspective for the organizational

def python():
 - Language
	- Clear and concise
	- Easy to learn and teach
	- Language of choice
 - Runtime
	- CPython offers a lot to engineers and operators:
	- Consistency adn predictability
	- Wide compatibility with C libararies
	- Embeddability and low memory footpritn
	- Exposure of underlying operating systems 
	- pypy (performance focused) CPython (most common) Jpython 
 - Platform
	- Huge open source library
	- organizationally neutral
	- over 100k packages
	- 850k python repositories on github
Youtube/Spotify (based on python)


What Python is not ?

Myths are the inevitable challenge of any brand:
- Big | Disruptive | grassroots | Wide reaching | old enough 

FUD: Fear, uncertainty and doubt, usually evoked intentionally in 
order to put a competitor at a disadvantage.

- Python is not new
- Python is a general purpose language

Python is not hard to scale: youtube/dropbox/yelp/reddit/paypal


When to use python ?

- 10:00 - 5:00 pm

common motivations to adopt python
- Engineering autonomy
	- chosen by researchers and develpoers
	- Not usually by managers or directors
	- Yes, ig python success are known
	- Few big companies sell python
	- Organizational neutrality is double edged
	
- Small and understaffed teams
	- 10x fewer lines than C++
	- 10-20x fewer lines than Java

- 2-4x faster development times 

- Career Development
	- Enterprise moves slowly
	- Market moves quickly
	
	
- Legacy Designs
 - large organizations use python
 - Autonomy is great, but so is relevance

- PayPal Python Applications
	- Services (HTTP/REST) Binary protocols(propietary but faster)
	- Administrative applications ( pricing, payments in core engine)
	- Machine local services (daemons/agents)
	- Batch processors ( thousand of batches and interacts with external FI)
	- Development and debugging tools
	- Architecture and desing utilities
	- Operational automation
	
Python is not yet enterprise-ready on:
 - client-side web
 - client-side mobile
 
There is no native Python on these platforms, so it isremarkable that there is as much usage as there is.
KIBY: client side mobile / web. No python running on client.
Where there is python, use python.


Architecture and Design: To prepare for a professinoal project
Theory and Practice: (between is called software architecture)

Designing architectures:
 - Gathering requirements
 - Researching environments
 - Choosing Dependencies
Discovery more than invention
Careful, deliberate communication

Software architecture is more about discovery than invention, it's about
what your constraints are, what you are trying to build and choosing the 
right tools to achieve that task.

We need careful deliberate communication on top of that to achive that.


EspyMetrics:
- Pure-python analytics application
- Open-source
design.rst

were there more mac users/pc users. 

Note:
- Describe your constraints.
- Prune the decision tree.
- Discover your architecture.




	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
