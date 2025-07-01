<h1>ToDoApp Swing GUI</h1>
<br>
This Java program is a To-Do List GUI application built using the Swing library.

<h3>Create the Main Window</h3>
- A JFrame is created with the title "To-Do List".

- Size is set to 400x500 pixels.

- Layout used: BorderLayout.

<h3>Add Input Field</h3>

- A JTextField is added at the top (BorderLayout.NORTH).

- It allows the user to type a new task.

<h3Create the Task List></h3>

- A DefaultListModel<String> is used to manage tasks.

- A JList<String> is linked to this model.

- Tasks appear in a scrollable list (JScrollPane in BorderLayout.CENTER).

<h3> Add Buttons Panel</h3>

- A JPanel is placed at the bottom (BorderLayout.SOUTH).

- Two buttons are added:

- Add Task

- Delete Task

<h3>Add Task Functionality</h3>

- When "Add Task" is clicked:

- The text from the input field is trimmed.

- If not empty, it's added to the task list with a prefix ☐ (unchecked box).

- The input field is then cleared.

<h3>Delete Task Functionality</h3>

- When "Delete Task" is clicked:
  
- The selected task in the list is removed (if one is selected).

<h3>Mark Task as Done (Double Click)</h3>

- A MouseListener checks for double-click on a task.

- If clicked twice:

- If the task starts with ☐, it changes to ☑ (checked box).

- If already ☑, it switches back to ☐.

<h3>Run the Application</h3>

- The main() method calls SwingUtilities.invokeLater() to run the GUI safely in the event-dispatching thread.

</br>
