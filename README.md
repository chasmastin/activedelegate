slingshot
=========

Application to make votes of elected officials directly correlate to the desires of their constituency. 

Elected officials who decide to use Slingshot are making a commitment that all of their votes on legislation 
will directly reflect the results of real-time polling done by the Slingshot app.  Slingshot is party-neutral 
and ideology-neutral.  To use Slingshot, a politician simply has to sign a pledge (TODO create pledge statement) 
that states they will follow the results of the app, and if they do not they cannot use the app to help govern.  

Some general design principals of the app:

1.  Authenticity:  Slingshot will require that each participant validate themselves as a real person.  
While voting record and position can remain anonymous, this approach to governance will only function 
if there is 100% trust in the validity of the polling.

2.  Slingshot makes politicians more into communicators of meaning of legislation to their constituents.   
The final decision will be in the hands of the constituents.  Thus, the app must create a vibrant discussion 
community around legislation and allow for direct communication from politicians to people.

3.  The app must be as freely accessible as possible via the web and mobile devices.

4.  Because very few people will be able to research and vote every day on every issue, one of the fundamental 
design principals is "autopolling", which can be optionally enabled.  Once enabled, the app will take your
preferences on social and economic issues and cast a vote for you based on user-analysis of a given piece 
of legislation.     

An example of the autopolling process:

A politician is elected on a platform that she will use the Slingshot app to govern.  Her constituents are 
all given an account in the system, and after authenticating they can log into the Slingshot site or download 
the app.  Once there, they are initially asked a series of questions that ascertain their position on a variety 
of issues.  Let's say, for the sake of this example, that a constituent determines that they are resolutely 
pro-life, no matter what.  So, a piece of legislation comes through the elected body that the users of the 
app determine, after research and presentation by the politician, that is pro-life.  If the constituent has 
determined they are pro-life, the system would automatically cast a vote in support of the bill for the constituent
if they have enabled and agreed to the terms of autopolling.


The plan is to build the system, refine it over the next year, and run candidates starting in 2013 or 2014.  
My initial inclination is to use Ruby on Rails for the web framework, and I believe both a webapp version 
(Sencha Touch?) and native iOS and Android versions will be build.  No matter what, this has to be 
Open Source Government.  This idea has been bouncing around my head for several years and I believe that if
properly executed it could address many of the seemingly calcified issues facing our government in the 
United States, and Representative Democracies in general.  

If you would like to help out please contact me at chas@whistlebox.com. 

Slingshot is just a working development title by the way, the actual app will have a different brand when 
presented by candidates.  
