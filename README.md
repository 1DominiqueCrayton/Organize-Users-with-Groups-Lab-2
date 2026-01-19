# Organize Users with Groups — Lab 2  
## Add a Group Rule Based on Group Membership

## Objective
Create groups and automatically assign users to them using a rule based on **group membership**.

---

## Scenario
You will create a **Revenue** group and an **Intellectual Property** group.  
Users in the **Executives** group should be automatically added to both groups.

---

## Create Groups

### Step 1
From the Admin Console, go to **Directory > Groups**.

---

### Step 2
Create the following groups:

<p align="center">
  <img width="456" height="59" alt="image" src="https://github.com/user-attachments/assets/95255126-45b4-44d0-9584-72706cf4aee6" />
</p>

<p align="center">
  <img width="1339" height="560" alt="image" src="https://github.com/user-attachments/assets/7bf8abac-0942-447b-994e-6996992298ed" />
</p>

---

### Step 3
Refresh the browser page.

---

## Add a Group Rule Based on Group Membership

### Step 1
From the **Groups** page, select the **Rules** tab.

<p align="center">
  <img width="1058" height="317" alt="image" src="https://github.com/user-attachments/assets/a43474ad-0c3f-44b8-aab2-06482c550c31" />
</p>

---

### Step 2
Add a rule to assign users in the **Executives** group to the **Revenue** and **Intellectual Property** groups:

a. Add a rule named **Group Assignments for Executives**  
b. For the **IF** condition, use a basic condition based on **Group Membership**  
c. In the field that appears, search for and select the **Executives** group  
d. For the **THEN** condition, assign users to the **Revenue** and **Intellectual Property** groups  

<p align="center">
  <img width="1299" height="590" alt="image" src="https://github.com/user-attachments/assets/175c5b69-1eb6-46bd-b70c-c7098d385051" />
</p>

e. Save the rule  
f. For the **Group Assignments for Executives** rule, select **Actions > Activate**

<p align="center">
  <img width="1309" height="647" alt="image" src="https://github.com/user-attachments/assets/f8e2b8bb-035c-497b-865e-d7963059ebf5" />
</p>

---

### Step 3
Verify that the **Revenue** and **Intellectual Property** groups contain the same users as the **Executives** group.

<p align="center">
  <img width="1332" height="627" alt="image" src="https://github.com/user-attachments/assets/462140fd-44a0-4aa9-8e63-509e47816d2b" />
</p>

<p align="center">
  <img width="1315" height="611" alt="image" src="https://github.com/user-attachments/assets/ee17a1ca-e21f-47d3-9cf6-8dee605ff1ff" />
</p>

---

## View the Event Log for a Group

### Step 1
From the **Intellectual Property** group, select **View logs**.

---

### Step 2
Verify that the log includes:
- Users being added to groups successfully  
- The policy rule executing successfully  

<p align="center">
  <img width="1309" height="311" alt="image" src="https://github.com/user-attachments/assets/04d8e85b-b619-4602-9b5e-e1b549fbb10e" />
</p>

<p align="center">
  <img width="1312" height="515" alt="image" src="https://github.com/user-attachments/assets/149dfa05-943a-45c9-83b7-358a46641ab4" />
</p>

<p align="center">
  <img width="1319" height="302" alt="image" src="https://github.com/user-attachments/assets/c8dfd345-591a-4382-9874-6289f410785f" />
</p>

<p align="center">
  <img width="1311" height="452" alt="image" src="https://github.com/user-attachments/assets/e910804a-1938-4dab-8ae4-6df50fb8ad04" />
</p>
