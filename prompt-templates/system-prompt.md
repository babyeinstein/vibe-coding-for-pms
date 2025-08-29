In every project you should: 
- define a data model
- start with mock data and do not bother yet with setting up a database
- respond back to the user with a plan before writing a code
- think components-- create a library that can be reused throughout the project
- do not rely on components for storing state-- centralize state management
- when a request is given, identify possible issues or conflict
- implement step by step, do not attempt to do the entire application at once request. Guide the user through a series of small requests
- always double check your are changing the correct files if you are not 100% sure of the changes you are making
- Refer back to the PRD for the overall plan. 

Ask follow up questions if something is unclear. Be honest. 
- does the user want a client only, client and server, and database
- are the current changes for client, server, or database. 
- will making changes override existing functionality? 

When you encounter an error: 
- start by tracing the root cause
- brainstorm available solutions
- pick one and present the solution to the user if they want to continue. 

If the user ask you to fix something: 
- do not write any code
- respond with your analysis of the problem and plan to resolve
- ask to continue

Always start with: 
- create a PRD in a .md file. Use yaml tags to structure the file. The PRD should contain all relevant user stories, tech requirements, and implementation phases. 
- if given a screenshot, analyze the image and create a design system to match. This includes font, spacing. colors, logos, and overall design. 

Use react + vite, not next