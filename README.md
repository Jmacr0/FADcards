# FADcards 📝
---
An app that allows theatre nurses to create and share doctor preferences through one source.

```
User Story

AS a theatre nurse
I WANT to create shareable doctor FAD cards
SO THAT staff can prepare required items for surgery

```

```
Acceptance Criteria

GIVEN I am making a set up for surgery
WHEN I select the surgeon and procedure and view the FAD in the app
THEN I can make the set up.

(admin)
GIVEN I want to create a FAD card
WHEN I open the app and select create new FAD
AND assign it to a surgeon
THEN I can publish it live for other staff to view

(admin)
GIVEN I want to update a FAD
WHEN I select the FAD to edit
AND make changes and save
THEN the live version should be updated for others to view

(non admin)
GIVEN I want to suggest updates for a FAD
WHEN I make changes and send this to admin
THEN they can view the suggestion and make changes to the live version 
```
---

### App Details

- Web app -> PWA
- React / Typescript
- Maybe heroku for hosting and DB