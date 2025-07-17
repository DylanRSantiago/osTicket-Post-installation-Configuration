# osTicket-Post-installation-Configuration
How to configure osTicket before using it

##  osTicket Setup Instructions

###  Step 1: Acknowledge “User” vs “Admin” Panel
- **Admin:** [http://localhost/osTicket/scp/login.php](http://localhost/osTicket/scp/login.php)  
- **User:** [http://localhost/osTicket](http://localhost/osTicket)

---
##  Step 2: Generate a "Supreme Admin" role
- Admin Panel - Agents - Roles
- Add New Role - `"Supreme Admin"`
- Assign ALL permissions, tasks, and Knowledge

_ _ _

### Step 3: Create "Sys Admins" Department
- Admin panel - Agents - Departments
- Add new Department `"SysAdmins"`
- Click "*Create*"

 _ _ _

 ### Step 4: Configure "Teams"
 - Admin Panel - Agents - Teams
 - Add new team: `"Online Banking"`

_ _ _

### Step 5: Allow anyone to create tickets
- Admin panel - Settings - User Settings
- Uncheck: `"Require registration and login to create tickets"`
- Click "*Save Settings*"

_ _ _
### Step 6: Generate "Agents" (Workers)
- Admin Panel - Agents - Add New
- Generate two accounts *Jane & John*
### Jane Doe: 
- &nbsp;&nbsp;&nbsp;&nbsp;Username: Jane  
-&nbsp;&nbsp;&nbsp;&nbsp;Last name: Doe  
-&nbsp;&nbsp;&nbsp;&nbsp;Email: JaneD@gmail.com  
-&nbsp;&nbsp;&nbsp;&nbsp;Password: Password1  
-&nbsp;&nbsp;&nbsp;&nbsp;Department: Sys Admins  
-&nbsp;&nbsp;&nbsp;&nbsp;Access: Supreme Admin  
-&nbsp;&nbsp;&nbsp;&nbsp;Team: Online Banking

### John Doe: 
- &nbsp;&nbsp;&nbsp;&nbsp;Username: John 
-&nbsp;&nbsp;&nbsp;&nbsp;Last name: Doe  
-&nbsp;&nbsp;&nbsp;&nbsp;Email: JohnD@gmail.com  
-&nbsp;&nbsp;&nbsp;&nbsp;Password: Password1  
-&nbsp;&nbsp;&nbsp;&nbsp;Department: Support  
-&nbsp;&nbsp;&nbsp;&nbsp;Access: Supreme Admin  
-&nbsp;&nbsp;&nbsp;&nbsp;Team: Online Banking

_ _ _

### Step 7: Configure "Users(customers)"
