# Part 6: Using Simple Asset Approval and Approval Paths

In these lessons, you will learn: 

* How to use the simple asset approval workflow
* How to use approval paths
* How to create new approval paths
* How to adjust approval path settings

### 31. Using Simple Asset Approvals

There are two types of asset approvals in Acquia DAM with Workstream:

* You can send assets for simple approval
* Or send them along a predefined approval path

Let’s talk about simple approval first. From a task, or a project, or from within the DAM, choose an asset and click on it to open the asset details. Note the menu of options on the right side of the screen, and choose Approval from these options. From here you can:

* Specify approvers from among those with DAM accounts, OR enter email addresses for partners, executives, or others that do not have a DAM account. It is important to note that if you include two approvers in a simple approval, both of those people must approve the asset.
* Enter an optional message to send to the approver when requesting their approval.
* Next, select the options an Approver has when approving assets:
  * Move the toggle to “Allow download” \(and indicate the allowed format\)
  * Move the toggle to “allow proofing”
  * Move the toggle to “remind” the approver that there is a request pending. You can specify a one-time or repeating reminder, and set the \# of days from approval request to reminder here.
* Once sent for approval, coming back to the image details you will see “approval pending”
* From here, approvers can review the proof, and:
  * Simply approve the asset with no changes, approve the asset with changes, or reject an asset.
  * The “Approve with Changes” and “Reject” options require a comment from the approver.
  * So, let’s approve the asset with no changes.
  * We will cover the details of the Asset Proofing process in a later lesson.
  * Now close out of the asset details to return to the task view. Refresh the page, and you will see an indicator of the asset’s approved status in the corner of the asset.
  * If the approver had approved with changes or rejected this asset, the task would be reassigned to the task owner for completion. Since the approver approved this asset, the task owner can change the status of the task to Completed by clicking on the task status on the task view and selecting the new status.
  * Click on the chat icon to see approval details - you can also send reminders from this screen, add approvers, and cancel approval requests.

### 32. Using Approval Paths

As an Acquia DAM user, you may have access to certain Approval Paths. To send an asset down an approval path:

* Click on the asset from a task, project, or from the DAM to go to its details page.
* Select Send for Approval from the right side menu.
* In the resulting dialog box, select the Approval Path tab.
* Select the appropriate Approval Path from the dropdown list.
* The Approval path may prompt you to complete additional details, such as your desired approvers. Once you complete these, click Send.

### 33. Creating Approval Paths

A more complex and flexible method of gaining asset approval is Approval Paths. Approval paths are pre-set, multi-step approval processes for assets that require it as they go through their stages of development. Approval paths are very specific and controlled, in order to manage confusion around who is asking whom for what type of approval on what asset. Approval paths do away with all of that confusion.

* To access Approval Paths
  * Go to Manage -&gt; Approval Path
  * From this screen, you will see:
    1. Any existing approval paths
    2. Who is allowed to see those approval paths
    3. The frequency of use of each approval path
    4. Whether the approval path was ever used
    5. When was the last time it was used, and
    6. The Completion rate \(or, how many assets made it through to the finish line and got approved using this approval path\)
    7. The "more options" menu will offer the options to edit, duplicate, or delete the approval path.
  * Let’s look at a simple approval path and take it apart. In defining approval paths, you will establish:
    1. The approver \(including multiple approvers\). Choose one of these options, and follow the prompts to indicate approvers. Let’s look at each of these options:
       1. Asset’s original uploader is pretty clear.
       2. Prompt Requester for approvers means that when a user uploads an asset, the DAM will prompt them at that time for the approver\(s\).
       3. Or, Identify approvers now, to choose specific approvers by their DAM account name if they have one, or their email address, if they don’t\).
    2. You will select an approval style \(when multiple approvers are indicated\). The options here are: “Approval is required from all” or “first response wins”.
    3. You will set Approval permissions, including whether the approver can view comments, proof, or download the asset. These are multi-select, so you can choose whichever combination applies to this step.
    4. You can set Approval reminders. Choose the number of days after an approval request to send a reminder. You can also choose whether or not this reminder repeats at the regular interval. So, if you indicate 2 days here, and select Repeat, a reminder will be sent every two days until this approval request is completed.
    5. You can choose to escalate an approval to another party \(a manager for example\) if an approval request is not answered within a specific timeframe. The escalation point can be identified by a DAM account name or an email address, if the escalation point does not have a DAM account.
    6. Finally, auto-decide options can be set. This feature allows you to automatically reject or accept an approval after it ages by a pre-set interval.
    7. You can cancel, save as draft, or publish your new approval path.
    8. Once saved or published, you will return to the list view of approval paths.
    9. From here, you can edit, delete, or duplicate your approval path as needed.
    10. Let’s edit the approval path, so I can show you where you can find Settings.

### 34. Approval Path Settings

* Once you have created an approval path, you have some flexibility related to its settings. To access Settings, Choose an approval path and choose Edit from the more options menu. This will take you to the Edit view of the approval path.
* In the lower left corner, click on Settings.
  * The first setting is who can view this approval path. Your options are Anyone, or specific groups that you allow. Choose one or more of the groups as needed.
  * The second setting is related to behaviors when a new version of an existing asset is uploaded. Options are restarting the approval path from the beginning, restarting this step in the approval path, or doing nothing.
    1. You may want to choose “restart this step” or “restart the approval path from the beginning” if there are lots of changes, possible confusion, or if, for example, legal needs to approve any changes to the final asset.
  * And finally, this setting is related to behavior on final approval of assets. Do you want to set all Inactive assets to Active on final approval? Doing this would make all assets related to the campaigns using this Approval Path active and usable by your team, for use in their other tasks related to the campaign, for example. If you recall a previous lesson, this setting is the counterpart to when we made assets inactive on upload when filling out a request form.
    1. You may want to make assets active to allow brand portal users and others to use them right away, and start downloading them, so there are no more obstacles for them.
    2. On the other hand, if the assets are associated with a deadline, and you do not want them to go early, or if you want to have more active control, you may want to leave assets inactive and activate them manually when you are ready.
* Once you have made or changed your selections, save them by clicking Save changes.

