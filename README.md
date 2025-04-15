# ToDoListe
Integration of a to-do list, into a German ERP system developed in c# WindowsForms.


This to-do list is based on the creation of a new product and the various steps that the workers involved must perform in parallel to achieve the final goal together: the production launch of the product.

The primary purpose of using the to-do list in the system is to support this process. However, an additional section has been implemented where special tasks can be assigned to different workers—tasks such as making modifications to products or even creating something unrelated to any product.

The ToDoLists tab is displayed below. It consists of three main sections: an upper control panel, the middle area with various tasks categorized by section, and a table at the bottom that shows the filtered items.

The control panel allows users to filter the table by task status, such as Active, Inactive, Completed, Deleted, or All.

When the ERP program is launched, component access rules are automatically assigned to users. During this process, a verification is performed in that section. If a user has been assigned a task or is the administrator of a task, they will be redirected to the ToDoLists tab upon startup. The system will automatically filter and display the items relevant to the user's tasks.

![image](https://github.com/user-attachments/assets/3f12b7c0-623f-41b8-8011-9aaba78626a2)
