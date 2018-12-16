# ![alt logo](https://raw.githubusercontent.com/Codeward/Sparkle/master/images/Sparkle-logo.png) Sparkle 

Manage jobs/builds easily into one clear dashboard and get notified. For now it supports just Jenkins.


## Highlights

- All details you want to track on a dashboard
- Get notified about the changes
- Support multiple connections
- Manage jobs / builds within groups
- Dark and Light theme

![alt dashboard](https://raw.githubusercontent.com/Codeward/Sparkle/master/images/Sparkle-v1.2.0-Minimal.png)


## Dashboard

![alt dashboard](https://raw.githubusercontent.com/Codeward/Sparkle/master/images/Sparkle-v1.2.0.png) 

- Favourites on top
  - Mouse click opens Job url
  - Mouse hover shows details
- Grouped Jobs by given group name
  - Mouse click opens Group url
- Latest Job information
  - Job name
  - Job status 
    - Success - Green
    - Failure - Red
    - Aborted - Grey
    - Running - Blue
    - Default - Yellow
  - Started time ago
  - Started by
- Latest 5 Job boxes
  - Mouse click opens job url
  - Mouse hover shows job details
- Sparkle star 
  -  Mouse click adds or removes as favourite
- Notifications on new job events
  - Status information about new started job
  - Dashboard icon to open the dashboard
  - Url icon to open job url
- Reorder Connections and Groups


## Connections

- Add Jenkins Connection
- Reorder Connections and Groups
- Edit Jenkins Connection
- Enable Connection
- Delete Jenkins Jobs on the server 
- Create Groups
- Enable Group
- Delete Group
- Show Jobs in Group
- Edit Group
  - Url to navigate to from dashboard
  - Enabled? To be shown on dashboard
  - Use smart job names? Corresponding characters inside a group will be remove
     - Ex. Feature-Name-Build, Feature-Name-Deploy. Becomes Build, Deploy
  - Select Jobs
  - Search for Jobs


## Settings

- General
  - Select theme
  - Run on start-up
  - Set polling interval
- Notification
  - Notifications for
    - All builds
    - My builds
    - Don't show notifications
  - Notifications when
    - Build starts
    - Build Succeeds
    - Build Fails
    - Build Aborted
  - Play sound when
    - Build starts
    - Build Succeeds
    - Build Fails
    - Build Aborted
- Check for updates