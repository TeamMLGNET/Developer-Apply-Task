# Developer-Apply-Task
This is the Developer Apply Task for upcomming Developers in Java for TeamMLG. Good Luck

> [!IMPORTANT]
> You have to do all tasks correctly, to be a possible Developer for TeamMLG.

> [!WARNING]
> If you successfully complete this task, it does not mean that you will automatically be accepted.

**________________________________________**

You have to do following Tasks:

- [ ] Add Rank command with the LuckPerms API
- /rank set PLAYER RANK
- /rank reset PLAYER
- /rank rename OLD_NAME NEW_NAME
  
- [ ] Add a ReportCommand
- with MySQL
- /reports: Lists all reports.
- /report PLAYER REASON: Report Command
  REASON: HACKING, TROLLING, INSULT, NAME

**________________________________________**


**MAVEN:**

```
<dependency> 

         <groupId>net.luckperms</groupId>           <artifactId>api</artifactId>
         <version>5.4</version>
         <scope>provided</scope>

</dependency>
```


**GRADLE:**

```
dependencies {
    compileOnly 'net.luckperms:api:5.4'
}
```


> [!NOTE]
```LuckPerms luckPerms = LuckPermsProvider.get();```
