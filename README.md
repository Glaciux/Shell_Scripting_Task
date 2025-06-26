
  
<h1>Creating a TO-DO list in bash scripting</h1>
<h3>First, create a script named todo.sh</h3>
 <h4>
 <p>The script should display a menu with the following options:
   <ul>   
     <li>View all tasks</li>
     <li>Add a new task</li>
     <li>Delete a task</li>
     <li>Exit the program</li>
     <li>Store tasks in a file named todo.txt in the user’s home directory (~/todo.txt)</li>
     <li>Use numbered lines so tasks can be deleted by their number</li>
     <li>Keep running in a loop until the user chooses to exit</li>
   </ul>
 </p>
 </h4>
 <p>Start here 👇🏿</p>
 <ul><li>Create a todo.txt file to store the items</li></ul>
 
 ![todo_file](https://github.com/user-attachments/assets/20227911-859f-4c0c-980d-757c6584c8bd)

 
 <ul><li>View all tasks</li></ul>
 <p>These are tasks that have been added already</p></br>
 
 ![View task](https://github.com/user-attachments/assets/0370338c-08fd-462b-a21e-5e171b17bdf0)

 <ul><li>Add a new task</li></ul>

 ![Add_tasks](https://github.com/user-attachments/assets/ef0255fa-c409-4112-9610-7680543954e5)

 

 <ul><li>Delete a task</li></ul>
 
 ![Delete task](https://github.com/user-attachments/assets/e8320b23-96ad-45cf-9733-fd0681018975)


 <ul><li>Exit the program</li></ul>

  
 ![Exit program](https://github.com/user-attachments/assets/6e6dc944-fe5f-4b01-8d94-00fb1f3ada05)

 <h3>Explaining the script</h3>
 
 <p>The user is prompted to create a "todo.txt file using "-rp":</br>
  -r removes with space</br>
  -p is to prompt input that will be saved in the variable provided</br>
  "! -f" checks if the file exists
 </p>

 ![create todo code](https://github.com/user-attachments/assets/3a7631ef-1e5e-4528-8e60-6c2559ae73ca)

 <p>Use a while loop for repetition until the user exits manually:</br>
  create the activities and prompt a selection in variable "choice"</br>
  -p is to prompt input that will be saved in the variable provided
 </p>

 ![While loop_code](https://github.com/user-attachments/assets/989a2785-3c8d-4793-8c8b-c21a5dcacfd5)


<p>Use case statement to select from the menu</br>
  check if ther's any task in the list by number</br>
  -p is to prompt input that will be saved in the variable provided</br>
  </p>
  
  ![check task_code](https://github.com/user-attachments/assets/6c326518-99f0-4f83-9a56-fc3e8245db1e)

  <p>The user is prompted to add a task
  </p>

  ![create_ and_add_task_code](https://github.com/user-attachments/assets/16afb73f-9767-42cf-b915-2785b43ce6e5)


  <p>The user is prompted to delete a task
  </p>

  ![Delete_code](https://github.com/user-attachments/assets/197395ad-4b26-4b8d-a2a2-cef1baa46ad8)

 <p>exit 0 means the script was executed successfully
  </p>

  ![Exit_code](https://github.com/user-attachments/assets/43bdb5cb-0bac-4de9-9081-ff71e820fac4)
