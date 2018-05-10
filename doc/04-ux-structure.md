UX Fundamentals: The Structure Plane
---

### Defining Structure
- Structure defines how users get to a given screen and where they can go when they're done
- Structure also defines categories of information
- Created by interaction design, which presents information in a way people can interact with it
- Also created by information architect - organization, labeling, search, and navigation systems.
- Good structure organizes information in a way that provides intuitive access to content.  (intuitive => use it once, learn it rapidly, and remember it forever. ie. "single-trial learning")

### Interaction Design
- Interaction design defines the structure and behavior of interactive systems
- It creates meaningful relationships between people and the things they use
- It effectively communicates interactivity and functionality
- It reveals simple and complex workflows
- It informs users about state changes
- When done right, it prevents user error

### Five Essential Principles of Interaction Design
- Consistent - use visual conventions and common components across the site   
  - Behavior - components should have consistent appearance and behavior.  (ie. navigation, buttons, controls, icons, alerts, etc.)
  - Voice - labels, terms, content, and imagery should have a stable, consistent style.  
  - This leverages the visitor's prior experience.  
  - Design patterns are reusable solutions to recurring problems.
  - Content may change but interaction and process should stay the same.
  - Make actions and results consistent and predictable.
- Visible
  - Discoverability shouldn't involve luck or chance
  - People should be able to tell that an opportunity to interact is available.
  - Use content hinting - avoid "false bottoms" when more content and interactivity exists below the visible space.
  - People will attempt to interact with anything that might possibly be clickable.
  - Standard UI components are understood to be interactive - use them!
  - Different text color, 3D and icons all invite interaction
  - Mobile devices - no hover for touchscreens, consider lefties by making interfaces reversible, don't make people reach over the interface and obstruct their view
- Learnable
  - Even interfaces that are easy to use may require learning
  - We learn behaviors from experiences - across the web, devices, and real-world places and objects
  - Be careful with gesture on touchscreen devices.  They can be arbitrary, there are lots of different variations, and they can be difficult to learn.
- Predictable
  - Answers these questions: Where am I?, How did I get here?, What can I do here?, Where can I go from here?
  - Provide a strong sense of place
  - Set the correct expectations
  - It's possible for people to accurately predict the outcomes of their interactions
  - Previews can be used to set user expectations for new or complex interactions - show what can be done and a high-level view of the structure to provide context (much like a map)
- Feedback
  - Every action should produce a visible, understandable, and immediate reaction.
  - Acknowledge interactions to let people know they have been heard (or felt).
  - Failing to acknowledge an interaction can lead to unnecessary repetition of actions and errors (or mistakes.)
  - Error prevention is the best error handling - complement, don't complicate.  Describe what happened, explain why it happened, suggest a fix, never blame the user
  - Examples of feedback: Location - where am I?, Status - what's happening?  Is it still happening?, Future state - what will happen?, Outcomes/results - here's what happened.

### The Five Essential Principles of Interaction Design are Interrelated
- Consistency helps people use what they know
- Visibility of opportunity can invite interaction
- Learning is easier when predictions are accurate
- Feedback facilitates learning

### Interaction Design Considerations
- Remember: you are not designing for yourself
- Understand the goals and needs you're designing for
- Think hard about the design and the experience
- Set the user's expectations for the experience
- Don't hinder, obstruct, or interfere with the experience
- Try to break what you build - be your own worst visitor
- Again: you are not designing for yourself

### Information Architecture
- Information architecture is the creation of organizational and navigational schemes
- A good IA allows people to move through content efficiently and effectively
- It's about more than just finding content
- It's also about educating, informing, and persuading, often in equal doses
- An effective IA is flexible, accommodating growth and adapting to change

### Information Architecture Organization Patterns
- Hierarchical Tree
  - This is a standard structure with and index page and a series of sub-pages
  - It's good for organizing complicated structures that resemble a desktop site or system's structure
  - Multi-faceted navigation structures can present a problem for people using small screens
- Hub and Spoke
  - This gives users a central index (hub).  They'll navigate to the spokes from there.
  - Users can't navigate between spokes.  They have to return to the hub.
  - Good for multi-functional tools within an app - each with its own internal navigation and purpose.
- Nested List
  - This patterns leads users in linear paths to more detailed content
  - Nesting provides a quick, easy method of navigation under stress - it also gives the user a strong sense of where they are within the application
  - Good for apps or sites with singular or closely related topics, but can be a barrier to exploring
- Dashboard (Bento Box)
  - The dashboard displays portions of related tools or content on a main screen
  - This pattern is more suited to desktop or tablet due to its complexity
  - It allows the user to get key information at a glance, but relies heavily on a well-designed UI
  - Good for multi-functional tools and content-based tablet apps that have a similar theme
  - The tablet screen give more space to utilize this pattern well
  - It's critical that you understand how a user will interact with and between each piece of content
- Filtered View
  - This pattern allows the user to filter content in order to create an alternate view of a specific set of information
  - Good for apps or sites with a high volume of content
  - Can be a good basis for magazine style apps or sites, or as a sub-pattern within another navigation pattern
  - Can be trouble for smartphones - filters and faceted search can be difficult to display on a small screen

### Information Architecture Organizing Principles
- Getting to know nodes
  - A node is a basic unit of any information structure
  - Nodes can be as small as a single number or as large as an entire library
  - Nodes allow us to use a common language and a common set of ideas across different problems
  - The organizing principles we use determine how the nodes in an information structre are arranged
  - In other words, it tells us which nodes are grouped together and which ones are kept separate
- Organizing rules of thumb
  - The organizing principles used at the highest levels of the site or app should be those most closely tied to user needs and business objectives
  - Those used at lower levels are usually influenced by feature specs and content requirements
  - Every collection of information has a built-in conceptual structure - and in most cases it has more than one
  - The hard part isn't creating a structure - it's creating the right structure for our objectives and our users' needs
- Organizing with facets
  - Facets are attributes of an information set that provide a flexible set of organizing principles for nearly any kind of content
  - Using the wrong facets can actually be worse than using none at all
  - When users have too many option to sort through, they often can't find anything
  - It's our job - not the user's - to identify the specific attributes of the information that will be most useful, usable, and valuable to our users

### Roles and Processes
- Who does what?  It's common for development teams to have no one explicitly responsible for structure.  In some situations it is the responsibility of a developer or a designer.  Ideally, an information architect is on the team to deal specifically with issues related to information organization and related interaction.  Someone needs to do it!
- How to communicate organization structure? - text outlines (hierarchical structures), graph diagrams (hub and spoke), decision path diagrams, and visual vocabularies are also useful for diagramming structures
- Organization structure needs to be documented and shared with the team

### Structure Takeaways
- Good structure organizes information in a way that provides intuitive access to content
- Structure is created by interaction design, which means presenting information in a way people can understand and interact with it
- Structure is also create by information architecture, which is the combination of organization, labeling, search, and navigation systems within any digital product
- Structure should always be appropriate for the audience and flexible to accommodate change
- Whether you have a specialist to address structure or not isnt important - someone needs to do this work!
- Focus on relationships between content elements: Which categories go together?  Which dont?  How do the steps in an interaction sequence fit together.
