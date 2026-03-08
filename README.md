### Installtion Guide for our DB 

**1. Create a new database**

1. Open **pgAdmin**
2. Go to **Servers → PostgreSQL → Databases**
3. Right-click **Databases**
4. Click **Create → Database**
5. Enter a name (for example `streaming_system_copy`)
6. Click **Save**
7. Save this file "streaming_system.backup"

 ### AND DON'T OPEN THIS FILE "streaming_system.backup" AFTER DOWNLOAD 

---

**2. Open Restore**

1. Right-click the **new database** you just created
2. Click **Restore...**

---

**3. Select the backup file**

In the Restore window:

* **Format:** `Custom or tar`
* **Filename:** select your `.backup` file

Example:

```
C:\Users\umair\Desktop\streaming_system.backup
```

---

**4. Run restore**

Click **Restore**.

The backup will be imported into the new database.
