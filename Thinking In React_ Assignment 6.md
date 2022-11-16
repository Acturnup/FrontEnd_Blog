## Plan To-do-list ##


1. Break the UI into a component heirarchy:  
<sub> break down the mock-up that you created into a list of components and describe how you anticipate each component to interact together. </sub>


![image](https://user-images.githubusercontent.com/91300625/202065146-4a0768c6-9fdb-4ca1-b699-844f0e42f12d.png)

 {category: "High Priority", finished: true, task: "Make a reservation to Japango"},
 
 {category: "High Priority", finished: false, task: "Do Front end homework"},



3 and 4. Identify the minimal state representation of your app and identify where state should live:
<sub>identify where you might need to keep state of something; in which component will it be stored, and how will it be accessed? Try to not repeat data in multiple places, and keep the state representation as minimal as possible. </sub>


Peices of the To-Do-List

  - The task text the user has entered
  - The value of the high priority box
  - The value of the users task
  - The filtered list catergory 
  - Heading of the section
  - Heading for each category


Our state is:

 - The task text the user has entered
 - The value of the high priority box
 - The value of the users task

---
I have decided that my state lives in *Filterable To-do-List Table*  
this.state = {filterText: '', highPriority: false} to *Filterable To-do-List Table* constructor to reflect the intial state. 
Next, pass the filterText and High priority to *Task Table* and *Task input bar* as a prop.


Lastly, use the props to filter the rows in the T*ask Table* and set the values of the form fields in *Task Input bar*.

These state's will be rendered *Task Input bar* & *Task Table*.

----- 
Another state lives is *Task Table*
this.state = {checkedBox: false} to *Task Table* constructor to reflect the inital state.
Next, it will pass the checkedBox to *Task Table* and *Task row* as a prop.



