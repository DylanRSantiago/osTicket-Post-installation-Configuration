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
- Assign ALL permissons, tasks, and Knowledge

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
