- Template gallery
	- Nvim home
	  template:: Nvim Home
	  template-including-parent:: false
		- Created: <%today%>
		- [[Gratitude Journal]]
		- [[Lectio]]
		- [[SD-Journals]]
		- Diary
	- SD Journal
	  template:: SD Journal
	  template-including-parent:: false
	  collapsed:: true
		- *Reflection for Spiritual Direction Course*
		- 1. **I notice…(awareness)**:
		- 2. **I’m curious about… (attentive exploration)**:
		- 3. **I wonder how I can… (active response)**:
	- Capture web page
	  Template:: Capture
	  template-including-parent:: false
	  collapsed:: true
		- **<% time %>** [[quick capture]] :
	- Gratitude
	  Template:: Examen
	  template-including-parent:: false
	  collapsed:: true
		- <iframe src="https://indify.co/widgets/live/quotes/l2NrY3j6Da1wFFEXeu8l" style="height:275px;width:275px" title="Iframe Example"></iframe>
		- [[affirmations]] today:
		- What happened today:
		- What grateful for today:
		- What do better tomorrow:
	- Morning review
	  Template:: Morning review
	  template-including-parent:: true
	  collapsed:: true
		- <iframe src="https://indify.co/widgets/live/quotes/l2NrY3j6Da1wFFEXeu8l" style="height:275px;width:275px" title="Iframe Example"></iframe>
		- DONE Create solid schedule for today.  Look at your "TODOS" down below and make sure you are developing a good plan.
		- ### Critical Tasks for today
		- ### Notes
		- ### Working on
	- Daily Agenda
	  template:: Daily Agenda
	  template-including-parent:: false
	  collapsed:: true
		- <iframe src="https://indify.co/widgets/live/quotes/l2NrY3j6Da1wFFEXeu8l" style="height:275px;width:275px" title="Iframe Example"></iframe>
		- ---
		- ## WELCOME TO TODAY!!  YOU ARE AWESOME
		- DONE Create solid schedule for today.  Look at your "TODOS" down below and make sure you are developing a good plan.
		- ###  Critical Tasks for Today
		- ### Notes
	- Daily Template
	  template:: Morning Daily
	  template-including-parent:: false
	  collapsed:: true
		- ## Morning Pages
			- **A line about today**
			- **3 Things I'm Grateful For**
			- **2 [[affirmations]] **
		- ---
		- ## Daily Log
			-
	- # Weekly Review
	  template:: WeeklyReview
	  collapsed:: true
		- ### A line about this week
		- ### A line about today
		- ### What went well this week?
		- ### What needs improvement?
		- ### What could I have spent more or less time doing?
		- ### What am I grateful for this week?
		- ### What am I proud of this week?
		- ### What brought me joy this week?
		- ### What did I learn?
		- ### What #[[goals]] did I work towards?
		- ### What goals will I focus on next week?
	- Project page
	  template:: project page
	  template-including-parent:: false
	  collapsed:: true
		- tags:: project page
		  icon:: 📂
		-
		- ### Project Meta
			- DOING #project <% current page %>
			- query-table:: false
			- query-table:: false
		- ### Notes
	- ### Meetings
	  collapsed:: true
		- date:: 
		  template:: Meetings 👥
		  people::
		  collapsed:: true
			- #+BEGIN_QUERY
			  {:title [:b "Meeting referencing 🔎" ]
			   :query  [:find (pull ?b [*])
			   :in $ ?end ?daysback
			   :where
			   [?b :block/path-refs ?ref]
			  (not [?b :block/page ?page]           ;<--- :block/page is an id,
			   [?page :block/name "meetings"])       ;     not a string
			  [?ref :block/name "meetings"]
			   [?b :block/created-at ?v]
			   [(* ?daysback 60 60 24 1000) ?range]
			   [(- ?end ?range) ?period]
			   [(>= ?v ?period)]
			   [(< ?v ?end)]
			   ]
			   :inputs [:end-of-today-ms 8]
			   :result-transform (fn [result]
			                (sort-by (fn [h]
			                           (get h :block/updated-at)) result))
			  }
			  #+END_QUERY
			- ## **To ask:**
			- ## To-Do
			- ## Key points
		- 07:00
		- 08:00
		- ### Active Projects
			- [[Project 1]]
			- [[Project 2]]
			-
		- ### What did I do for ME today?
			-
	- Books
	  collapsed:: true
		- New Book
		  template:: new book
		  template-including-parent:: false
		  collapsed:: true
			- type:: book
			  status:: to-do
			  author:: 
			  series:: 
			  started:: 
			  finished:: 
			  rating::
			  recommended-by::
			- # Plot Points
			- # Highlights
			- # Lowlights
			- # Insights
		- Book 
		  template:: book
		  template-including-parent:: false
		  collapsed:: true
			- type:: book
			  status:: to-do
			  author:: 
			  series:: 
			  started:: 
			  finished:: 
			  rating::
			  recommended-by::
			- # Plot Points
			- # Highlights
			- # Lowlights
			- # Insights
		- Book review
		  Template:: Book Review
		  alias:: book name
		  author:: [[author]]
		  tags:: fiction
		  type:: book
		  lang:: English
		  status:: reading
		  cover:: ![cover](https://img1.doubanio.com/view/subject/l/public/s29126537.jpg){:height 153, :width 100}
		  icon:: 📚
	- Identifying Trailhead #spiritual-direction 
	  Template:: Trailhead
	  collapsed:: true
		- Choose a trailhead that you are interested in exploring. If it is not current in your life, take a moment to close your eyes and imagine you are in that situation now. Ask yourself, “What parts are here as I connect with this situation or look at this issue?” List the parts at this trailhead one by one as they arise. For each part, write as much of the following information as you can. Remember, you haven't fully explored these Parts, so don't be concerned if you don’t know much about them. Just fill in what you know. You can add more information later.
			- Name of part:
			- What the part feels emotionally:
			- What it looks like:
			- What it feels like in your body and where:
			- What the part says:
			  id:: 66008f52-1348-4fc1-bef2-d344ca66c880
			- How it makes you behave:
			- What it wants: